# SmartContract: Implementing require(), assert(), and revert()

## Function and Errors 

This smart contract demonstrates the usage of `require()`, `assert()`, and `revert()` statements for error handling and ensuring proper contract behavior.

## Description

This Solidity smart contract provides examples of how to use `require()`, `assert()`, and `revert()` for validating user input, checking internal assumptions, and preventing critical errors. Understanding these statements is essential for writing robust smart contracts.

## Functions and Errors

The contract includes three functions that showcase the use of the mentioned statements:

* **require(_i > 10, "Input must be greater than 10"); This is a require statement. It ensures that the condition _i > 10 is true, otherwise it will revert the transaction and display the error message "Input must be greater than 10".

  
* **if (_i <= 10) { revert("Input must be greater than 10"); }: This is an if statement that checks if the condition _i <= 10 is true. If it is true, it will execute the code inside the curly braces.

  
* **function testAssert() public view {: This line starts the declaration of the function testAssert. It is declared as public, meaning it can be called from outside the contract, and view, indicating that it doesn't modify the contract's state.
* **assert(num == 0);: This line contains an assert statement. It checks if the value of the state variable num is equal to 0. If the condition evaluates to false, the transaction will revert, reverting any state changes, and consuming all gas.
  
## Understanding the Statements

* **`require()`:** Enforces conditions during function execution. If the condition fails, the transaction is reverted with a custom error message, providing valuable feedback for troubleshooting.
* **`assert()`:** Verifies internal assumptions within the code that should always hold true. If the assertion fails, the transaction is reverted with a generic error message, indicating a potential bug in the code logic.
* **`revert()`:** Allows manual transaction reversal with a custom error message. It offers more flexibility compared to `require` for tailored error handling within a function.

## License

MIT License

## Author/s

* Nicole D. Bautista (8210179@ntc.edu.ph)

## Getting Started 

This section would typically explain how to deploy the contract to a blockchain network and interact with its functions, but it might not be necessary for a purely educational contract like this one.  


* **Interaction:**
    * Provide step-by-step instructions on how to interact with each function, including any required inputs or expected outputs.
    * Use code blocks to demonstrate commands.

## Help 

This section could provide guidance on troubleshooting common issues or using the contract effectively. 

  
