# Joint-Savings

Background and Overview

A fintech startup company has recently hired you. This company is disrupting the finance industry with its own cross-border, Ethereum-compatible blockchain that connects financial institutions. Currently, the team is building smart contracts to automate many of the institutions’ financial processes and features, such as hosting joint savings accounts.

To automate the creation of joint savings accounts, you’ll create a Solidity smart contract that accepts two user addresses. These addresses will be able to control a joint savings account. Your smart contract will use ether management functions to implement a financial institution’s requirements for providing the features of the joint savings account. These features will consist of the ability to deposit and withdraw funds from the account.

Instructions

Create a Joint Savings Account Contract in Solidity

Compile and Deploy Your Contract in the JavaScript VM

Interact with Your Deployed Smart Contract

Step 2: Compile and Deploy Your Contract in the JavaScript VM
Compile your smart contract. If an error occurs, review your code, and make the necessary changes for a successful compilation.

In the Remix IDE, navigate to the “Deploy & Run Transactions” pane, and then make sure that “JavaScript VM” is selected as the environment.

Click the Deploy button to deploy your smart contract, and then confirm that it successfully deployed.

Step 3: Interact with Your Deployed Smart Contract
Now that your contract is deployed, it’s time to test its functionality! After each step, capture a screenshot of the execution, and then save it in a folder named Execution_Results. You’ll share this folder with your final submission.

To interact with your deployed smart contract, complete the following steps:

Use the setAccounts function to define the authorized Ethereum address that will be able to withdraw funds from your contract.

NOTE
You can either use the following Ethereum addresses or create new, dummy addresses on the Vanity-ETHLinks to an external site. website, which includes an Ethereum vanity address generator.

Dummy account1 address: 0x0c0669Cd5e60a6F4b8ce437E4a4A007093D368Cb
Dummy account2 address: 0x7A1f3dFAa0a4a19844B606CD6e91d693083B12c0
Test the deposit functionality of your smart contract by sending the following amounts of ether. After each transaction, use the contractBalance function to verify that the funds were added to your contract:

Transaction 1: Send 1 ether as wei.

Transaction 2: Send 10 ether as wei.

Transaction 3: Send 5 ether.

NOTE
