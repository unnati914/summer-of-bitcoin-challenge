## What is a BitCoin?
BitCoin can be considered as a type of cryptocurrency. It was invented in 2009.. There are no physical bitcoins, only balances kept on a public ledger that everyone has transparent access to. All bitcoin transactions are verified by a massive amount of computing power. Bitcoin is very popular and has triggered the launch of hundreds of other cryptocurrencies, collectively referred to as altcoins.  Bitcoin is commonly abbreviated as "BTC." BitCoin can be considered as a leisure, for eg : you pay money to fruit seller that is considered as a trade.



## Hashing Algorithm 
Hashing is the process of mapping digital data of any arbitrary size to data of a fixed size. In simpler words, hashing is a process of taking some information that is readable and making something that makes no sense at all.In this task, the input file that has been given is in the form of hashes.If you take a look at the databases, we will have a limited (but huge) number of possible HASH values, simply because our HASH length is limited.If you understand that the hashing algorithm adheres to the rule where even the smallest change in input data must produce significant difference in output.


## Understanding Blocks
There is a thing which is called ledger and in that there are different blocks which are forming a chain such as linked lists. There is a pointer in the each block which points to next block. 

## Project Understanding (NAIVE APPROACH)
We would be importing csv file with certain constraints and would be reading the data in the file in the given format. We would be sorting fee column and converting it to numpy array. This is a three step process for this project
1. Sort the fee column 
 
2. Store the ids until the cumulative weight doesn't exceed the limit.

3. When creating the block file we must keep track of parent that it should be placed above the current I'd.

Second approach to this problem could be fractional knapsack problem or algorithm

## Tools and Technologies used for the task
Python Language

Windows Operating System 

Blockchain 

Sorting

