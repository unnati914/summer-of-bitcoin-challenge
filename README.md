## What is a BitCoin?
BitCoin can be considered as a type of cryptocurrency. It was invented in 2009.. There are no physical bitcoins, only balances kept on a public ledger that everyone has transparent access to. All bitcoin transactions are verified by a massive amount of computing power. Bitcoin is very popular and has triggered the launch of hundreds of other cryptocurrencies, collectively referred to as altcoins.  Bitcoin is commonly abbreviated as "BTC." BitCoin can be considered as a leisure, for eg : you pay money to fruit seller that is considered as a trade.



## Problem Statement

 1. Read a file mempool.csv, with the format:   txid , fee , weight , parent_txids

 2. We need to output a block of transaction id's which should be less 4000000 (i.e. keep a track of weight)  

3. Condition for a block is transactions can be included only if it's parent transactions have been included before !


## Understanding Blocks
There is a thing which is called ledger and in that there are different blocks which are forming a chain such as linked lists. There is a pointer in the each block which points to next block. 

## Project Understanding (NAIVE APPROACH)

1. Read files using pandas module in python & sort the dataframe maximising the fee & minimising the weight.

2. Check for parent_txid's

3. Use global variables - highest_weight = 4000000 & minimum_weight & check whether the total weight of transactions in a block must not exceed 4,000,000 weight.


Second approach to this problem could be fractional knapsack problem or algorithm

## Tools and Technologies used for the task
Python Language

Windows Operating System 

Blockchain 

Jupyter Notebook

## Description of files for this repo

  sb_README.pdf : Problem Statement

  block_sample.txt : Sample output of Block Transacctions.

  Summer of BitCoin Challenge.ipynb : The Jupyter Notebook containing all the functions & code.

  Main.py : Source Code for the problem

  mempool.csv : Input Dataset for the mempool 
  
  block.txt : output containing Block Transactions.
  
  

