# Decentralized Consensus Challenge
------

Congratulations on making it to the Decentralized Consensus Challenge! Blockchain's have several layers starting from the protocol level all the way up to the dApp layer. Your challenge
today is to **EITHER** extend Rchain **OR** implement an ERC20 Token! ​ 

**YOU ONLY NEED TO CHOOSE 1 CHALLENGE** 

**Submission equals invitation to interview!** **Incomplete solutions are welcomed!**

**Submit a single PDF containing**

 1. Write up on your process (w/ screenshots)
 2. Link to your Github repository containing challenge code
 3. Screenshot of showing successful completion of the challenge
	 * Challenge 1 (Extending Rchain): Screenshots of *get_total_tokens()* and *get_transactions_for()* output.
	 * Challenge 2 (ERC20 Token): Screenshots of contract deployed to Ropsten with time/date stamp and link to smart contract's public hash via [Ropsten scanner](https://ropsten.etherscan.io/).

We will ask you to run the code and demo it live!

#### Tips On Getting Started:
* Dive Deep into the code! Then build fast!
* Find resources online.
* Keep it simple.
* Test driven development.


## Challenge 1 
#### Extending Rchain + Starting Resources:

 1. Understand and familiarize with the [Rchain codebase](https://github.com/Mereep/rchain)
	 * Learning Rust [[1]](https://doc.rust-lang.org/rust-by-example/)[[2]](https://youtu.be/U1EFgCNLDB8) 
 2. Run Rchain as per [example](https://github.com/Mereep/rchain/raw/gh-pages/Blockchain%20Article%20Part%201.pdf) 
	 * Multiple users on the network
	 * Both example attacks
 3.  Extend *World State* with *get_total_tokens()* to display the current token total in the network.
	 * Tip: can be calculated by walking through the chain
 4. Extend *World State* with *get_transactions_for()*  display all the transactions in coronological order and block # for a given id. 

#### Optional:
* Dockerize the Rchain codebase 
* Scale to 10 users


## Challenge 2
#### ERC20 Token + Starting Resources:

 1.  Understand the fundamentals 
	 * [What is Ethereum?](https://www.youtube.com/watch?v=TDGq4aeevgY) 
	 * [What is a smart contract?](https://youtu.be/ZE2HxTmxfrI) 
	 * [What is an ERC20 Token?](https://blockgeeks.com/guides/erc20-tokens/)
 2. Implement **YOUR OWN** [ERC20 Token](https://www.toptal.com/ethereum/create-erc20-token-tutorial)
	 * Add a comment at the top of your contract saying *Insight Decentralized Consensus Challenge*
 3. Deploy the Smart Contract to Ethereum testnet Ropsten using [Truffle](https://www.trufflesuite.com/blog/an-easier-way-to-deploy-your-smart-contracts)

#### Optional:
* Deploy contract to a local testnet 

---------

##### Please have your code ready to demo!



