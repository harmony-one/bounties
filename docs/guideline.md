# Guidelines for developers on bounties

# 1 Content of bounties

### 1.1 Purpose of Bounties

* We can use external developers with coding experience and skill sets.
* Give out rewards to make larger impact in developer (Gitcoin, etc.) community.
* To show the fact that we are technical, product focused, and decentralized.

### 1.2 Catagories of Bounties

Based on the existing bounties at [our bounty repository](harmony.one/bounties) as 5/23/2021, the bounties can be majorly categorized to the following types:

#### 1.2.1 Internal bounties

##### [Harmony Node](https://github.com/harmony-one/harmony)

These are bounties that have some updates on Harmony node program. Bounties are most likely to be proposed by core developers. Most bounties are adding new features. E.g.

* [Rosetta API Extension](https://github.com/harmony-one/bounties/issues/3)
* [Harmony Config V2.0.0](https://github.com/harmony-one/bounties/issues/34)
* [Account abstraction of EIP-2938](https://github.com/harmony-one/bounties/issues/35)

##### Internal Services

This catagory is about bounties that helps improve or adding new feature to the existing harmony services provided by harmony team.

* [Explorer V2 Frontend](https://github.com/harmony-one/bounties/issues/37)
* [Bridge dashboard with statistics](https://github.com/harmony-one/bounties/issues/26)
* [ether.js as wrapper for RPC Provider](https://github.com/harmony-one/bounties/issues/20)
* [Contract code verification tool](https://github.com/harmony-one/bounties/issues/27)

##### Toolings

* [Horizon Bridge Subgraphs](https://github.com/harmony-one/bounties/issues/15)
* [Harmony Subgraphs: Transactions, HRC20 and HRC721](https://github.com/harmony-one/bounties/issues/10)
* [analytics.harmony.one](https://github.com/harmony-one/bounties/issues/39)

#### 1.2.2 External bounties

##### External collaborations and integrations

* Bridges ([Terra](https://github.com/harmony-one/bounties/issues/32), [Celo](https://github.com/harmony-one/bounties/issues/33))
* API integration ([0x](https://github.com/harmony-one/bounties/issues/38), [Trezor](https://github.com/harmony-one/bounties/issues/29), [UMA](https://github.com/harmony-one/bounties/issues/12))
* Misc ([Humming bot](https://github.com/harmony-one/bounties/issues/16))

##### Ecosystem and DAPPS

* [Argent Wallet](https://github.com/harmony-one/bounties/issues/31)
* [Harmony Name Service](https://github.com/harmony-one/bounties/issues/13)
* [PoolTogether](https://github.com/harmony-one/bounties/issues/44)
* [Indonesia Rupiah Token (IDRT) stablecoin](https://github.com/harmony-one/bounties/issues/11)

#### 1.2.3 Research bounties

* [1s Finality](https://github.com/harmony-one/bounties/issues/14)
* [nnet](https://github.com/harmony-one/bounties/issues/25)
* [A lot more ideas](https://docs.google.com/spreadsheets/u/1/d/1J3gMrq52Ho75fpw716Am_5akjVsg6U5brHHSy1z4tDM/edit#gid=527101002)

## 2 "Good" bounties

### 2.1 What makes a good bounty?

First, what is the characteristics of bounties?

1. The candidates are all developers. And most of them can work alone to complete a bounty.
2. The candidate may not have prior knowledge to Harmony blockchain.
3. The candidate has the flexibility to contribute to a single project or work on multiple projects.

This will give several insights to what a good bounty should be:

1. Self-contained.

   This means the bounty would better not require help or support from anyone or anything else during the process, it is complete by itself. 

   If the self-contained cannot be contained for a bounty, you need to provide with a clean scope with lesser boundary.

   Sometimes this can be compromised through clean writing and some helpful conversation at the bootstrap. 

2. No ambiguity in project description.

   For engineers, less ambiguity the better. Treat them as high-level coding machine. You need to strictly define the starting point and target point, and let them improvise in the process. It would be very helpful to define the starting/ending with some engineering documentation.

3. Well defined acceptance criteria.

   This is the "ending point" which we talked about. Do not be afraid to add strict and detailed criterias. Actually more strict you are in acceptance criteria, the happerer the engineer is. Providing some test scenarios would help for both developer and the proposer of the bounty.

4. No business included or long-term dev-ops.

   Since the candidates are developers works in short term, do not have business operation engaged. For programmers, the simpler, the better. If the project requires long-term dev-ops support, we need to send someone to take the project after finished.

6. About the size of the bounty.

   The size of the bounty is not a "criteria" of a good bounty. A bounty can be large or small. But practically, the most welcomed bounty shall be around 1-6 human weeks.

### 2.2 How to write a good bounty?

There are four required fields:

1. Description
2. Context (Optional)
3. Acceptance Criteria
4. Reward

Let's just see some examples (Please do not take it personal) :

1. A self-contained bounty: [ether.js provider](https://github.com/harmony-one/bounties/issues/20)
2. A bad example: [0x Api intergration](https://github.com/harmony-one/bounties/issues/38)
3. A not very self-contained bounty: [harmonyConfig v2.0.0](https://github.com/harmony-one/bounties/issues/34)
4. An external ecosystem bounty: [Harmony Name Service](https://github.com/harmony-one/bounties/issues/13)
