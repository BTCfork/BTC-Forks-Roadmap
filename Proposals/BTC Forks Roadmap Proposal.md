

![BTCFORK Header](http://i.imgur.com/vYX8cWI.png)

This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.<br />
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a>

###0. Contents

0. Contents
1. Introduction
2. Goals of the Project
3. Rough Schedule
4. Governance
  1. Summary
  2. Bitcoin Evolutionary Process (BEP)
  3. Consensus Abstraction Layers (CAL)
  4. Accelerated Phylomemetic Tree Development
  5. Implementation Readiness Levels
5. The First Spinoff
  1. Goals
  2. Process to Launch
  3. Checklist of Things to Achieve before a Successful Fork Can Occur
6. Future Objectives
7. Risks
  1. Attacks
  2. Lack of Support
  3. Bugs
8. Support for Business Implementations
9. Expenses and Funding
  1. Project Expenses
  2. Project Funding Ideas
10. Decentralisation of Communication Channels
11. Definitions
12. FAQ
13. Contribute

---

###1. Introduction

We are forking Bitcoin.

We are a group of Bitcoin participants forking Bitcoin back to its original vision of scaling on-chain to the world; with or without miner majority. We believe that Bitcoin will scale on chain, and should be governed through users freedom of choice to choose the software they want to run without coercion or force. We believe this is the original vision of Bitcoin; to allow any interested user access to a network of peer to peer cash, with a low barrier to entry. 

Our mission is simple: to advance Bitcoin scaling while making a powerful statement on governance by executing a successful hardfork spinoff of the Bitcoin network and facilitating a process that allow further spinoffs in the future..

The Bitcoin experiment has not failed. It is only just getting started!!

---

###2. Goals of the Project

1. Give users and market freedom of choice.
2. Allow bitcoin to scale.
3. Improve consensus mechanisms.
4. Improve security of code produced.
5. Improve network decentralisation.
6. Improve development productivity.

---

###3. Rough Schedule

**Months 1-3 :** 
Community development, establishment of necessary channels, build, and testing infrastructure, and community release of several proposed forks (including multiple client bases and PoW implementations). Our goal is to create a collaborative environment in which forks can be proposed, tested, evaluated, and deployed by the community and marketplace. We will research key challenges, like PoW changes, difficulty adjustment, script limits, and effects of blocksize cap through tests on our public test network.

**Months 3-6 :** 
Client release of final binaries, and establishment of exchange relationships necessary to begin trading of dominant fork. Deployment of required network infrastructures, including an initial node and mining network. We will focus on getting a fork ready for widespread use, getting a working product to the marketplace.

**Months 6+ :**
Support of the initial and any further forks through the creation of community resources for comparison, discussion, and decision making. We will faciliatate the overall Bitcoin governance process by encouraging sane forks, regardless of whether or not they are contentious. We will aim to provide the market with all resources and information necessary to make informed decisions.

---

###4. Governance

**4.i. Summary**

Bitcoin in its essence is a social system. A way of arranging the interactions between people. This means a number of problems that it faces right now cannot be solved with code alone.

Development of bitcoin through an evolutionary process will allow the best ideas to succeed and the worst ideas to fail. Allowing people to freely chose which version of a cryptocurrency they want to use is key to making this happen. Participants currently have only one choice if they disagree strongly with the current development; exit bitcoin completely. It is far too binary as it means price is only a reasonably good signal in the long-term, at which point it may already be too late to fix any problems. Giving participants a choice to support another 'version' of bitcoin is creating a very direct short-term and long-term signal of what the best approach is.

A decentralised system works best when all its components are in [equilibrium](http://www.bitcoinwednesday.com/wp-content/uploads/2016/02/Bitcoins-Incentive-Structure.pdf).

Developers, miners, investors and nodes should all keep each other in check through their own selfish interests. Currently the bitcoin developers have the majority share of power in this system as they are advocating against freedom of choice. Numerous attacks from various angles have been made to stop participants from having the freedom to choose the software they run. Collusion between the miners and main developers of bitcoin has made it so that investors, nodes and users have only one option to voice opposition, and that is to leave the bitcoin economy entirely. This is a very ineffective way of signalling to the miners and developers that their needs are not being met, because new participants may be joining all the time and may be replacing participants who have exited. If the bitcoin economy and its participants are given freedom of choice to choose which ever version of bitcoin suits their needs best then participants are far less likely to exit the ecosystem entirely, and therefore the total market cap of bitcoin as a collection of systems is likely to rise (although some versions will fail and some will succeed).

---

**4.ii. Bitcoin Evolutionary Processes (BEP)**

Turning bitcoin development into an evolutionary system where progress is market driven rather than driven by a select few ‘official’ developers. The bitcoin evolutionary process is made up of three parts. The first part is the **Consensus Abstraction Layers**. The second part is the **Accelerated Phylomemetic Tree Development**. The third part is the **Implementation Readiness Levels**. Each part is designed to solve a different problem in bitcoin currently.


**4.iii. Consensus Abstraction Layers (CAL)**

The consensus abstraction layers are a way of assessing and tracking changes to a cryptocurrency made by developers. These changes may be the general principles that the participants follow, the consensus logic that the network follows or specific changes in the code of an implementation. Use of the consensus abstraction layers will allow participants to hold other participants to account within the ecosystem and will reinforce the ability for users to consent to the network(s) they are using. If an implementation/code change is made that is not inline with the current abstraction layers of that cryptocurrency then this implementation is considered to be forked and the type of fork is dictated by the CAL that the fork has taken place on.

		CAL0 - Freedom of Choice
		CAL1 - Constitutional Principles
		CAL2 - Consensus Logic
		CAL3 - Everything Else


[PLACEHOLDER LINK]()

---

**4.iv. Accelerated Concept Development**

The Accelerated Concept Development system aims to achieve the goal of improving development productivity in a traceable, open and collaborative way.

Full concept development of Bitcoin would encompass all the artefacts produced during the software development lifecycle, from requirement specifications through design and further on to the released code.

We propose an “accelerated” development tree model (based on the branching features of modern distributed version control systems) to help the community produce Bitcoin Evolutionary Proposals in terms that are more generally accessible than specific source code. The two basic parts of this are:

- Requirements
- Design

Since there is currently a lack of formally specified requirements or design for bitcoin, there is no “one baseline” at present from which to start.

Nevertheless, it seems that such a tree-based evolution process could be applied from a later starting point as long as there is an initial motive. For example, one could set up a repository for a tree to develop various fork proposals. These proposals could be represented by requirements + design changes to the existing consensus. The process would start from a “root node” representing the status quo (no requirements + design changes), and would split into branches as participants introduce ideas which are incompatible with the concepts at a particular tree node. Participants would need to formulate their ideas not vaguely, but in terms of actual requirements and design. The community would discuss these proposals and refine them using the collaborative features of the version control system. Arguments and counterarguments would end up being stored in this tree structure along with the branches containing the evolving ideas. The end result would resemble Decision Trees or Classification Trees which can be used by later generations to inspect and understand the rationale which lead to certain requirements and design decisions.

Once some points in this tree have reached sufficient maturity in terms of completeness and consistency, development teams might decide to 'adopt' them and see them through to implementation and release. The teams could “tag” the nodes in the concept tree which correspond to the requirements & design which they are targeting, making it possible to have an overview of Bitcoin evolution as a whole.

Proposed requirements and design elements should be formulated according to engineering best practices, i.e. they should strive to be complete, consistent, traceable, verifiable etc.
[https://zolotarev.fd.cvut.cz/ma/ctrl.php?act=show,file,9727](https://zolotarev.fd.cvut.cz/ma/ctrl.php?act=show,file,9727)
[http://www.win.tue.nl/~wstomv/edu/2ip30/references/smart-requirements.pdf](http://www.win.tue.nl/~wstomv/edu/2ip30/references/smart-requirements.pdf)

Since it would be infeasible to create a prerequisite for elaboration of complete, consistent requirements and design of the existing system (a moving target), we propose that changes can be specified in isolation and discussed by experts based on their body of knowledge of various implementations and use cases. In this way, the concept tree would evolve partial specifications which are consistent in themselves, and could later be integrated to form a more complete specification picture of the entire system.

The community, incl. development teams, would be able to accompany an open development process through various levels of implementation maturity. In fact, the closer to deployment, the more public the process would need to be, to allow sufficient time for verification and validation. The end result would be solid requirements, traceable to design, which in turn would be traceable to code which should be suitably covered by tests, which the public could independently verify and validate.

---

**4.v. Implementation Readiness Levels**

[http://www.nasa-usa.de/directorates/heo/scan/engineering/technology/txt_accordion1.html](http://www.nasa-usa.de/directorates/heo/scan/engineering/technology/txt_accordion1.html)

The following section outlines how the maturity of a proposal could be described in terms of 'Implementation Readiness Levels'. The IRLs are a method of improving the quality and security of the code released and implemented into the economy. They also offer participants in the network a measure of the maturity of a technology.

		IRL1 - Basic Technology Research - Ideas, observations, napkin drawings, good problem descriptions, solution suggestion blog posts, concept papers without a need for empirical data or proof-of-concept implementation.
			↓
		IRL2 - Research to Prove Feasibility - Research (analysis + experimental implementations yielding empirical data), published papers. No need for formal specification of requirements, design or verification methods. Peer review at research level.
			↓
		IRL3 - Technology Development - Research elements turned into module implementations, either from scratch or based on existing prototypes.
			↓
		IRL4 - Technology Demonstration - Able to demonstrate limited functionality in a public or private test network (testnet).
			↓
		IRL5 - System/Subsystem Development - Develop a public fork/spin-off system based on an existing production system (which could be a previous spin-off) by producing a delta of system/subsystem requirements and associated design, implementation, tests and verification results
			↓
		IRL6 - System Test, Launch & Operations - Public test phase on test network of existing system, with clear test plan and quality gates to move to next phase: public test on main network. Public test on main network with clear warning that this is a test ("play money"), and should not be treated as actual currency by anyone. Active steps to minimize detrimental impacts on the existing operational network (non-aggression principle). After final validation, production release, and move to operational maintenance.

---

###5. The First Spinoff

**5.i. Goals**

The main goal of the first bitcoin spinoff will be to allow bitcoin to scale safely and facilitate the development of a process for further spinoffs. The aims of this project are not to support any particular fork but the first fork is of particular importance because it will lay the ground work for others in the future and will show that hardforking bitcoin in this way is possible.

**5.ii. Process to Launch**

	Create final specification of MVF (Minimum Viable Fork)
			↓
	Create Initial MVF Client
			↓
	Create Final Release of MVF Client
			↓
	Run MVF on Test-net
			↓
	Run Hidden MVF on Main-net
			↓
	Launch MVF on Main-net
	
**5.iii. Checklist of Things to Achieve before a Successful Fork Can Occur**

- Have at least one exchange available.
- Have at least one desktop wallet available (will likely be in the client).
- Have at least one SPV mobile wallet available.
- Have at least 3 mining pools available.
- Have at least 1000 distributed nodes active on the network.

---

###6. Future Objectives

1. Create a Bitcoin implementation written from scratch to clean the code up and function as the new reference client.  An effort could be made parallel to the actual phylomemetic evolution of Bitcoin to try to “catch up” in terms of documenting existing requirements and design, by integrating these dispersed parts of the tree, or alternatively, attempting to construct a clean formal specification of the system from scratch based on the inputs and knowledge that the phylomemetic process has delivered.

2. Modularise the reference client so that the functions of being a node and submitting transaction are separate. This will allow easier development of clients with various features.

---

###7. Risks

**7.i. Attacks**

- DDOS attacks against nodes.
- DDOS attacks against exchanges.
- Social attacks.
- Legal attacks.
- Spam attacks.
- Blockchain bloat attacks.
- 51% attacks.
- Empty block attacks.

**7.ii. Lack of Support**

- Lack of support from users, miners, investors, businesses, developers, exchanges.

**7.iii. Bugs**

- Obviously every effort will be put towards making sure any software that is released for use but every software has a risk of having bugs in the code. Bugs could range anywhere between minor to major.


###8. Support for Business Implementations

Support for businesses wanting to implement a bitcoin spinoff. Forks designed with adequate documentation to make implementation by businesses easier.

---

###9. Expenses & Funding


#####9.i. Project Expenses

- Dev funding
- Slack
- Github
- Education Material


#####9.ii. Project Funding Ideas

- Donations
- Client transaction fees.
- Create a Foundation

---

###10. Decentralisation of Communication Channels

One key failure within the bitcoin community in recent years has been the centralisation of information and information exchange. Knowledge is power and whoever controls the main communication channels can control the narrative right now.

---

###11. Definitions

It should be made clear that there is no such thing as an ‘official’ definition. These definitions are the ones that we feel are most logical and representative.

**Hard Fork** - A hard fork is a change the consensus logic of the network, such that anyone who does not upgrade to the new consensus logic will not be a part of the new network. The are different types of hard fork.

**Spinoff** - A spinoff is a type of hard fork where not all participants in the network agree to the new constitutional principles or consensus logic. In this situation the spinoff will have somewhere between 0-100% of the network share which is made up of market cap and participants. Depending on whether a spinoff has the same proof of work the spinoff will also take a share of the miners on the network.

**Participant** - Anyone who takes part in the bitcoin economy. That could be a user, speculator, miner, developer, business or investor.

**Altcoin** - A cryptocurrency that starts with it’s own genesis block.

---

###12. FAQ

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

###13. Contribute


Calling all devs and non-devs alike: Help us bring Bitcoin to the world!

Start the conversation on reddit at [reddit.com/r/btcfork](https://www.reddit.com/r/btcfork)

Vote on BTC Fork Constitution and features at [btcfork.consider.it](https://www.btcfork.consider.it)

Contribute code or testing at [github.com/BTCfork](https://www.github.com/BTCfork)

Follow us on Twitter at [twitter.com/btcfork](https://www.twitter.com/btcfork)

Join us on Telegram at [@BTCFork](https://telegram.me/BTCFork)

Join our Slack (automated invitation coming soon.)
