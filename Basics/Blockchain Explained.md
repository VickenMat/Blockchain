1) Explain what it is
2) Break down block and chain
4) Explain why it's useful with Google sheets example
5) Explain what it can be used for
6) Why should you care?

- One way hash functions to link blocks

What is a blockchain?
- At it's simplest, the [[Blockchain]] is a way of storing information
- At it's core, a blockchain is a secure and decentralized digital ledger that records and verifies transactions or data
	- It does so by creating an unchangeable and transparent record of these transaction, which is maintained by a network of computers rather than a central authority
	- The core function of a blockchain is to ensure the security, integrity, and trustworthiness of the recorded information
- A blockchain is a secure database shared across a network of participants where real time information is available to all members at the same time
- A distributed database that maintains a continuously growing list of ordered records, called blocks
	- These blocks are linked cryptographically, with each block containing a hash of the previous block, timestamp and transaction data
- Decentralized public ledger that keeps track of transactions across numerous computers
	- Essentially a network of computers, or "nodes" that share the same transaction history
- Digital ledger that records information in a secure and unchangeable way
	- It's like a chain of digital blocks, where each block contains a list of transactions and new blocks are added as more transactions occur
	- This ledger is maintained by a network of computers rather than a central authority
- A blockchain is a distributed and decentralized digital ledger that records transactions in a secure and immutable manner
	- Its a chain of blocks, where each block contains a list of transactions 
	- These transactions are grouped together into a block and each new block is linked to the previous one, forming a chain
	- This chain of blocks is stored on a network of computers, and each participant in the network has a copy of the entire blockchain
- Let's divide blockchain into 2 parts
	- Block
		- A block is a set of transactions that occur over the network
	- Chain
		- The chain is where blocks are linked to each other in a way where the next block contains a hash to the previous one
		- Even the smallest change will change the hash and break the whole chain, making it difficult to tamper data

![Blockchain Example](https://assets-global.website-files.com/5d2dd7e1b4a76d8b803ac1aa/5e81c66dd4cabdcc1674a08d_0nt8_YaCOJ_ED51A163rrtjq4mA4Qp1MsIXdDUR4iUAVBYYM5thrRmXCJsZHNa95-yQ3poZep9S8hkUffFkdqbIt9EXmk0bUbLfV0TJWOTH2dwUp6sSsCtnPx8esAE_DROgkKAAT.png)

In More Detail
1) 
2) 

What is the goal of a blockchain
- Allow information to be recorded and distributed digitally but not edited
- The whole point of using a blockchain is to allow trustless data sharing in a secure and tamper proof method *update this*
- Share information amongst all parties that access it via an application
- Keep records
	- Digital ledger that records transactions
	- Keeps a record of who sent what to whom and when
	- Can be applied to any transfer of information
- Security
	- Immutable
- Decentralization
	- Unlike a bank or government, blockchain is maintained by nodes
	- Nodes work together to validate and record transactions
	- Decentralization ensures that no single entity has control over the entire blockchain, making it resistant to censorship and manipulation

Blockchain ABC
- [[Decentralization]]
	- No single controlling entity
	- The blockchain operates on a network of computers (nodes) which work together to validate and record transactions
	- Reduces the risk of a single point of failure and makes the system more resilient
- [[Immutability]]
	- Once a transaction is recorded in a block, it is extremely difficult to alter or delete, ensuring the integrity of the data
	- Irreversible
	- Permanent
- [[Distributed]]
	- All nodes have a copy of the blockchain
- [[Transparent]]
	- The information stored on a blockchain is visible to all participants in the network, providing transparency and accountability
- [[Security]]
	- Blockchains use cryptographic techniques to secure transactions
- [[Consensus]] Mechanisms
	- [[Proof of Work]]
	- [[Proof of Stake]]
	- Employ these mechanisms to ensure that all nodes in the network agree on the validity of transactions and the order in which they are added to the blockchain
- [[Trust]]
	- Blockchains create trust in environments where trust may be lacking, as all participants can independently verify transactions and data
	- They do not need to trust each other, only the mechanism behind the transaction being reliable

Benefits
- Eliminate intermediaries/middle men
	- Reduces fees
	- Reduces delays
- Simplify record keeping
- Cost savings
- Increased efficiency


Comparison
- Imagine a digital notebook like a global Google sheets that anyone can write in - *Global Ledger*
	- Think of a Google spreadsheet being hosted on Google's servers, which have a single point of failure and can be hacked, destroyed, or manipulated
	- Instead of a central point like Google's servers, it's maintained by a [[Peer to peer]] network of computers called [[Node]]s all around the world
	- These nodes have access to the full blockchain and are responsible for validating new records along with securing the database against malicious actors
	- 
- Whenever someone writes something new, it gets added to the end of the notebook and can never be changed - *Immutable*
- Everyone can see what's been written in the notebook, and they know it's true because it cannot be changed - *Transparent*
Applications
- Digital money (cryptocurrency)
- Voting
	- Each person eligible to vote has one token sent to an address
- Health care
	- Store patients health records
- Supply chain
	- Food and drug traceability
- Digital ownership
- Insurance
- Real estate
- Energy
- Identity Management
	- Verify identity fraud
- Land Registry
	- Digital certificate of ownership