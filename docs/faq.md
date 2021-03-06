Introduction
------------

### **What is Burst?**

Burst is a blockchain platform with multiple core-level features that has been running publicly since August 2014. It is a fork of Nxt and it's 100% Proof of Capacity (PoC) , meaning that you can mine it with your disk space. The more disk space you assign to mining, the higher chances you have of processing the next block. Because contrary to Proof-of-Work (PoW) this hardly needs computational resources, a full node can run on something as light as a Raspberry Pi. There will be a total of 2,158,812,800 Burst coins mined around the year 2033.

Frequently Asked Questions
--------------------------

**1) How can I obtain a coin to cover the transaction fee for setting a reward recipient (when mining) or activating an account on the blockchain with a public key?**

Request a single coin from the community in one of the forums or Burst faucets: When you are able, it is good form to return the coin that you are provided, donate it back to the faucet operator, or pay it forward to a new account holder.

Forums:

<https://discordapp.com/invite/RPhpjVv>

<https://www.reddit.com/r/burstcoinmining/comments/903gq6/initial_burstcoin_requests/>

<https://forums.getburst.net/c/new-members-introductions/getting-started-initial-burstcoin-requests>

Faucet list:

<https://faucet.burstpay.net/> (Due to daily limits, this faucet may be empty, if so you may try again the next day)

**2) I purchased coins from Bittrex. How can I move them to my new wallet?**

Bittrex requires an account to be active on the blockchain with a public key set before they will make outbound transfers. Either set a reward recipient if you will be mining, or set a name (alias) if you will not. Both require a minimal transaction fee. (See FAQ 1)

**3) I sent coins to Bittrex and they have not arrived in my Bittrex wallet. What should I do?**

Bittrex provides a message that must be included with each deposit so that they will know which account to credit. The process is a follows: To receive the message, log into your Bittrex account, click on your Burst wallet, click on the symbol for making a deposit, copy the message provided (a series of letters and numbers), Paste this message into the message box in your outgoing transaction, verify that the encryption check box is unchecked, copy and paste the payment address provided by Bittrex, verify that the address copied correctly, complete your other details, send the transaction. If you encrypted the message, or did not include it, this may be why your coins have been delayed. Contact Bittrex support with all of the details and eventually your coins will be posted to your account. It is important to follow instructions carefully and fully understand what you are doing at all times as it is possible to loose coins due to inadvertent errors such as this.

**4**)*' Where can I buy, sell, or trade Burst for other coins, tokens, or fiat currencies?*'

A list of exchanges is maintained at <https://www.burst-coin.org/exchanges>. Direct Fiat-to-Burst purchases are currently available on indacoin.com. Please note: Not all exchanges listed operate in every country. For example, Indacoin does not operate in the United States. One option for individuals in the United States is to purchase Bitcoin from Coinbase, transfer the Bitcoin to Bittrex, and convert the Bitcoin to Burst using a market order.

**5**)*' Should I store my Burst in an offline wallet, online wallet, or leave them on an exchange?*'

This is a personal choice that should be made with the security in mind. There are benefits to each depending on your circumstances. If you cannot be absolutely certain that your computer or other device is safe from hackers, malicious malware, key stroke loggers, etc., it is safest to leave your coins on a reputable exchange with two factor authentication activated. Offline wallets can be a safe option if your computer and password is secure. Please note: Two factor authentication further protects your coins on an exchange by requiring a secondary means of identifying yourself. This is an extra layer of security that can protect your coins if your exchange password is compromised. Do not leave your coins unprotected on an exchange that does not offer it. Remember, exchange passwords can be stolen like any other. Without two factor authentication enabled, there is little difference between an exchange, online, or local wallet.

**6) If I use SSD’s would I make more money?**

No, it’s 95% capacity and 5% scan time that determine success. More plot area = better deadlines = better chance of forging a block, or better rates from a pool.

**7**)*' What security measures can I take to keep my coins safe?*'

Before transferring coins to a new wallet, verify your pass phrase by signing in and out of your wallet until you are comfortable that your record of the pass phrase is accurate. Keep at least two copies of your pass phrase in separate locations. Do not disclose your pass phrase to anyone who cannot absolutely be trusted with it. Will your pass phrase still be available to you if your computer is stolen, after a natural disaster, or to your estate or other trusted individual if this should be necessary. Your pass phrase is your only access to your Burst assets. Depending on the value of your account, extraordinary measures should be employed to protect it. Your security plan might also include multiple wallets, one or more for cold storage, and one or more for other activities such as mining and/or daily transactions.

**8**)*' Are the passphrases secured?*'

I’ll leave the effort to a few people to show how secure a 12-word passphrase is:<https://burstforum.net/topic/4766/the-canary-burst-early-warning-system> Key point: brute forcing it will be around 13,537,856,339,904,134,474,012,675,034 years.

**9**)*' My local wallet used to run, I synchronised it before and now it says ‘stopped’. when I start it, it stops after a few seconds, what should I do?*'

I suggest that you change the database type to portable MariaDB (on Qbundle, at the top, ‘Database’ select, ‘change database’) and then re-import the database from scratch (see 35)

**10**)*' My new wallet will not start. What should I do?*'

Click on settings, Java, verify that “portable java” has been selected.

**11**)*' Is there a faster way to synchronizing the blockchain?*'

It is recommended that you use Portable MariaDB rather than H2. If you have not done so already, you can make the change at any time. Regarding a faster download method, In the Qbundle wallet, you can select ‘Database’, ‘Import database’. Verify that the ‘CryptoGuru repository’ is selected, then ‘start import’. This will download a relatively fast and up-to-date copy of the blockchain. This process is referred to as ‘boot strapping’. When complete, more recent blocks will be update automatically using regular peer to peer synchronization.

**12**)*' I logged into my account and my balance appears to be incorrect. Why is this?*'

Synchronization with the blockchain occurs each time a wallet is opened. Until synchronization is complete, older balances will be displayed. If, after verifying that synchronization has completed, the balance still appears to be incorrect, verify that you have entered the correct passphrase into the correct account. If you have copied and pasted your passphrase, verify that you have not inadvertently copied an extra space before or after the passphrase. At this point any difference between the displayed balance and the perceived correct balance should be reconcilable by reviewing your most recent transactions.

**13**)*' Are there channels for my language?*'

Telegram:

Spanish: <https://t.me/burstcoin_es>

German: <https://t.me/Burstcoinde>

Italian: <https://t.me/BurstCoinItalia>

Forum:

Spanish: <https://burst-coin.es/index.php/forum/index>

Discord:

Spanish: <https://discordapp.com/invite/RaaGna9>

Bulgarian: <https://discord.gg/r4uzTd>

(there are others, please contact me to put up)

**14**)** What is ‘solo’ and ‘pool’ (wasn’t his name Chewbacca?)**

Solo is where you attempt to ‘forge’ (mine) a block by yourself; you get 100% of the block reward and fees. But you only receive funds if you forge, no burst for coming in second place.

Pools allow a group of miners to ‘pool’ together their resources and when a miner wins, they give the pool the winnings (this is done by the reward assignment you completed earlier), it is then divided according to different percentages and methods and burst is sent out according to pool rules (minimum pay-out, time, etc.)

**15**)** I have been mining for 2 days and my wallet doesn’t show any Burst WHY?**

Mining solo: it is win-or-lose, nothing in between, and wining is luck and plot size. Pool mining: because it costs 1 burst to send burst, the pools have either a time requirement (every X days) or a minimum amount (100 burst +) so you need to research your pool. Some pools allow for you to set the limit (cryptoGuru and similar) to be met before sending

**16**)** How do I see what I have pending?**

On CryptoGuru, based pools, it’s the ‘Pending (burst)’ column, other pools, look for the numbers next to your burst ID. One is Paid and the other pending.

**17**)** I’m part of a pool and I forged a block, but I didn’t receive the total value of the block, why?**

A pool has 2 basic numbers that denote the pay-out method, in the format ‘XX-XX’ (i.e. 50-50) The first number is the % paid to the block forger (miner) and the second is the retained value, which is paid to historic ‘shares’ (or, past blocks that the pool didn’t win, but had a miner that was ‘close’ to winning with a good submitted deadline)

Examples of pools:

0-100 (good for &lt;40TB)

20-80 (30-80TB)

50-50 (60-200TB)

80-20 (150-250)

100-0 (solo mine, 150+ TB)

Please note that there is an overlap as this is personal preference and just guidance; a higher historical share value means a smoother pay-out regime, which some people prefer. If fees are not factored in, or are the same on different pools, the pay-out value will be the same over a long enough period.

**18**)** Is XXX model of hard drive good? Which one do you recommend?**

CHEAP is best. If you have 2 new hard drives, both covered by warranty, get the one with the lowest cost per TB (expressed as $/TB , calculated by dividing the cost by the number of terabytes) because plot size is KING,

**13**)** How many drives can I have on my machine?**

For best performance, you can have up to 2 drives per thread (3 on a new fast AVX2 CPU). So that quad-core core-2-quad can have up to 8 drives, but a more modern i7 with 4 cores + hyper threading can squeeze 8 \* 3 or 24 drives. (Performance while scanning will suffer)

**14**)** Can I game while I mine?**

Some people have done so, but you cannot have the ‘maximum’ number of drives and play games generally.

**15**)** Can I mine Burst and GPU mine other coins?**

Yes, if you CPU Mine Burst.

**16**)** I’m GPU plotting Burst and GPU mining another coin, my plots are being corrupted, why?**

My advice is dedicating a GPU to either mining or plotting, don’t try to do both.

**17**)** What is a ‘plot’?**

A plot is a file that contains Hashes, these hashes are used to mine burst. A plot is tied to an account, but they can be created (with the same account ID) on other machines and connected back to your miner(s).

**18) How much can I make on Burst?**

<https://explore.burst.cryptoguru.org/tool/calculate>

Gives you an average over time assuming a few things like: Average luck/100% uptime/no overlapping/fees on pool/good plot scan time (&lt;20 seconds) if you do not have all of these, you may not see that number.

**19**)** How can I help Burst?**

Run a wallet, which will act as a node (or if you’re a programmer, contact the Dev team Bring attention to burst (without ‘shilling’ or trying to get people to buy) And help translate into your local language

Be a productive member of the community and contribute experience and knowledge if you can, or help others get into Burst.

**20**)** Will I get coins on the fork(s) and where will they be?**

There will be no new coin, and no new coins to be given/air dropped etc, the forks are upgrades to burst and there will not be a ‘classic’ or ‘new’ burst.

**21**)** Will I need to move my Burst off of the exchange for the fork?**

No, your transactions are on the block chain, which will be used on the fork, they will be visible after the move; nothing will need to be done on your side.

**22**)** Where can I read about the progress of Burst and news in general on the community?**

There is no finer place than https://www.burstcoin.ist/

**23**)** What are the communities for Burst and the central website?**

Main website: https://www.burst-coin.org/

Reddit: https://www.reddit.com/r/burstcoin and https://www.reddit.com/r/burstcoinmining/

[Burstforum.net](http://burstforum.net/): https://www.burstforum.net/

Getburst forum: https://forums.getburst.net/

Official Facebook channel: https://m.facebook.com/groups/398967360565392

(these are the forums that are known to be supporting the current Dev Team)

Other ways to talk to the community:

Discord: https://discordapp.com/invite/RPhpjVv

Telegram (General): https://t.me/burstcoin

Telegram (Mining): https://t.me/BurstCoinMining

**24**)** When will Burst partner up with a company?**

Burst is a currency, the USD does not ‘partner up’ with a company, the DEV team will not partner up and give over to special interests.

**25**)** Why is the DEV team anonymous?**

They prefer anonymity, as it allows them to work without constant scrutiny and questions unless they wish to engage, plus the aim is for Burst to become a major contender, and this brings issues with security. They will work and produce results, they owe you nothing and if you cannot see the vision they provide then please do not ‘invest’ for short term gain.

**26**)** When moon/Lambo/$100/make me rich?**

My crystal ball is still broken, come back to the FAQ later for answer (seriously, this is a coin to hold, if you want to day-trade, good luck to you)

**27**)** How can I better educate myself and learn about Dymaxion?**

Read about the Dymaxion here: https://www.reddit.com/r/burstcoin/wiki/dymaxion

**28**)** My reads are slow, why?**

There are many reasons for this, if your computer has a decent spec it’s likely due to USB3 hub issues, or plugging into a USB2 hub, but other reasons can be multiple plots in the same folder, but it’s best to visit the mining subreddit. They can help more than an simple FAQ https://www.reddit.com/r/burstcoinmining/

**29**)** I have a great idea for Burst (not proof of stake related)?**

Awesome! Please discuss with the DEV team on discord https://discordapp.com/invite/RPhpjVv

(Please be aware that this is a public forum, you need to find who to ask/tell)

**30**)** I have a great idea for Burst (Proof of stake related)?**

No. if you want a POS, find a POS coin. On the tangle which is being implemented a POS/POW/POC coin can be created, but BURST will always be POC mined. You are welcome to implement a proof of stake coin on this!

**31**)** Will the Dev team burn any coins?**

Burst is not an ICO, so any coins will need to be bought to be burnt. You are welcome to donate, but the DEV team have no intention of burning any coins, or increasing the coin cap.

**32**)** When will there be an IOS wallet?**

IOS wallet is completed; we are waiting for it to go on the app store. Apple is the delaying factor.

**33**)** Why do overlapping plots matter?**

Plots are like collections of lottery tickets (and if only one ticket could win). Having 2 copies is not useful, and it means that you have less coverage of ‘all’ the possible numbers. It’s not good, avoid.

**36**)** What will the block reward be next month/will the block rewards run out in 6 months?**

<https://www.ecomine.earth/burstblockreward/> Rewards will carry on into 2026, but transaction fees will be a bigger % by then, and so profitable mining will continue.

**37**)** How can I get started with Burst (wallet/mining/everything) and I need it in a video**

<https://www.youtube.com/watch?v=LJLhw37Lh_8> Watch and be enlightened.

**38**)** Can I mine on multiple machines with the same account?**

Yes, if you want to pool mine this can be done (but be prepared for small issues like reported size being incorrect. Just be sure to keep question 33 in mind.)

**39**)** Why do some of my drives take forever to plot?**

Most likely they are SMR drives, it’s best to plot onto another SSD and then move the finished plot/part of a plot across to the SMR drive as this is much quicker. SMR drives are fine on the read, just random writes that are terrible.

So plot an SMR drive quickly, plot to a non SMR or better still SSD drive, in as big a chunk as possible (fewer files better) and move. a version of Xplotter, called Splotter, can do this easily.

<https://github.com/NoParamedic/SPlotter>

**40**)** I have a great idea; why not get listed on more exchanges!!**

Exchanges list coins because of 2 reasons:

1.  Clients email and REQUESTING Burst and provide details like: i. https://www.burst-coin.org/information-for-exchanges
2.  The coin pays (often A LOT, seriously we’ve been asked for 50 BTC)

I suggest you speak with your exchange and ask ‘when will they offer Burst?’

**41**)** Do you have a roadmap?**

<https://www.burst-coin.org/roadmap>

**42**)** Why is the price of Burst going up/down/sideways/looping through time?**

The price of burst is still quite dependent upon Bitcoin, meaning that if Bitcoin gains, the value of Burst gains, if Bitcoin drops then Burst also drops. If there is news for Burst then we will see something independent of Bitcoin moving. Variations can be because of people buying in bulk or selling in bulk. There are also ‘pump and dump’ schemes that we detest, that can cause spikes in price that have nothing to do with news or Bitcoin, just sad people taking advantage of others.

**43**)** Where is the best place to go with my mining questions?**

<https://www.reddit.com/r/burstcoinmining/>

or https://t.me/BurstCoinMining

**44**)** What hardware do you advise me to buy, is this computer good?**

See question 43 for specific questions on hardware, it depends on so many variables. The ‘best’ in my opinion is a 36 bay Supermicro storage server, usually they have dual 6-core CPU’s and space for 36 drives. No USB cables, plotting and mining monster, anything else, DYOR.

**45**)** Where do you buy your hard drives?**

I have bought most from EBay in job lots, and some refurbished drives with short warranties. Everything else I have bought, from Amazon.

**46**)** Can I mine on my Google drive/cloud based storage?**

In short: no. If you want to try, and get to *maybe* 1 TB and then find that your local connection isn’t fast enough, or that shortly after, your account is blocked for various reasons. Please be my guest.

**47**)** Can I mine on my NAS?**

Some you can mine with the NAS (if it can run the miner, it can scan locally) but generally they’re not very fast. good for maybe 16 TB? Having a plot on a NAS and mining from another computer depends on the network speed between the NAS and scanning computer. I believe you can scan about 8 TB (maybe a bit more) and keep the scan times to within acceptable, but YMMV.

**48**)** How can I set up a node?**

No need to set up a node, just set up a wallet (version 2.0.1) or Qbundle (2.0) and it will do the rest

**52**)** I am mining in a pool, and it says that my effective capacity is lower than I actually have, why?**

1.  If you've not been mining for &gt;48 hours, or just added additional capacity, it will take time.
2.  The value fluctuates (normally, +-5% but can be up to 10% at times)
3.  Read on the ‘Quick info’ tab about adjusting your deadline to compensate for changes i. revisit once a month for best results
4.  If you have overlapping plots it will also be lower so be aware of this (see question 33)

**53**)** What pool should I join?**

First of all, read question 9, after you have understood that it depends on the size (and how patient you are) select from the following list: https://www.ecomine.earth/burstpools/

**54**)** What miner to use?**

I use Blago’s miner, there are many out there but Blago’s works for me on CPU mining, it can be found in Qbundle.

**55**)** What Wallet to use (I use windows)?**

Qbundle: https://github.com/PoC-Consortium/Qbundle/releases/

**56**)** What Wallet to use (Superior not windows)?**

<https://package.cryptoguru.org/> for Debian and Ubuntu, for Mac. read:

<https://www.ecomine.earth/macoswalletinstallguide/>

**57**)** Will i need to 'replot' after POC2 (second fork) happens?**

No, there will be a tool which will optimise, but it is not CPU intensive (it basically re-shuffles your plot) and is just IO intensive. You do not need to replot.

TurboPlotter and https://github.com/PoC-Consortium/Utilities/tree/master/poc1to2.pl are tools that will/can be used to actuate optimization, but PLEASE wait with optimization until after the hard fork.

**58**)** Will the transaction fee always be 1 burst?**

No, dynamic fees are coming in the next fork.
