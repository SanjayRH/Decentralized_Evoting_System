# E-voting-system
This application is made using Node.js and truffle framework on Ethereum Blockchain

## Dependencies
Install these prerequisites:
- Node.js: https://nodejs.org
- **Install Ganache** from: https://www.trufflesuite.com/ganache
- **Install Metamask** (a Chrome Extension) from: https://metamask.io/
## Setting up dependencies
- Launch Ganache application on your system. Go to QuickStart Ethereum.
- Download the code.
- On command line type: **npm install**. With this all the dependencies of the file get installed.
- Make sure Ganache application runs throughout while using the application.
- Now setup metamask Chrome Extension to get results on client side.
- Enter seed phrase and save it somewhere as it will be used to recover your password.
- Enter password for metamask that will be used to unlock.
- Set up new custom RPC connection.
- Assign any network name eg: New RPC
- Enter New RPC URL which should be same as the one that is on your Ganache application under RPC server.
- Also assign Chain ID by entering hexadecimal value of your network ID used in Ganache application. Click on Save.
- New RPC connection gets created on metamask.
## Command line instructions
- Make sure truffle is there on the system. Use  **npm install truffle --save** if not there. 
- Also check truffle version with **truffle --version**
- Now compile contracts using command on command line: **truffle compile**
- Test smart contracts using command on command line: **truffle test**
- Deploy the smart contracts using command on command line:
- For the first usage: **truffle migrate**
- For next usage: **truffle migrate --reset**
- Once the smart contracts are deployed on blockchain. Then we should view them on client side.
- Run the blockchain server using: **npm run dev**
- If issue persists: then run **npm install lite-server@2.3 --save-dev** 
- and then **npm run dev**
