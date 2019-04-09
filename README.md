# PASCoin
PoW Erc20 Token Mining

Livecoin Exchange : https://www.livecoin.net/en/trading/PAS_ETH
                    https://www.livecoin.net/en/trading/PAS_BTC

For Solo mining guide is following.Pool coming soon.

Pay Shop Coin Contract Address: 0x8020d165806DB531777b05bdb3B4eB8F6B3ce8ba
https://etherscan.io/token/0x8020d165806DB531777b05bdb3B4eB8F6B3ce8ba


Steps:
Download and extract the Miner to your computer.
Open up the tokenminer.ini file in notepad, and add your information using the below as a guide. Note that you should look for the different sections and replace with your information:
Host=https://mainnet.infura.io/your_api_key
RPCPort=8545
MinerAcct=0x........................................
AcctPK=.............................................................
TokenContract=0x8020d165806DB531777b05bdb3B4eB8F6B3ce8ba
GasPrice=5
You are now ready to start mining.

Open up a cmd window.
Browse to where you extracted the miner.
Run the following command:
tokenminer.exe -S -C -t 1
The above command is starting your miner with CPU mining with 1 thread.

 

Things you need:
An ethereum account with some Eth loaded on it
Your own infura.io url — signup here http://infura.io/signup
The MVis Token Miner — https://github.com/mining-visualizer/MVis-tokenminer/releases
 

Note:
These instructions were written with MVis-tokenminer 2.1.13
