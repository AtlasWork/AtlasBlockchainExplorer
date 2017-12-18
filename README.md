# AtlasBlockchainExplorer V2 based off github.com/etherparty/explorer

![ETHExplorer V2 Screenshot](http://i.imgur.com/wgROAS9.png)

##License

The code in this branch is licensed under GPLv3 (see LICENSE file)

Feel free to modify or reuse the code here.

##Reddit

Discuss this project at: [Reddit Page on /r/atlasblockchain](https://www.reddit.com/r/atlasblockchain/)

##Donations

ETH Address: 0xEa148e8f5266B4264f412eC1E0DE8dfd6eEC0D42

BTC Address: 1DHCfst4g6jsBmxBrbsf6LkDYsrTGCqfTn

##Installation

`git clone https://github.com/AtlasWork/AtlasBlockchainExplorer.git`

`npm install`

`bower install`

`npm start`

Make sure to install atlasgeth as well for the Atlas Blockchain explorer to be able to function. Then run:

`geth --rpc --rpcaddr localhost --rpcport 57200 --rpcapi "web3,eth" --rpccorsdomain "http://localhost:8000"`

Then visit http://localhost:8000 in your browser of choice after you npm start the explorer

##Updates since original etherpaty/explorer base:

-Regular Expressions completed for Addresses, Block #s, and Transacions IDs (aka Search works great)

-The theme is based off Bootstrap V3 for responsive design.

-You can easily change from a dark or light theme utilizing https://bootswatch.com

-There is a basic API implemented now as well as well as a Ethereum Blockchain Information page

-Realtime ETH/USD Price Ticker

-Realtime Ethereum Hashrate

-Address Pages are integrated with Shapeshift to easily send a payment to an address.

-Responsive design

-Fontawesome Icons

-Block Time Averages

-Gas Prices/Limits

-Total/Current Difficulty

-Realtime latest blocks and recent transactions

-Other random blockchain info stats were added
