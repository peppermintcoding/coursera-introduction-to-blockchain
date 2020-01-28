# The Internet of Information and the Internet of Value

While our current internet is mainly a form of exchanging information the second era of the internet will be about exchanging value. In 2009 *Satoshi Nakamoto* launchen bitcoin, a peer-to-peer electronic cash system.
The internet is designed to excahnge information peer-to-peer but was never intended for the exchange of value in the same way. It wasn't designed to protect any assets either. Only with intermediate companys like banks and governments an exchange could take place.
With blokchain we can enforce trust between any two people in the world, wether they know each other or not.

When the internet was created media and information was democratized. Everybody could produce and exchange any information on the network. It leveled the playing field for everybody. With a far lower barrier to entry than before everybody, anywhere could produce wealth.
Now the internet consists of a few global corporations who control most of the traffic, and most of our data. Because we still need banks to verify transactions we still see some 2,5 billion people excluded from the global financial system. But only only people are exlcuded, conversations and ideas are too if they don't conform to a specific company's rule.
Data is the new asset class of our time. Right now, only a few have control over our personal data and it is getting more difficult to protect personal privacy.

When we send data over the internet, like an image we are not sending the original but a copy. This works fine for images and texts eventhough we still don't know how the recipiant will use the image. This falls apart when thinking about sending money. That's the reason even in the age of the internet, banks are necessary for money transaction or any other transaction of value. After confirming our identity these middle men then take a percentage cut of every transaction but also capture data.
With the blockchain, a peer-to-peer value exchange medium, we ensure integrity of data without a third party.

# The Trust Protocol

Third partys control data on centralized servers. When these servers are breached all personal data is at risk. Nick Szabo wrote a short paper, The God Protocol, which describes the relationship of users and these third partys in the middle of all transactions. Trusting them is a leap of faith, making them nothing else than gods. Without faith there is no way to know if they are truly trustworthy.
After the 2008 financial meltdown *Bitcoin* was introduced. Not one party had the control but a network of computers was needed to make transactions. Transactions are verified through mass collaboration powered by anyone who wants to participate. Bitcoin, as any other cryptocurrency, runs on the underlying structure of the blockchain.
While the *blockchain* seems new it has it origin in 1991 when Stuart Haber and Scott Stornetta wrote the paper "How to Time-Stamp a Digital Document", a concept for ensuring signing a document at a specific time. They used a Merkle Tree, or hash tree, where every 'block' stored multiple transactions.
In 1996 Ross Anderson described in his paper "The Eternity Service" a decentralized storage system with the inability to delete any updates made to the system. 
While some people build simplified blockchains, they all needed trust between the users for making changes to the system.

Even banks are using blockchains internally to lower costs, gain greater security and fewer errors. The blockchain underneath bitcoin works in the same way but it is not stored on some central server secured from the public but on a public network, the internet. The blockchain is a chain of blocks with transactions. The blockchain is not the product but the protocol, in a way bitcoin is the prodcut. While http makes the internet work it's not the product but many prodcuts are being built on top of the http protocol.
Every 10 minutes a block on the bitcoin blockchain is verified, cleared and stored. It is linked to the block before it creating this chain. To steal a bitcoin, the history of it on the blockchain has to be changed completely, making theft particially impossible. 
While putting a coin on a blockchain representing some monetary value is one way of using the blockchain as its protocol there are many more. Any certificate or license, deeds, titles, educational degrees or even votes and medical records can be kept on a blockchain. Origins of food and their ingredients can be tracked. Everything that can be represented in code can be stored on a blockchain. Especially with the upcoming internet of things more and more use cases become apparent. Transaction of goods and information between these small devices could run on a global ledgers, a ledger of everything.

# Trust

Trust in business is the expectation that the other part will act with integrity. 
+ Honesty
+ Consideration
+ Accountability
+ Transparency
Because we can't know with whom we are doing business with on the internet we need to rely on third parties. By doing so they charge a small fee. With blockchain this fee can be given back to the network instead of a single company. With smart contracts on top of the blockchain salaries for company CEOs can even be automated, only giving them a bonus if the company is doing well. Tax money can be tracked with a blockchain and will ensure it is being used where it was promised. Through the transparancy trust is build.


# How does the blockchain work?

First we need to send a message with a transaction to the network. The address to where I am sending the transaction is the public key of that person and then I sign the message with my private key. There is no way to reverse a transaction once it is made. Then the network, a network of nodes, will verify a block with all the current transactions.
A math problem will need to be solved to verify the block. That's what miners do. A block consists of all the transactions, the hash of the previous block, the hash of the current block and a *nonce*. The miners are trying to figure out the nonce so the block's hash matches the current block's hash. It's called *proof of work*. When a node solves the problem it gets a reward from the network and the block gets added to the blockchain.
