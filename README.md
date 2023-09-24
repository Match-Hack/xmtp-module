# NextJs **XMTP module**

This repository contains an XMTP module for NextJs. It allows you to use some XMTP functionalities in your own NextJs application.

## What is XMTP?
XMTP SDKs allows Web3 users to send messages between blockchain accounts within DApps. The XMTP messaging API client handles the following functions:

1. Authenticating users through their owned and controlled XMTP identity.
2. Ensuring end-to-end encryption for messages owned and controlled by the user.
3. Offering an interoperable inbox accessible across applications developed using XMTP.
4. Transmitting messages to the increasingly decentralized XMTP network.<br>
   
More information about XMTP can be found [here](https://xmtp.org/) and here is their [documentation](https://xmtp.org/docs/introduction)
## Installation
- Install nodeJs 18
- Run: ```npm install```
- Start the server by running ```npm run dev```

## Usage
Once the server is up and running, it will automatically try to connect to Metamask and start listening for new XMTP messages. <br>
You can send XMTP messages to the `receiver` address. If this address is not registered, an alert is displayed. <br>