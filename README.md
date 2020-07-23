# synthetix-faq-bot
Implementation of Discord bot for answering synthetix related questions.  

The bot has a categorized predefined [list](#list-of-questions-currently-available) of most frequent questions.  
    
It offers search functionality to users in DM.  

When asked a question in DM, the bot will try to find the best possible match from the known questions.  

This is the list of [commands](#known-dm-commands) available in DM with the bot.

In public channels the bot is only meant to answer predefined questions, with the command **!FAQ question *questionNumber***, e.g. **!FAQ question 7**.  
It can also use [aliases](#list-of-aliases-currently-available) for a question to post an answer in public channel, e.g. **!FAQ gas price**.    

The answers are built using Discord [Embeds](https://discordjs.guide/popular-topics/embeds.html) for pretty print, embedding links and adding images.

# Usage in channels
The bot is triggered by the prefix **!faq** in channels.  
The bot can answer predefined questions either by their question number of by alias.  
Examples:  
**!faq question 1**  
**!faq gas price**  

The list of all [questions](#list-of-questions-currently-available).  
The list of all [aliases](#list-of-aliases-currently-available).  
You can also get the latest aliases from the bot by doing  **!faq aliases**

# Usage in direct messaging

The bot is intended to be used mainly in direct messaging.
It has a list of predefined commands which can be browsed if **help** message is sent to the bot.

Additonally to known commands, the bot **can be asked a custom question (detected by a question mark at the end of the message)**. It will search for best possible match in the list of know questions.

## Known DM commands

**help**  
Displays the list of known commands


**list**  
Lists all known questions

**categories**  
Lists all categories of known questions


**category categoryName**  
List all known questions for a given category name, e.g. **category Staking&Minting**

**question questionNumber**  
Shows the answer to the question defined by its number, e.g. **question 7**

**search searchTerm**  
Search all known questions by given search term, e.g. **search SNX price**

**Or Ask the bot any question and it will try its' best to find a match from the known questions**


# List of questions currently available
To get the answer to a predefined question send the bot the message **question X**  
**X** being the question number, e.g. **question 21**

1  
I claimed my SNX staking rewards but I don't see them in my wallet?  
2  
How can I check exactly how many of my SNX are unlocked?  
3  
I previously locked my SNX to mint sUSD. How can I unlock my SNX?  
4  
How can I cash out my Synth gains for ETH?  
5  
How can I unlock/vest my escrowed tokens from the HAV token sale?  
6  
My wallet says I have havvens (HAV) but no SNX?  
7  
What is the current gas price?  
8  
What is the current sUSD price?  
9  
What is the current SNX price?  
10  
How to delegate claiming of SNX Rewards?  
11  
Why does my total sUSD debt fluctuate over time?  
12  
How to claim Synth Exchange Rewards without Mintr, directly using the smart contract?  
13  
How can I earn Synth exchange rewards?  
14  
How do I increase my C-Ratio (Collateralization Ratio)?  
15  
How can I claim my SNX Staking Rewards?  
16  
Now that I've minted sUSD, what can I do with it?  
17  
How can I receive SNX staking rewards?  
18  
Do I need to register or open a trading account to use Synthetix.Exchange?  
19  
How can I see how many fees were generated by a trade?  
20  
How can I make a trade on Synthetix.Exchange?  
21  
Why are my transactions failing?  
22  
Why am I blocked from claiming rewards?  
23  
Why are Synthetix transactions so expensive?  
24  
I don't have MetaMask, Trezor, Ledger, or Coinbase Wallet. How can I use the Synthetix dApps?  
25  
Why are transactions taking so long to process?  
26  
Why did I get a less synths on trade? 
27  
I am not able to burn my sUSD because the transaction keeps failing.  
28  
How to interact with a Synthetix contract using Metamask Mobile Wallet (Android/IOS)?  
29  
How often are prices updated? And where is the price feed/oracle coming from?  
30  
How can I see all of the Synths I own?  
31  
Where can I find a list of all the contracts?  
32  
Why is there a minimum deposit of 50 sUSD into the Depot?  
33  
What's the minimum amount of SNX to stake?  
34  
Where do Synth price feeds come from?  
35  
Why is it important to incentivise people to create a Synth liquidity pool?  
36  
Why aren't my SNX tokens showing up in Etherscan (or another platform)  
37  
Why does the number of my staked SNX fluctuate?  
38  
What is Curve Stablecoin Pool?  
39  
What are the rules for transferring SNX or synths?  
40  
What are SIPs & SCCPs?  
41  
What are inverse synths (iSynths)?  
42  
What is SNX inflation schedule?  
43  
Is SNX Liquid?  
44  
What is Discord Tip Bot  
45  
Why Is Gas So High  
46  
how can I use my sUSD?  
47  
What is layer 2?  
48  
What are chanlink oracles?  
49  
Can I use ether as collateral?  
50  
How to Trade?  
51  
How do I cancel a pending or stuck transaction?  



# List of aliases currently available
Use them in channels with **!faq alias**, e.g. **!faq gas price**.  
To get a list of all aliases you can do **!faq aliases**

* Question 7: What is the current gas price?  
faq! gas price  
faq! gas  
* Question 8: What is the current sUSD price?  
faq! peg  
Question 9: What is the current SNX price?  
faq! snx price  
faq! snx  
* Question 3: I previously locked my SNX to mint sUSD. How can I unlock my SNX?  
faq! unlock snx  
faq! snx unlock  
* Question 6: My wallet says I have havvens (HAV) but no SNX?  
faq! havven  
* Question 42: What is SNX inflation schedule?  
faq! inflation  
Question 15: How can I claim my SNX Staking Rewards?  
faq! claim snx rewards  
* Question 23: Why are Synthetix transactions so expensive?  
faq! expensive transactions  
