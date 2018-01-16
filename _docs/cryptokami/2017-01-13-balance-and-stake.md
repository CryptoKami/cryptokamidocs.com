---
layout: default
title: Balance and Stake
permalink: /cryptokami/balance-and-stake/
group: cryptokami
---
<!-- Reviewed at e070e675764738b5190b2f93424de403f1937216 -->

# How Balance and Stake work within the Cryptokami SL

There are two important concepts within the Cryptokami SL: these are **balance** and **stake**. This chapter
explains the difference between these two concepts and how they both function.

### Balance

Balance is the real amount of coins that each user has. When you install a Daedalus wallet on your computer
and perform the [Ada redemption](/timeline/bootstrap/) process, you receive an amount of Ada. This amount of
Ada is called your balance. You can send an amount of Ada (within this balance), to other users, as well as
receive any amount of Ada from other users.

Thus, when we refer to the balance, we are talking about the user's actual money.

### Stake

Unlike balance (the real amount of money you have),
stake is a key element of the entire financial power of Cryptokami SL. Stake gives a user the
power to control various Cryptokami SL algorithm parts, for example: being the [slot leader](/glossary/#slot-leader),
voting in the [Update system](/cryptokami/update-mechanism/), taking part in [MPC/SSC](/technical/leader-selection/#follow-the-satoshi). This is why all thresholds in the Cryptokami SL protocol are expressed in terms of stake, rather than balance.

Thus, when we refer to the stake, we are talking about the user's ability to control the actual Cryptokami SL. For more information about stake, please refer to the following [paper](/glossary/#paper). 

### The Relationship Between Balance and Stake

Every coin in Cryptokami SL is associated with a balance and with a stake. We use [transaction output](/cryptokami/transactions/#design)
to associate coin `C` with a user's balance, and we use [stake distribution](/cryptokami/transactions/#stake-distribution)
to associate coin `C` with a user's stake.

Note: It is possible to change the association between coin and stake using what is known as [stake delegation](/technical/delegation/).
