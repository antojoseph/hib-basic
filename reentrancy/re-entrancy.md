# Getting Started

Follow the instructions below to get started with testing the reentrancy vulnerability.

## Installation

1. **Install Foundry**: Follow the [Foundry installation guide](https://book.getfoundry.sh/getting-started/installation.html).
2. **Clone and Install Dependencies**: Run the following command to clone the repository and install submodules:
    ```sh
    git submodule update --init --recursive
    ```

## Testing the Vulnerability

To test the reentrancy vulnerability, run the following command:
```sh
forge test --contracts ./src/test/Reentrancy.sol -vvvv
```

Credits
