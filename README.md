# Joint Savings

### Background

A fintech startup company has recently hired you. This company is disrupting the finance industry with its own cross-border, Ethereum-compatible blockchain that connects financial institutions. Currently, the team is building smart contracts to automate many of the institutions’ financial processes and features, such as hosting joint savings accounts.

To automate the creation of joint savings accounts, you’ll create a Solidity smart contract that accepts two user addresses. These addresses will be able to control a joint savings account. Your smart contract will use ether management functions to implement a financial institution’s requirements for providing the features of the joint savings account. These features will consist of the ability to deposit and withdraw funds from the account.

### What You're Creating

* The completed Solidity `JointSavings` smart contract.

* A folder named `Execution_Results` that contains at least eight images. These images should confirm that the deposit and withdrawal transactions, which are designed to test the `JointSavings` functionality in the Remix  VM (London), worked as expected.

### Instructions

The steps for this homework are divided into the following sections:


#### Step 1: Create a Joint Savings Account Contract in Solidity


#### Step 2: Compile and Deploy Your Contract in the London VM


#### Step 3: Interact with Your Deployed Smart Contract
---
<br>
<br>


![alt text](<setup account 1 and account 2.png>)

Added the addresses to account 1 and account 2. We will be using these two addresses to send and recieve transactions.

<br>
<br>
<br>
<br>



![alt text](<deposited 1 ether as wei.png>)
In this transaction I deposited 1 Ether as wei:

transaction hash:	0xb4bfa6d64ba00d96ad79e5144c35da650a22d9ee0474ed8e9c98189ca70b7a9a

block hash:	0xcb35b1c88a2333aa7199403f38c4d59b04934d0e23030a343ed51f9861e7bb37
block number:
3

from:
0x5B38Da6a701c568545dCfcB03FcB875f56beddC4

to: 0xd9145CCE52D386f254917e481eB44e9943F39138

gas: 
49897

transaction cost:	
43388 gas 

execution cost: 22324 gas 
<br>
<br>




<br>
<br>
<br>
<br>


![alt text](<deposited 10 ether as wei.png>)
In this transaction I deposited 10 Ether as wei:

transaction hash:	0xcecfe71c484ef3ca022d25188f4eaf5565c3f49db250229cdde288a0e3cfb4d3

block hash:	0x84d5c7284804e0f8bc8480138b44591742c1a08a338d68fe4932dc8b6bfb5098

block number:	
4

from:	0x5B38Da6a701c568545dCfcB03FcB875f56beddC4

to: 
0xd9145CCE52D386f254917e481eB44e9943F39138

gas:
30232 

transaction cost:	
26288 gas 

execution cost:	5224 gas 


<br>
<br>
<br>
<br>

![alt text](<deposited 5 ether.png>)
In this transaction I deposited 5 Ether as wei:

transaction hash: 0x04691df53cca2a4844abdd09f4c6fd1d18814c6bf627b2b4749b5cab2a0b8c2e

block hash: 0x0e80700c6e09b589e25ede91291c563604f20c8f36b59872cd4d60585518066e


block number:
5

from:
0x5B38Da6a701c568545dCfcB03FcB875f56beddC4

gas: 30232

transaction cost: 26288 gas 

execution cost	5224 gas 

<br>
<br>
<br>
<br>




![alt text](<widthdrew 5 ether to account1.png>)
Widthdrew 5 Ether into the address of account1.

<br>
<br>

![alt text](<widthdrew 10 ether into account2.png>)
Widthdrew 10 Ether into account2.


<br>
<br>


![alt text](<contract balance after widthdrawing.png>)
This is the contract balance After sending a total of 15 Ether into account1 and account 2. We now have a remaining balance of about 1 Ether: 

from:	0x5B38Da6a701c568545dCfcB03FcB875f56beddC4

to:
0xd2a5bC10698FD955D1Fe6cb468a17809A08fd005

execution cost:
2371 gas

decoded output	{
"0": "uint256: 999999999999999995" }

<br>
<br


![alt text](<last to widthdraw address.png>)
The last address that made a widthdrawl was account 2. His address was:

0x7A1f3dFAa0a4a19844B606CD6e91d693083B12c0


<br>
<br


![alt text](<last to widthdrawl amount.png>)
Account 2 was the last person that made a widthdrawl and the amount was 10 Ether or 10000000000000000000 wei.