# Smart Contracts btween Company and Employees:

*In this project I'll be creating smart contract to auotamate my company finances with employees using Solidity.* **My task is to create the following contracts:**

* Associate level profit splitter
* Profit Splitter for different tiers of employees.
* Distributing Company Shares for employees based on a "deferred equity incentive plan"


# Test the level 1 contract
### How did it work?
* I used Remix IDE to work in Solidity and made three contracts seperately. The link to my contract files are stated below: 
* [`AssociateProfitSplitter.sol`](Starter-Code/AssociateProfitSplitter.sol)
* *There are three employees who'll be paid equally on this smart contract called AssociateProfitSplitter. There are three functions on this sol file:*

1- Balance Function: This serves as a test function of sorts.
2- Deposit Function: This function is made for the onwer to make calls.
3- Fallback Function: This will ensure that the logic in deposit function is exceuted properly. 
#### MetaMask Confirmation Screenshot
['MetaMask Test'](Images/level_1_Metamask.png)

#### Ganache Confirmation Screenshot
['Ganache Test'](Images/level_1_Ganache.png)

#### Solidity Confirmation Screenshot
['Solidity Test'](Images/level_1_Solidity.png)


# Test the level 2 contract
* In this contract the profits are distributed based on the percentage share for different tiers of employees (CEO, CTO, and Bob). The percentages are allocated and functions are made. THe link to my contract files are stated below:
[`TieredProfitSplitter.sol`](Starter-Code/TieredProfitSplitter.sol)

#### MetaMask Confirmation Screenshot
['MetaMask Test'](Images/level_2_Metamask.png)

#### Ganache Confirmation Screenshot
['Ganache Test'](Images/level_2_Ganache.png)

#### Solidity Confirmation Screenshot
['Solidity Test'](Images/level_2_Solidity.png)


# Test the level 3 contract
* In this contract the company is making sure to distribute 250 shares per employee every year. This contract is to make sure that employees stay with the company if they want their shares in full. 
* [`DeferredEquityPlan.sol`](Starter-Code/DeferredEquityPlan.sol)