# demux-cli ![EOSIO Alpha](https://img.shields.io/badge/EOSIO-Alpha-blue.svg)

CLI tool for starting, developing, and interacting with [demux-js](https://github.com/EOSIO/demux-js) projects.

## Installation

```bash
$ yarn global add demux-cli
```   
Or alternatively,
```bash
$ npm install -g demux-cli
```

## Usage

To see usage documentation, simply call `demux` with no arguments:
```bash
$ demux

Usage:

    demux init
        Initializes a new demux project in the current directory via
        initialization wizard. 

    demux generate updater [contract_name] [action_name] [handler_version]
        Adds a new updater, automatically wiring all needed exports.
        If any arguments are omitted, questions will be asked for the needed
        information.
        
    demux generate effect [contract_name] [action_name] [handler_version]
        Adds a new effect, automatically wiring all needed exports.
        If any arguments are omitted, questions will be asked for the needed
        information.
        
    demux generate [migration] [migration_name] [migration_sequence]
        Adds a new migration. automatically wiring all needed exports.
        If any arguments are omitted, questions will be asked for the needed
        information. The command requires that you are using the
        MassiveActionHandler, provided by demux-postgres.
```

## Contributing

[Contributing Guide](./CONTRIBUTING.md)

[Code of Conduct](./CONTRIBUTING.md#conduct)

## License

[MIT](./LICENSE)

## Important

See LICENSE for copyright and license terms.  Block.one makes its contribution on a voluntary basis as a member of the EOSIO community and is not responsible for ensuring the overall performance of the software or any related applications.  We make no representation, warranty, guarantee or undertaking in respect of the software or any related documentation, whether expressed or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose and noninfringement. In no event shall we be liable for any claim, damages or other liability, whether in an action of contract, tort or otherwise, arising from, out of or in connection with the software or documentation or the use or other dealings in the software or documentation. Any test results or performance figures are indicative and will not reflect performance under all conditions.  Any reference to any third party or third-party product, service or other resource is not an endorsement or recommendation by Block.one.  We are not responsible, and disclaim any and all responsibility and liability, for your use of or reliance on any of these resources. Third-party resources may be updated, changed or terminated at any time, so the information here may be out of date or inaccurate.  Any person using or offering this software in connection with providing software, goods or services to third parties shall advise such third parties of these license terms, disclaimers and exclusions of liability.  Block.one, EOSIO, EOSIO Labs, EOS, the heptahedron and associated logos are trademarks of Block.one.

Wallets and related components are complex software that require the highest levels of security.  If incorrectly built or used, they may compromise users’ private keys and digital assets. Wallet applications and related components should undergo thorough security evaluations before being used.  Only experienced developers should work with this software.
