Description:
	This package is to update the 3Commas bot pairs list base on the Marketcap of the pair token from Coingecko.

Note:
	- This package support and tested with only USDT pair now.
	- This tool will update only once time you run it.

1. Configure 3C key/secret
	1.1. open .config/key.json in text editor
	1.2. replace 3CKEY with your 3Commas Read and Write API Key
	1.3. replace 3CSECRET with your 3Commas Read and Write API Secret of the above API Key

2. Configure the bot information
	2.1. open .config/config.json in text editor
	2.2. replace EXCHANGEACCOUNTNAMEIN3C with your Binance exchange account name in 3Commas
	2.3. replace BOTNAMEIN3C with your Bot name in 3Commas
	2.4. change the market_cap value (currently is 10000000000) to your prefered value, ONLY pairs with above this market_cap value will be listed in the bots settings
