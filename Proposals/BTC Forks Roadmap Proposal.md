# The BTCForks Master Plan - Part 1

Draft 1 of The BTCForks Master Plan - Part 1

##1. Contents

1. [Contents](#1-contents)
2. [Introduction](#3-introduction)
3. [Statement of Need](#4-statement-of-need)
4. [Objectives](#5-objectives)
5. [Methods](#6-methods)
6. [Evaluation](#7-evaluation)
7. [Schedule](#8-schedule)
8. [Future Objectives](#9-future)
9. [Risks](#10-risks)
10. [FAQ](#11-faq)
11. [Contribute](#12-contribute)


##2. Introduction: 

We are forking Bitcoin.

We are a group of Bitcoin participants forking Bitcoin back to its original vision of scaling on-chain to the world; with or without miner majority. We believe that Bitcoin will scale on chain, and should be governed through users freedom of choice to choose the software they want to run without coercion or force. We believe this is the original vision of Bitcoin; to allow any interested user access to a network of peer to peer cash, with a low barrier to entry.

Our initial mission is simple: to advance Bitcoin scaling while making a powerful statement on governance by executing a successful hardfork spinoff of the Bitcoin network and facilitating a process that allow further spinoffs in the future.

The Bitcoin experiment has not failed. It is only just getting started!!


##3. Statement of Need

*Describes the problem.*

**Summary**

The aim of bitcoin is, or should be, to become the number one transaction network in the world. It will free up the worlds capital and offer a new era of economic growth and freedom. In the 7 years since bitcoin was released by Satoshi Nakamoto in 2009 it has grown massively in scale to a market cap of over $10b and handles around 2.5 transactions every second. Although, this is very impressive for a completely new technology, in comparison to other financial assets this is still very small. For example the market cap of gold is ~$8t and the market cap of Apple ~$580b.

Currently there are a number of roadblocks that need to be surpassed before bitcoin has the potential to reach mass adoption. One of the most significant roadblocks is bitcoin's technical ability to scale. Currently there is a coded limit to the number of transactions that can happen on the bitcoin network. This is the block size limit. The current current block size limit is set to 1MB. Using the current average transaction size it means that currently there cannot be any more than around 3 transactions per second on the network. This means the network is currently running at capacity.

**Governance Problems**

Bitcoin in its essence is a social system. A way of arranging the interactions between people. This means a number of problems that it faces right now cannot be solved with code alone.

Development of bitcoin through an evolutionary process will allow the best ideas to succeed and the worst ideas to fail. Allowing people to freely chose which version of a cryptocurrency they want to use is key to making this happen. Participants currently have only one choice if they disagree strongly with the current development; exit bitcoin completely. It is far too binary as it means price is only a reasonably good signal in the long-term, at which point it may already be too late to fix any problems. Giving participants a choice to support another 'version' of bitcoin is creating a very direct short-term and long-term signal of what the best approach is.

A decentralised system works best when all its components are in equilibrium.

Developers, miners, investors and nodes should all keep each other in check through their own selfish interests. Currently the bitcoin developers have the majority share of power in this system as they are advocating against freedom of choice. Numerous attacks from various angles have been made to stop participants from having the freedom to choose the software they run. Collusion between the miners and main developers of bitcoin has made it so that investors, nodes and users have only one option to voice opposition, and that is to leave the bitcoin economy entirely. This is a very ineffective way of signalling to the miners and developers that their needs are not being met, because new participants may be joining all the time and may be replacing participants who have exited. If the bitcoin economy and its participants are given freedom of choice to choose which ever version of bitcoin suits their needs best then participants are far less likely to exit the ecosystem entirely, and therefore the total market cap of bitcoin as a collection of systems is likely to rise (although some versions will fail and some will succeed).

**Our Options**

While there are many different proposals on how to solve this problem, most solutions boil down to one of two solutions. One solution is to change the economic model of bitcoin so that the bitcoin network does not scale much further on-chain, but rather exra layers are developed on top of the bitcoin network. These extra layers would connect to bitcoin for security but would not have the same security model of bitcoin. The Lightning is an example of a layer 2 network. This solution could be boiled down to "Bitcoin: An Electronic Settlement Network". Another solution is to allow the bitcoin network to scale on-chain by allowing more transactions to happen directly on the bitcoin network. This solution would keep the economic model of bitcoin that has worked over the past 7 years and would extend it to the future. "This solution can be boiled down to "Bitcoin: A Peer-to-Peer Electronic Cash Network for Payments and Settlement Transactions"

Currently, the development of the bitcoin reference client is done by the group of bitcoin developers calling themselves "Core". While there are various other smaller development teams that offer their own bitcoin clients, the Core developers control the development of the client that most network participants are aware of. The Core developers of bitcoin have decided to use the solution of "Bitcoin: An Electronic Settlement Network". A significant (although not necessarily a majority) number of the network participants do not feel that this solution is the best way forward.

**Reasoning for Not Choosing the Opposing Solution**

Our reasoning for the decision that the "Bitcoin: An Electronic Settlement Network" is not an optimal solution is that, from our analysis it seems that the economic and security model of this solution does not work and that the solution does not use fully understood technology. 

These are some of the major issues with Core's solution that have pushed us towards our conclusion:

1. Under this model the bitcoin network would operate constantly at capacity, meaning all blocks would be full at all times. This has started now already and will continue until layer 2 solutions are released. This means there would be large competition between network participants to get transactions published in blocks. The first issue with this is that, as transaction fees increase on the bitcoin network, current network participants will move to other transaction network (altcoins, visa, paypal etc.) and potential new network participants will choose not to use the bitcoin network. When a potential user is faced with the option of; sending a transaction on the bitcoin network at the cost of $1 with uncertainty of the speed and reliability of that transaction due to the network running at capacity, *or* sending that transaction on an altcoin network for $0.05 and having certainty of the speed and reliability of that transaction due to the network running below capacity, the user is most likely to choose the second option. If layer 2 solutions are not released and actively deployed fully across the network within a short time scale, it is possible, or even likely, that bitcoin will lose its network effect and leading position within the cryptocurrency market as other cryptocurrencies offer a better value proposition.

2. Currently it is not known exactly how layer 2 solutions will work in practice or whether they work at all as a solution to scaling. Changing the entire economic model of bitcoin before a solution is found to be working and suitable is highly risky.

3. If/when layer 2 solutions are fully deployed across the network and the bitcoin network is run at capacity, the transaction fees of the network will increase significantly (if the effects of issue 1 do not preclude this from happening). The security model of the layer 2 solutions require the ability to publish transactions to the bitcoin blockchain to secure the transaction in the event of a malicious actor (e.g a scammer). As the cost to publish a transaction to the bitcoin blockchain increases, the value that is secured in a transaction on a layer 2 solution decreases. To give an example; Alice buys a digital music album from Bob for $20 on the internet. Alice decides she wants to use a layer 2 solution to pay Bob. Alice sends Bob $20 and Bob releases the link to Alice so she can download the file. Alice is actually a scammer and tries to undo the payment so that the album actually cost her nothing. Bob is notified of this attack and is informed he can secure the transaction by publishing it to the bitcoin blockchain. Bob goes to publish the transaction to the bitcoin blockchain but sees that the current minimum transaction fee to get into a block within enough time to block the attacker is $20. This means that if he does secure the transaction on the bitcoin blockchain, all the value of the transaction will simply go to the miner. This meant that his transaction had zero security. This is also proportionally true for transactions of value higher than the fee to have the transaction published to the bitcoin network. For example if the album had been $40 instead, it seems certain that Bob would not have been happy to lose $20 or 50% of the transaction.

**Reasoning for Choosing Our Solution**

We propose the creation of a new bitcoin reference client that serves the need of the network participants that wish to support the solution of "Bitcoin: A Peer-to-Peer Electronic Cash Network for payments and settlement transactions". This reference client will be incompatible with the reference client developed by the Core developers. This means that when the client activates fully, the bitcoin network will become split in two. Each with their own unique philosophy and value proposition. Network participants will then be free to support which direction they feel is best for bitcoin to progress in. This will be the first stage of the project.




##4. Objectives

*Refine your idea and tell exactly what you expect to accomplish in response to the need.

- Give users and market freedom of choice.
- Allow bitcoin to scale.
- Improve consensus mechanisms.
- Improve governance system.
- Improve security of code produced.
- Improve network decentralisation.
- Improve development productivity.

##5. Methods

*What you will do to accomplish your objectives.*

- **Create a Format for Forking Cryptocurrencies.**

   The main goal of the first bitcoin spinoff will be to allow bitcoin to scale safely and facilitate the development of a process for further spinoffs. The aims of this project are not to support any particular fork but the first fork is of particular importance because it will lay the ground work for others in the future and will show that hardforking bitcoin in this way is possible.

- **Fork Bitcoin.**

   	1. Create user requirements of MVF (Minimum Viable Fork)
	2. Create requirements of MVF
	3. Create final specification and design of MVF
	4. Create Initial MVF Client
	5. Create Final Release of MVF Client
	6. Run MVF on Test-net
	7. Launch MVF on Main-net

- **Create a system for tracking consensus mechanisms.**

   [TEXT]

- **Create a system for producing higher quality code.**

   [TEXT]

- **Create a system for improving productivity of development.**

   [TEXT]



**6.ii. Process to Launch**


	
**6.iii. Checklist of Things to Achieve before a Successful Fork Can Occur**

- Have at least one exchange available.
- Have at least one desktop wallet available (will likely be in the client).
- Have at least one SPV mobile wallet available.
- Have at least 3 mining pools available.
- Have at least 1000 distributed nodes active on the network.

---


##6. Evaluation

*How to measure your results and effectiveness. This should correspond to your objectives.*


##7. Rough Schedule

**Months 1-3 :** 
Community development, establishment of necessary channels, build, and testing infrastructure, and community release of several proposed forks (including multiple client bases and PoW implementations). Our goal is to create a collaborative environment in which forks can be proposed, tested, evaluated, and deployed by the community and marketplace. We will research key challenges, like PoW changes, difficulty adjustment, script limits, and effects of blocksize cap through tests on our public test network.

**Months 3-6 :** 
Client release of final binaries, and establishment of exchange relationships necessary to begin trading of dominant fork. Deployment of required network infrastructures, including an initial node and mining network. We will focus on getting a fork ready for widespread use, getting a working product to the marketplace.

**Months 6+ :**
Support of the initial and any further forks through the creation of community resources for comparison, discussion, and decision making. We will faciliatate the overall Bitcoin governance process by encouraging sane forks, regardless of whether or not they are contentious. We will aim to provide the market with all resources and information necessary to make informed decisions.


##8. Future Objectives

1. Create a Bitcoin implementation written from scratch to clean the code up and function as the new reference client.  An effort could be made parallel to the actual phylomemetic evolution of Bitcoin to try to “catch up” in terms of documenting existing requirements and design, by integrating these dispersed parts of the tree, or alternatively, attempting to construct a clean formal specification of the system from scratch based on the inputs and knowledge that the phylomemetic process has delivered.

2. Modularise the reference client so that the functions of being a node and submitting transaction are separate. This will allow easier development of clients with various features.

3. Work on an objective description of the fundamental principles that underlie Bitcoin's evolution as a technology.
This will cover the CALs etc.

4. Work on elaborating a (subjective) set of constitutional principles that the community supporting the solution "Bitcoin: A Peer-to-Peer Electronic Cash Network for payments and settlement transactions" can agree on. This will require conducting a constitution-forming process, starting from the already existing inputs (Satoshi's confirmed writings, principles extolled at Satoshi's Roundtable workshop, etc.)

5. Work with industry to develop a Bitcoin Industry Code of Conduct or Ethical Code that lines up with the constitutional principles, but puts them in practical context. This document can provide guidance on conduct and best practices for miners, pools, exchanges, software development houses, academic researchers etc.


##8. Risks

**8.i. Attacks**

- DDOS attacks against nodes.
- DDOS attacks against exchanges.
- Social attacks.
- Legal attacks.
- Spam attacks.
- Blockchain bloat attacks.
- 51% attacks.
- Empty block attacks.

**8.ii. Lack of Support**

- Lack of support from users, miners, investors, businesses, developers, exchanges.

**8.iii. Bugs**

- Obviously every effort will be put towards making sure any software that is released for use but every software has a risk of having bugs in the code. Bugs could range anywhere between minor to major.


###9. Support for Business Implementations

Support for businesses wanting to implement a bitcoin spinoff. Forks designed with adequate documentation to make implementation by businesses easier.

---

##9. FAQ

Have any other questions about our project? Ask on our subreddit.

**Is this just another [altcoin / pump and dump]?**

No! First of all this is not an altcoin; it is a Bitcoin implementation that forks from the main chain, preserving the same UTXO set, genesis block, and blockchain up to a certain height. While some may redefine the word "altcoin" to include any forks of the main chain outside the de facto reference implementation, we do not agree with this disingenuous use of the term.


**Who is behind this project?**

We are a group of Bitcoin developers, users, and supporters who are frustrated by the lack of scaling and governance solutions proposed by the status quo. While many of us choose to remain anonymous and pseudonymous for fear of attack in what remains a politically loaded space, we will strive to make as much information on the development of our fork public as possible. We welcome any with time or skills to spare to join the project using the links below.


**Why now?**

After years of stalling on the scaling issue (with solutions demanded as early as 2012), we believe the time has come to abandon ultraconservatism and move towards progress and open experimentation. With many popular Bitcoin businesses expressing concerns or pivoting out of the space, we see an existential crisis looming for Bitcoin if scaling is not improved soon. The active engagement of the community in forks as a freedom-preserving upgrade mechanism is long overdue.


**What client are we using for the fork?**

We have not chosen a specific client for the fork. Rather, we aim to encourage all developers to propose forking clients, and wish to provide an infrastructure through which these forks can all be tested and evaluated. We support any and all technically significant forks of the current blockchain, and believe all should be discussed and submitted to consideration to the wider community.


**But can't a fork cause loss of funds?**

No, a properly implemented and deployed fork will not cause a loss of funds in the absence of severe negligence. Because the new fork inherently has a different value than the old chain, and requires proactive upgrade actions from users and nodes, these users have an opportunity to take appropriate security protections in anticipation of the fork. Old clients will simply continue operating on the old chain, with clients intending to trade goods for fiat simply operating with the exchange value of the old chain. Several cryptocurrencies have already demonstrated successful forks with no fund loss, and we believe the fear of such forks in the Bitcoin community is unsupported by the current empirical evidence.


**Why not a soft fork?**

We believe deploying critical protocol changes through soft forks is an inherently bloated process that is coercive to far more people than an equivalent hard fork. Soft forks activate exclusively on miner vote, disenfranchising nodes that do not hold hashpower and excluding them from the decision process. Furthermore, many soft forks decrease the security of old nodes by removing their ability to meaningfully validate an ever-increasing percentage of transactions in blocks. Lastly, soft forks are coercive to dissident miners, who are forced to either upgrade to the fork or accept the potential orphaning of all blocks they mine. On the other hand, a hard fork allows all users of the system to explicitly choose the consensus rules and blockchain with which they transact. Hard forks also mitigate the damage possible through development capture by allowing users a choice to change to a chain with values, developers, and code of their choosing. Ultimately, hard forks are an essential upgrade mechanism, and critical to the antifragility of all cryptocurrency.


**But a hard fork is hard?**

A hard fork is hard but necessary. After the first fork is executed, we expect the ecosystem of tools surrounding the management of forks to become increasingly robust, supporting future forks in a far more seamless and low-effort fashion.

---

##10. Contribute


Calling all devs and non-devs alike: Help us bring Bitcoin to the world!

Start the conversation on reddit at [reddit.com/r/btcfork](https://www.reddit.com/r/btcfork)

Vote on BTC Fork Constitution and features at [btcfork.consider.it](https://www.btcfork.consider.it)

Contribute code or testing at [github.com/BTCfork](https://www.github.com/BTCfork)

Follow us on Twitter at [twitter.com/btcfork](https://www.twitter.com/btcfork)

Join us on Telegram at [@BTCFork](https://telegram.me/BTCFork)

Join our Slack (automated invitation coming soon.)
