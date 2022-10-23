# Smart Contract Development with Truffle
1. Installed truffle by running the following command 

`npm install -g truffle`

2. Initialized the project folder and ran this command to initialize Truffle

``truffle init``

3. Created two smart contracts (Helloworld.sol and Helloworld2.sol) in the contracts folder. Using the following command, compiled both the smart contracts

`truffle compile`

4. Before deploying, created an account on Chainstack, created a public chain project and configured a Ethereum Goerli Testnode. Added the Execution client HTTPS endpoint to truffle-config.js

5. To deploy the smart contracts I created 2_hello_world_migration.js in the migrations folder. Using the following command, deployed the smart contracts

`truffle migrate --network goerli`

6. Wrote test cases to check the smart contracts


