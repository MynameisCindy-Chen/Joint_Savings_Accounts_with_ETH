# Joint Savings Accounts Creation

This assignment is to create a joint saving account along with presentation of transaction betwen two different account addresses. 

The first thing is to creat a smart contract that can accepts two user addresses by using ether to do transaction. These features consist of deposit and withdraw just like bank account with money transaction.

After smart contract being created with solidity, four functions are needed to complete and display ether transaction: withdraw function, deposit function, setAccounts function and default fallback function. Also, relevant variables, variable type and statements are listed for the necessary functions. This smart contract run secussfully without error message. Then I complie and deploy the contract, please see below picture of those transaction.

Here are the display of 2 different account addresses:

I used these 2 accounts to withdraw ETH and accountOne are used to deposit ETH.

![Module_20_Assigment](../Module_20_Assignment/Execution_Results/Two_Accounts_Addresses.PNG)

Please see below results of three transantions on ETH deposit.

- The first transaction is sending 1 ether as wei by using Ethereum Unit Converter.

![Module_20_Assignment](../Module_20_Assignment/Execution_Results/Transaction_1_1ETH.PNG)

- The second transaction is sending 10 ether as wei by using Ethereum Unit Converter, and contract balance shows 11 ETH in total.

![Module_20_Assignment](../Module_20_Assignment/Execution_Results/Transaction_2_10ETH.PNG)

- The third transaction is sending 5 ether, so the final balance is 16 ETH in this smart contract.

![Module_20_Assignment](../Module_20_Assignment/Execution_Results/Transaction_3_5ETH.PNG)

After completing money deposit and I have 16 ETH in my contract, I made 2 transaction to transfer and withdraw moeny to accounnt1 and account 2 seperately.

Here is the result of Transaction A with transfering 5 ETH to account1 from my smart contract:

After transaction A completed, the contract balance is 11 ETH.

![Module_20_Assignment](../Module_20_Assignment/Execution_Results/Send_5ETH_to_accountOne.PNG)

Here is the result of Transaction A with transfering 5 ETH to account1 from my smart contract:

After transaction B completed, the contract balance is 1 ETH. The below picture also shows basic information of last_to_withdraw account address and last_withdraw amount.

![Module_20_Assignment](../Module_20_Assignment/Execution_Results/Send_10ETH_to_accountTwo.PNG)

In general, I am satified with my smart contract. This is what I can do for now from what I learn so far. The only concern is the gas spending which is hard to control.
