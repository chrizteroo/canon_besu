# Canon
A Hyperledger Indy replacement using Ethereum


Steps
1. Check to verify if nodejs is installed
2. Open terminal
3. Create a new folder and give it a name
4. git clone https://github.com/VeriDID/Canon.git
5. cd to canon
6. npm init
7. npm install --save-dev hardhat
8. npx hardhat
9. choose create an empty hardhat.config.js
NOTE: Since the entry point is index.js Hardhat.config.js will be changed later to index.js
10. npm install --save-dev @nomicfoundation/hardhat-toolbox
11. npm install web3 web3-eea fs solc
12. change hardhat.config.js to index.js
13. create a new folders and give it a names
a. private_tx.js
b. compile_deploy_eth_sendTransaction.js
c. compile_deploy_web3_eth_sendTransaction.js
d. compile_deploy_web3_quorum_priv_generate.js
e. compile_deploy_web3eea_eaasendraw.js
f. configure .env
g. npm install dotenv
14. specify the path to the for --genesis file
example: besu --data-path=/path/to/data-dir --genesis-file=/path/to/genesis.json
15. npm install besu
16. To run the script 
17. node start-private-network.js







# PRIVATE_NETWORKS
