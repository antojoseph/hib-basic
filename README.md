# hib-basic (sample)

This repository contains multiple sub-projects, each with its own specific instructions. Please refer to the README files inside each folder for detailed information:

 ## How to Run

- [HelloWorld](helloworld/hello_foundry/README.md)
  ```sh
  forge test
  ```
- [Overflow](overflow/README.md)
    ```sh
    forge test --contracts ./src/test/Overflow.sol -vvvv
    ```
- [Reentrancy](reentrancy/re-entrancy.md)
    ```sh
    forge test --contracts ./src/test/Reentrancy.sol -vvvv
    ```
- [Uninitialized](unInitialized/README.md)
    ```sh
    forge test --contracts ./src/test/Uninitialized.sol -vvvv
    ```
- [Visibility](Visibility/README.md)
    ```sh
    forge test --contracts ./src/test/Visibility.sol -vvvv
    ```

