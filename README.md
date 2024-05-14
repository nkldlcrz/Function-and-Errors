# SmartContract: Implementing require(), assert(), and revert()

## Function and Errors 

This smart contract demonstrates the usage of `require()`, `assert()`, and `revert()` statements for error handling and ensuring proper contract behavior.

## Description

This Solidity smart contract provides examples of how to use `require()`, `assert()`, and `revert()` for validating user input, checking internal assumptions, and preventing critical errors. Understanding these statements is essential for writing robust smart contracts.

## Description each Statement and function

The contract includes three functions that showcase the use of the mentioned statements:

setRate Function: Require Statement
** *This function sets the rate to the provided _newRate.
** *It uses the require statement to ensure the new rate is greater than the current rate.
** *The error message has been changed to "New rate must exceed current rate".

checkRateIfFifthy Function: Assert
** *This function uses assert to check if the rate is exactly 10.
** *If the rate is not 10, it will fail the assertion and revert the transaction.

resetRate Function: Revert
** *This function resets the rate to zero.
** *It uses an if statement with revert to ensure the rate is not already zero before resetting it.
** *If the rate is already zero, it will revert with the message "Rate is already zero".
  
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

  
