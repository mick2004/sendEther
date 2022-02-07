Send Ethereum Using Ethers.js

The ethers.js library aims to be a complete and compact library for interacting with the Ethereum Blockchain and its ecosystem. It was originally designed for use with ethers.io and has since expanded into a more general-purpose library.

This tutorial demonstrates how to send ethreum in automated way using ether.js

Steps To use

1.Checkout the project
2.Edit .env file 
RINKEBY_PRIVATE_KEY -> Your Rinkeby private key
RINKEBY_URL -> Rinkeby URL end point
TO_ADDR ->Address where you wish to send ether


3.Initialise js libraries
a)Install Node.js
For mac you can use 
brew install nodejs
b)cd into sendEther you checked out
c)npm init -y
d)npm install ethers dotenv

4.Run 
node sendEther

5.The program will send ether and give you tx hash

6.You can see transation details on

https://rinkeby.etherscan.io/tx/<<txhash>>
