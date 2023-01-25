# Basic Binance Trading Bot

#### Code writen in Python

This python Trading Bot will perfom operations in the Futures Derivative of Binance. For now only opens Long positions, but you will figure how to do both ways. An advice is to at least have 6 times the money you wanna use on it, for example: if you cant to put 3 dolars have 18 in the futures wallet this is only to prevent margin calls.

It is a simple code, you can use it locally so you don't get your Keys Exposed in a hack of a thirth party company.

This bot will save the details of the transaction in a csv file so you can keep track of it.

The code could still have some bugs, so please tell me about them or contribute to improve it.

#### Futures releases:

1. **Check for open position:** If your computer crash you can restart the bot and it will automatically close the open position with the lowest lost and continue trading.
1. **Failsafe:** if you put an entry and the market goes down like there is no tomorrow after open X position it will automatically close operations.
1. **Auto profit**: this will choose automatically the best profit choice based on the last hours of trading.
