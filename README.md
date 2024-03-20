This repository contains a Solidity smart contract for string manipulation and a React web application to interact with the deployed contract.

Smart Contract
The smart contract is written in Solidity and provides two main functions:

length: This function takes a string as input and returns the length of the string as an integer.

concatenate: This function takes two strings as input and returns the concatenation of both strings as a new string.

The contract is located in the Strings.sol file.

Web Application
The web application is a simple user interface developed in React that allows users to interact with the smart contract deployed on the blockchain network. The web application includes two main sections:

Length: In this section, users can input a string and calculate its length using the length function of the smart contract.

Concatenate: In this section, users can input two strings and concatenate them using the concatenate function of the smart contract.

The web application utilizes the web3 library to interact with the blockchain network and Strings.json to access the ABI interface of the smart contract.
