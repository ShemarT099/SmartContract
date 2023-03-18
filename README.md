# Introduction

This repository contains code and build functions for my final year project during my time at university

# SmartContract


This atomic swap allows users to agree on a predetermined set of rules before exchanging cryptocurrencies across two different blockchains. 

The owner of a token would deploy a contract onto their blockchain with the details of the exchange such as:

The name of the token 

The amount they want to swap

The secret key

The timelock.

A secret key is provided by the owner which is then turned into a hashlock via Hash.sol. Hash.sol includes a cryptographic function called SHA256, which would turn the string into a an address of type bytes32


# Tools

This Atomic Swap smart ontract was developed on the Remix IDE, and built using the Solidity language.
It has been tested using Truffle-Ganache and MetaMask

Truffle-Ganache is a development envrionment and testing framework that allows users to create their own personal blockchain where smart contracts can be tested before deployment

