# ETH-Explorer to Connect Your Own Private Ethereum Blockchain Network

This is a very basic explorer to show your private chain on the browser. To get the updated version you may visit this link https://github.com/jacktang/explorer-v2

![EthExplorer Screenshot](http://i.imgur.com/NHFYq0x.png)

## License

GPL (see LICENSE)

## Installation steps:

Step 01: 
Install [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git "Git installation") if you haven't already

Step 02: 
Clone the repo 
`git clone https://github.com/etherparty/explorer`
`git clone https://github.com/wahid028/explorer.git`

Step 03: 
Download [Nodejs and npm](https://docs.npmjs.com/getting-started/installing-node "Nodejs install") if you don't have them

Step 04: 
Run `npm start` Start the program. All dependencies will be automatically downloaded

Step 05: 
Visit http://localhost:8000 on your browser. You might get an error message: 
`geth --rpc --rpccorsdomain "http://localhost:8000"`

Step 06: 
Install [geth](https://github.com/ethereum/go-ethereum/wiki/Building-Ethereum "Geth install") and modify the `genesis.json` file to create your own private ethereum blockchain network, then initialize the genesis file and run the below command 
`./geth --datadir "#" --port 30303 --networkid XXXX --rpc --rpcport 8545 --nodiscover --rpccorsdomain "http://localhost:8000" --verbosity 5 console
` 
this command.

Step 07: 
Refresh the page of your browser


