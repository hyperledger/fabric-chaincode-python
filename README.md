# Hyperledger Fabric Chaincode Python

![GitHub License](https://img.shields.io/github/license/hyperledger/fabric-chaincode-python)
[![OpenSSF Best Practices](https://bestpractices.coreinfrastructure.org/projects/14928/badge)](https://bestpractices.coreinfrastructure.org/projects/14928)
[![OpenSSF Scorecard](https://api.scorecard.dev/projects/github.com/hyperledger/fabric-chaincode-python/badge)](https://scorecard.dev/viewer/?uri=github.com/hyperledger/fabric-chaincode-python)

[![Python Version](https://img.shields.io/pypi/pyversions/fabric-chaincode-python.svg?cache=1)](https://pypi.org/project/fabric-chaincode-python/)
[![GitHub Actions](https://github.com/hyperledger/fabric-chaincode-python/workflows/CI/badge.svg)](https://github.com/hyperledger/fabric-chaincode-python/actions?query=workflow%3ACI)
[![GitHub Release](https://img.shields.io/github/v/release/hyperledger/fabric-chaincode-python.svg)](https://github.com/hyperledger/fabric-chaincode-python/releases)

This is a Python based implementation of Hyperledger Fabric chaincode shim and contract
API, which enables development of smart contracts using the Python language. Chaincodes
(smart contracts) written in Python run inside Hyperledger Fabric peers.

## Documentation

- [API documentation](https://hyperledger.github.io/fabric-chaincode-python/)
- [Full Hyperledger Fabric documentation](https://hyperledger-fabric.readthedocs.io/)
- [Samples repository](https://github.com/hyperledger/fabric-samples)

## Project structure

```
src/
├── fabric_contract_api/   Python Contract API
└── fabric_shim/           Python chaincode shim (Fabric 2.x)
```

- **fabric_contract_api** - Contains the Python contract API used to write smart contracts with the high-level contract programming model.
- **fabric_shim** - Contains the Python classes that implement the chaincode shim API and the way to communicate with Fabric peers.

## Building and testing

Make sure you have the following prereqs installed:

- [Python](https://www.python.org/) 3.11 or later
- [pip](https://pip.pypa.io/en/stable/)

Create a virtual environment and install the development dependencies:

```
python3 -m venv .venv
source .venv/bin/activate
pip install -e . -r requirements-dev.txt
```

Run the unit tests:

```
pytest tests/
```

## Contributing

We welcome contributions to the Hyperledger Fabric project in many forms. If you are
interested in contributing updates to this project, please start with the
[contributing guide](CONTRIBUTING.md).

There is also a [release guide](RELEASING.md) describing the process for publishing new
versions.

## Community

- [Hyperledger Community](https://www.hyperledger.org/community)
- [Hyperledger mailing lists and archives](http://lists.hyperledger.org/)
- [Hyperledger Chat](http://chat.hyperledger.org/channel/fabric)
- [Hyperledger Fabric Wiki](https://wiki.hyperledger.org/display/Fabric)
- [Hyperledger Code of Conduct](CODE_OF_CONDUCT.md)

## License <a name="license"></a>

Hyperledger Project source code files are made available under the Apache License,
Version 2.0 (Apache-2.0), located in the [LICENSE](LICENSE) file. Hyperledger Project
documentation files are made available under the Creative Commons Attribution 4.0
International License (CC-BY-4.0), available at
http://creativecommons.org/licenses/by/4.0/.
