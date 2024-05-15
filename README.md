# SmartContract: Implementing require(), assert(), and revert()

## Function and Errors 

This smart contract demonstrates the usage of `require()`, `assert()`, and `revert()` statements for error handling and ensuring proper contract behavior.

## Description

This Solidity smart contract provides examples of how to use `require()`, `assert()`, and `revert()` for validating user input, checking internal assumptions, and preventing critical errors. Understanding these statements is essential for writing robust smart contracts.

## Description Each Statement and Function

Set Item Prices:

Once the contract is deployed, you can set prices for different items.
In the "Deployed Contracts" section, find the deployed instance of MysmartcontractItemPricer.
Expand the contract instance to reveal its functions.
Find the setItemPrice function and provide the item name and price as arguments.
Click on the "Transact" button to execute the function.

Get Item Prices:

You can retrieve the price of an item using the getItemPrice function.
Enter the name of the item for which you want to check the price in the input field provided.
Click on the "Call" button to execute the function and view the result.

Check Price Validity:

Use the checkPriceValidity function to verify that the price of an item is valid.
Enter the name of the item for which you want to check the price validity.
Click on the "Call" button to execute the function.
If the price is set for the item and not unrealistically high, the function call will succeed. Otherwise, it will revert with an error.

Reset Item Prices:

If needed, you can reset the price of an item to zero using the resetItemPrice function.
Enter the name of the item for which you want to reset the price.
Click on the "Transact" button to execute the function.

  
## License

MIT License

## Author/s

* Nicole D. Bautista (8210179@ntc.edu.ph)
