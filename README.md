# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm install ethers`

### `npm start`
useState: The component uses the useState hook to manage the state of walletAddress, which stores the user's wallet address.

requestAccount: This function requests access to the user's MetaMask wallet using window.ethereum.request. If successful, it sets the walletAddress state with the user's wallet address.

connectWallet: This function is intended to be used to connect to a smart contract using the ethers.providers.Web3Provider after requesting the account.







Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

