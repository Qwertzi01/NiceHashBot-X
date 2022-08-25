# NiceHashBotX
**NHBotX is a Bot for extended order management, manual or automatic, at NiceHash.**  
From buyers for buyers developed further.

- [Features](#features)
- [Get the Bot](#get)
- [How to run?](#run)

**Beware of scammers!** Only use our official pages and contacts:  

Media: [Telegram](https://t.me/nicehashbotx) / [Discord](https://discord.gg/quDQsxHCGT) /  [Bitcointalk](https://bitcointalk.org/index.php?topic=5266034.0) / [Github](https://github.com/Qwertzi01/NiceHashBot-X)  
Contact: nicehashbotx@outlook.com / [Telegram](https://t.me/nhbotx)  

# <a name="features"></a> Built-in Features

- Manage pools (create/edit/delete)
- Manage orders (create/recreate/refill/edit/delete)
- Automatically manage orders for **(Bot On mode)**:
    * **recreating** - recreates automatic expired and completed orders (but first preventing from completing)
    * **refilling** - automatic refill order with own defined amount if only a amount x is left in the order
    * **price adjustment** - keep price as low as possible to get hash (max. increase in x% and decrease price)
    * **own price step** - define a custom price step for price adjustments (only smaller steps than predefined)
    * **order handling** - automatic calculation of price/speed and necessary price/speed/order adjustments
    * **OneShot feature** - the Bot create a new order if difficulty of a coin is low to get wished profit
    * **Interval orders** - automatic creating of order(s) to a predefined interval and timerange
- Order handler engine is full-configurable to fit the most needs for different use cases
- OneShot runs in background and can be used at the same time as all other Bot functions
- Interval order(s) run also in background and are full-configurable over a config file
- Info section to get algorithms specifications and own NiceHash BTC wallet address
- Fast ability to manual control a order with speed/cancel buttons in main window
- Option to filter orders for specific bot instance regarding algo and/or market
- Support for creating of order bunches, also with different price steps in percent
- Easy configurable and full control over timings for different Bot tasks
- Hidden settings can be changed over a config file (for experienced users)
- Optimized stability for 24/7 continuous operation, error log and auto-restart
- Console window showing clean colorized tasks, important events and failures
- Run on **testnet** and **production** environment with all marketplace locations

# <a name="get"></a> How to get the Bot

Contact for further infos and price: nicehashbotx@outlook.com

![NiceHashBotX](https://i.ibb.co/5cZqr1d/Nice-Hash-Bot-X.jpg)

# <a name="run"></a> Instructions on how to run
- Run NiceHashBotX.exe (compatible with Windows 7/8/10/11)
- Note: .NET Framework 4.8 or higher is required
- You can also run multiple instances of NiceHashBotX - each in own folder with different API credentials.

*NiceHashBotX v1.06-3 is closed source. Based on the source of the official NiceHashBot.*
