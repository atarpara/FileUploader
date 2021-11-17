<p align="center">
Decentralize Storage 
</p>
<p align="center">
<img src="src\dapp.png" title="Storage">
</p>


## Features
  - [X] Built for Ethereum using [Web3](https://github.com/ethereum/web3.js/).
  - [X] Deployable on [IPFS](http://github.com/ipfs).
  
  
  
## Prerequirement

Ganache app [Download Here](https://trufflesuite.com/ganache)

MetaMask Extension on Your Broswer [Download Here](https://metamask.io/) 

Ganache Account Import In MetaMask [Full Guide](https://www.linkedin.com/pulse/using-ganache-ethereum-emulator-metamask-farhan-khan)


## Setup


1. Clone Repository

    ```sh
    $ git clone https://github.com/Atarpara/FileUploader.git
    $ cd FileUploader
    ```

2. Install Dependencies

    ```sh
    $ npm install
    ```
3. Open the Ganache App

    ```
    goto quick start or workspace
    goto contract option
    Link the truffle project
    Add path clonerepo\FileUploader\truffle-config.js
    ```

    
4. Complier and Deploy smartcontract on Ganache Account
    ```sh
    $ truffle migrate --reset
    ```

5. Run Fileuploader

    ```sh
    $ npm run start
    ```
