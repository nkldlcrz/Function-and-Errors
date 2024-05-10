# SmartContract: Implementing require(), assert(), and revert()

## Function and Errors 

This smart contract demonstrates the usage of `require()`, `assert()`, and `revert()` statements for error handling and ensuring proper contract behavior.

## Description

This Solidity smart contract provides examples of how to use `require()`, `assert()`, and `revert()` for validating user input, checking internal assumptions, and preventing critical errors. Understanding these statements is essential for writing robust smart contracts.

## Functions and Errors

The contract includes three functions that showcase the use of the mentioned statements:

* **requireExample(uint256 _value):** This function validates user input (`_value`). It ensures that the input is less than or equal to 10. If not, the transaction is reverted with a clear error message ("Input value must be less than or equal to 10").
* **assertExample():** This function calculates the sum of `x` and `y` (always 30 in this example). An assertion verifies the expected result (30). If the assertion fails, the transaction is reverted with a generic error message, indicating a potential bug in the code logic.
* **revertExample():** This function prevents division by zero. If the divisor (`b`) is zero, the transaction is reverted with an informative message ("Divisor cannot be zero").

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

  
