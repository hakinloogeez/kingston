The original versions released by original dev has an issue where "Staking Is Not Active". Staking was supposed to activate after block 86,401. This didn't occur. I have committed a few changes to the code here, but have neither tested nor compiled it for testing. This version of code here, on GitHub is no longer the original and may or may not function as originally planned. As with any edited code, use it at your own risk and test it BEFORE you load your wallet.dat into it. As of now, there is currently no dev, no discord with original devs, no twitter, and the bitcointalk ANN page has been locked. The only available active community is currently telegram, a new discord has been created here https://discord.gg/PJv5SSD . 


# Kingston [KGX]

 
![logo](https://cdn.discordapp.com/attachments/422468140551634955/424229016493359105/kingstonWaller_0.1.1.png)

Intro
==========================
Kingston is an anonymous, untraceable and secure hybrid cryptocurrency with POW-POS & Masternodes. 
The main goal is to develop the cryptocurrency as a single, decentralized payment system for your everyday life. 
We focus mainly on time, size, anonymity and security of your transactions with helping hand of masternodes to keep the integrity of the network and provide instant and safe transactions. 
The coin works on C11 algorithm – it's resistant to ASIC and Nicehash attacks, maximally secured and uses small capacity of video memory. Kingston has a 1% Premine of 288,000 KGX for bounties, distribution, marketing and development.

Kingston is a cutting edge cryptocurrency, with many features not available in most other cryptocurrencies.
- Anonymized transactions using coin mixing technology, we call it *DarkSend.
- Fast transactions featuring guaranteed zero confirmation transactions, we call it *InstantX.
- Decentralized blockchain voting providing for consensus based advancement of the current Masternode
  technology used to secure the network and provide the above features, each Masternode is secured
  with collateral of 5,000 KGX

Specifications
==========================
* Total number of coins: 28,800,000 KGX
* Ideal block time: 60 seconds
* Maturity: 60 blocks
* Min stake age: 8 hours
* Cost of Masternode: 5,000 KGX
* Masternode Reward: 50% of current block reward

Technology
==========================
* Hybrid PoW/PoS Masternodes
* Stealth addresses
* Encrypted Messaging
* Multi-Signature Addresses & TXs
* Fast 60 Second Block Times
* New C11 PoW Algorithm for PoW
* SHA256d Algortihm for PoS Hybrid
* Full Decentralization

LINKS
==========================
* Official Website(https://kingston.cash/)
* UnOfficial Discord(https://discord.gg/PJv5SSD)
* UnOfficial Github(https://github.com/hakinloogeez/kingston)

OVERVIEW
==========================
<table>
<tr><td>Ticker Symbol</td><td>KGX</td></tr>
<tr><td>Algorithm</td><td>C11</td></tr>
<tr><td>Type</td><td>PoW - PoS Hybrid*</td></tr>
<tr><td>Block Time</td><td>60 Seconds</td></tr>
<tr><td>Difficulty Retargeting</td><td>Every Block</td></tr>
<tr><td>Max Coin Supply</td><td>28,800,000 KGX</td></tr>
<tr><td>Premine/Initial Supply</td><td>1%*</td></tr>
<tr><td>Reward Method</td><td>see below</td></tr>
</table>

<list>
<li>Block       2 to   2.880 = 1 KGX (100% Miner)</li>
<li>Block   2.881 to  86.400 = 30 KGX  (50% Miner | 50% Masternode)</li>
<li>Block  86.401 to 172.800 = 25 KGX  (25% Miner | 50% Masternode | 25% POS)</li>
<li>Block 172.801 to 345.600 = 20 KGX (25% Miner | 50% Masternode | 25% POS)</li>
<li>Block 345.601 to 518.400 = 15 KGX  (20% Miner | 50% Masternode | 30% POS)</li>
<li>Block 518.401 to 691.200 = 10 KGX  (10% Miner | 50% Masternode | 40% POS)</li>		
<li>Block 691.201 until max. = 5 KGX  (0% Miner | 50% Masternode | 50% POS)</li>
</list>


Development process
===========================

Developers work in their own trees, then submit pull requests when
they think their feature or bug fix is ready.

The patch will be accepted if there is broad consensus that it is a
good thing.  Developers should expect to rework and resubmit patches
if they don't match the project's coding conventions (see coding.txt)
or are controversial.

The master branch is regularly built and tested, but is not guaranteed
to be completely stable. Tags are regularly created to indicate new
stable release versions of Denarius.

Feature branches are created when there are major new features being
worked on by several people.

From time to time a pull request will become outdated. If this occurs, and
the pull is no longer automatically mergeable; a comment on the pull will
be used to issue a warning of closure. The pull will be closed 15 days
after the warning if action is not taken by the author. Pull requests closed
in this manner will have their corresponding issue labeled 'stagnant'.

Issues with no commits will be given a similar warning, and closed after
15 days from their last activity. Issues closed in this manner will be 
labeled 'stale'.
