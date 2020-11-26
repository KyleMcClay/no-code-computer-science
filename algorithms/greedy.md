---
description: A Greedy Algorithm chooses the best local option
---

# Greedy

## What is a Greedy Algorithm? 🤑 

A **Greedy** Algorithm always takes the best possible local option available.

![Wall Street Bull](../.gitbook/assets/alec-favale-9li7kvwxvx0-unsplash.jpg)

## Greedy is Good? 🤩 

A Greedy algorithm is very useful when choosing between clear right and wrong choices that do not change throughout the algorithms completion.

* Greedy will work😄 
  * Choosing a career based on total salary
  * Choosing a meal based on the biggest size
  * Choosing a product based on price
* Greedy will **Not** work🤮 
  * Choosing a career based on happiness
  * Choosing a meal based on taste
  * Choosing a product based on quality

## 🤖**Lets Create A Wall Street Trading Bot**🤖 

The wall street trading bot is using a simple **Greedy** algorithm which is: _Buy Low & Sell High_. With this greedy algorithm the trading bot plans to maximize profit. To give the bot a chance against all of the wall street "Bulls". The bot will be given the next five days of stock prices for a specific company. 

* Stock prices for the next 5 days 
  * $11, $8, $18, $4, $12
* Trading Algorithm 🤖 
  * Buy Today 
    * if the Price Increases Tomorrow
  * Sell Today 
    * if the Price Decreases Tomorrow
* Sample Trading 🕓 
  * Next 5 Days = $11, $8, $18, $4, $12
* Transaction Logs of Bot🤖 
  * $11 = Nothing
  * $08 = Buys 
  * $18 = Sells 
  * $04 = Buys
  * $12 = Sells
  * Profit = 18-8 + 12-4 = $16

🦊This strategy is the best possible option for this problem but can break down on different types of problems🦊 

## \*\*\*\*🕹**Lets Make a Super Mario Bros Algorithm**🕹\*\*\*\*

The **Greedy** algorithm is trying to beat the Super Mario game as fast as possible. The algorithm must obey the rules we set. Algorithm Rules:

* Mario always runs forward
* Mario always jumps on or over enemies
* Mario always jumps over obstacles

The **greedy** part of the algorithm is always "greedily" moving forward, this was chosen because it seems to be the fastest way to complete the level.

* Good👾 
  * Simple strategy
  * Easy to implement
  * Mario will complete levels fast
* Bad 💩 
  * Mario will **Not** find 
    * Secrets
    * Bonus content
  * Faster solutions are possible with shortcuts
* Ugly☠ 
  * Unforeseen circumstance can make the game unbeatable
  * Unique enemy \(Bowser\)
    * Can **Not** defeat using normal jump attacks
  * Unique level \(Swim\) 
    * Can **Not** navigate using normal controls
  * Unique puzzle \(collect keys\)
    * Can **Not** win without doing something

\_\_💰A **Greedy** Algorithm can be short sighted💰 

