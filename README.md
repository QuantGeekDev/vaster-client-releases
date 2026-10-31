# Vaster client downloads

This repository distributes the portable Vaster renter CLI and Python SDK.
It contains signed client artifacts and installation instructions. Vaster control,
marketplace and supplier implementation repositories remain private.

Use the versioned [releases](https://github.com/QuantGeekDev/vaster-client-releases/releases).
Alpha versions require renter API protocol 1; client installation alone does not
qualify a host, managed workload, payment or external-marketplace booking boundary.

Download the CLI release's install.py and run it with an explicit --version.
Python 3 and Cosign 3 are required. SDK releases include install_sdk.py (Python
3.11+) and a complete hello.py example. Follow https://vaster.cloud/docs/clients/install.

The verifiers bind the exact source workflow, tag, protocol, target and hashes.
CLI signer: QuantGeekDev/vaster-host/.github/workflows/client-release.yml.
SDK signer: QuantGeekDev/vaster-control/.github/workflows/python-client.yml.
Issuer: https://token.actions.githubusercontent.com. Private keys remain local.
Never put API keys in command arguments, public issues or logs.
