# Stellar-Lumens-Node-Red-StellarRed
A node red node for interacting with the Stellar Lumens Horizon API

Connects with Stellar Horizon API to interact with the blockchain

Currently on Testnet



THIS IS AN EXPERIMENTAL BETA. IF YOU CHOOSE TO USE IT ON MAINNET YOU DO SO AT YOUR OWN RISK. BE CAREFUL. THIS IS NOT READY FOR MAINNET DEPLOYMENT. YOU'VE BEEN WARNED.



This flow builds a UI that can:

Generate keypairs

Check Balances

Notify after receiving a payment (some bugs still)

Send XLM or tokens

Make a trade offer

Add trustline

Generate a new token

Check Kraken Prices

4-28-21 - NFT Generator

If you are already familiar with NodeRed all you need to do to make this flow work is add the following two lines to the functionGlobalContext of your settings.js file, typically located in /home/pi/.node-red stellarsdk:require(“stellar-sdk”), nodefetch:require(“node-fetch”)

https://blockshangerous.com/2021/03/23/getting-started-with-stellarred/
