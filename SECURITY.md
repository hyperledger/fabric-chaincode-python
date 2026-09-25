# Security Policy

We take the security of `fabric-chaincode-python` seriously. This document describes how to report a vulnerability and how we handle it.

## Reporting a Vulnerability

Please **do not** open a public issue for security vulnerabilities. Instead, report them privately so they can be addressed before disclosure.

To report a vulnerability, contact the project maintainers directly. See [MAINTAINERS.md](MAINTAINERS.md) for contact information.

Vulnerabilities in the broader Hyperledger Fabric ecosystem should be reported in accordance with the
[Hyperledger Fabric security policy](https://github.com/hyperledger/fabric/blob/main/SECURITY.md).

## Responsible Disclosure

We follow a coordinated disclosure process:

1. You report the vulnerability privately to the maintainers.
2. The maintainers acknowledge receipt and begin an assessment.
3. A fix is prepared, tested, and released.
4. The vulnerability is disclosed publicly only after the fix is available.

We ask that you keep the details confidential until a fix has been released.

## Scope

- The Python chaincode shim and contract API implemented in this repository (`src/`).
- Supporting build and test tooling under `scripts/` and `tests/`.

Third-party dependencies are outside this repository's direct control; please report issues with them to their respective projects.

## Supported Versions

Security fixes are provided for the latest stable release and, where feasible, recent releases still under active maintenance. See [RELEASING.md](RELEASING.md) for the release and support policy.

## Thanks

We appreciate responsible security researchers who help us improve the security of this project.
