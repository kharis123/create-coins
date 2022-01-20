THIS SCRIPT ONLY WORK AT TESTNET AT https://remix.ethereum.org/

# create-coins
Replace the symbol and name with your own:
62 symbol = "QKC";
63 name = "QuikNode Coin";

set the decimal (value in which tokens can be divided, 0to8 decimal units can be used) and establish a total supply value as you wish:
64 decimals = 2;
65 _totalSupply = 100000;
 
Please change YOUR_METAMASK_WALLET_ADDRESS to your own wallet address (same wallet you specified to obtain test currency):
66 balances[YOUR_METAMASK_WALLET_ADDRESS] = _totalSupply;
67 emit Transfer(address(0), YOUR_METAMASK_WALLET_ADDRESS, _totalSupply);
