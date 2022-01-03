# Homework19 Blockchain Python
This assignment uses HD wallets, BIP44 and Python to create a Universal wallet that can support multiple crypto currencies.In this assignment 2 coins have been set up in the Universal wallet.Ethereum and Bitcoin Testnet.

## Dependencies
In addition to the below, the following should have been installed:
- HD Wallet Derive
- Blockchain TX

- PHP must be installed on your operating system
- clone hd-wallet-derive tool
- bit Python Bitcoin library
- web3.py Python Ethereum library

Create a symlink called derive for the hd-wallet-derive/hd-wallet-derive.php script. This will clean up the command needed to run the script in our code, as we can call ./derive instead of ./hd-wallet-derive/hd-wallet-derive.php. Make sure you are in the top level project directory - in this case the directory named wallet.

Windows Users: Creating symlinks is not supported by default on Windows, only reading them, so Windows users must perform the following steps:
Open up Git-Bash as an administrator (right-click on Git-Bash in the start menu).
Within bash, run the command export MSYS=winsymlinks:nativestrict.
Run the following command: ln -s hd-wallet-derive/hd-wallet-derive.php derive.
Test that you can run the ./derive script properly, by running the following command:
./derive --key=xprv9zbB6Xchu2zRkf6jSEnH9vuy7tpBuq2njDRr9efSGBXSYr1QtN8QHRur28QLQvKRqFThCxopdS1UD61a5q6jGyuJPGLDV9XfYHQto72DAE8 --cols=path,address --coin=ZEC --numderive=3 -g

![Output](https://github.com/chirathlv/Project1/blob/Renu/Images/Total%20Wine%20Sales%20per%20Income%20Bracket.png)

Steps:

1. Create a file called wallet- have used Jupyternotebook.

2. In a separate file, constants.py, set the following constants:
BTC = 'btc'
ETH = 'eth'
BTCTEST = 'btc-test'
Import all constants: from constants import * into the Jupyternotebook.

3. Generate a new word mnemonic using tool- https://iancoleman.io/bip39/. Set this mnemonic as an environment variable by storing it a an .env file and importing it into your Jupyter notebook.

4. Derive the wallet keys for each coin.

5. Link the keys to the signing libraries.

6. Execute transactions. 

7. View ETH transactions in Metamask account and Ganache- refer screen shots below.

![Output](https://github.com/chirathlv/Project1/blob/Renu/Images/Total%20Wine%20Sales%20per%20Income%20Bracket.png)

8. View BTCTEST transactions using BlockCypher- refer screen shots below.


![Output](https://github.com/chirathlv/Project1/blob/Renu/Images/Total%20Wine%20Sales%20per%20Income%20Bracket.png)