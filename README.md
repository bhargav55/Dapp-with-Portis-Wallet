# Dapp with Portis Wallet

This is a simple Dapp that uses Portis Wallet for better user experience while building Decentralized applications on Matic Network.

Portis is a web-based wallet built keeping easy user-onboarding in mind. It comes with a javascript SDK that integrates into the DApp 
and creates a local wallet-less experience for the user. Further, it handles setting up the wallet, transactions and gas fees. 
Like Metamask, it is non-custodial - users control their keys, Portis just stores them securely. 
But, unlike Metamask, it is integrated into the application and not the browser. Users have their keys associated with their login id and passwords.

  1. Deploy a sample contract to matic mumbai testnet.

     Congfiguration for matic testnet is given in truffle-config.js
     
  2. Register your Dapp in Portis Dashboard.
  
     The link for the dashboard is given below:
     https://dashboard.portis.io/
     
  3. Integrate Portis with Dapp
  
     Here is the link on how to integrate Portis with Dapp
     https://docs.matic.network/docs/develop/wallets/portis
     
  4. Run the application
  
     npm start
     
     The application tries to invoke the transaction i.e., invoke contract method. But you dont need metamask installed in your browser and pay for the gas.
     as Portis is integrated into the application and not the browser.
