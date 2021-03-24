# Stellar-Lumens-Node-Red
A node red node for interacting with the Stellar Lumens Horizon API

Connects with Stellar Horizon API to interact with the blockchain

Currently on Testnet

This flow builds a UI that can:

Generate keypairs

Check Balances

Notify after receiving a payment (some bugs still)

Send XLM or tokens

Make a trade offer

Add trustline

Generate a new token

Check Kraken Prices

If you are already familiar with NodeRed all you need to do to make this flow work is add the following two lines to the functionGlobalContext of your settings.js file, typically located in /home/pi/.node-red stellarsdk:require(“stellar-sdk”), nodefetch:require(“node-fetch”)

https://blockshangerous.com/2021/03/23/getting-started-with-stellarred/
