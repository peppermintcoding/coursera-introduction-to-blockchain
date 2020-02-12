# Blockchain Design Principles

Privacy and security are the underlying principles of blockchain. But it can do more than that. It can protect civil and property rights. There are seven design principles to blockchain.

## Network Integrity

Trust does not come from an outside source, a third party like a bank or insitution. So the four values, *honesty*, *consideration*, *accountability* and *transparancy*, are coded into the blockchain directly. This integrity is distributed among all of the nodes and acting without it comes with great cost or loss of reputation.
The problem with integrity online is because money and assets aren't easy to share online. Money can't exist at two places at once. Online money can be spend twice without any of the others knowing about it, the *double spending problem*. Therefore we need a bank to validate transactions.
On the bitcoin blockchain every transaction is timestamped and can't be spend again after that. The network relies on *proof of work* for trust. By solving a puzzle with computing power it validates a block on the blockchain. Solving the problem is hard, but validating that the problem is solving is easy.
In Ehtherium this proof will move from proof of work to *proof of stake*. Social networks can also be used for proof. When someone is trustworthy they get a vote.
On the blockchain, the truth of the present relies on the proof of the past. For a bitcoin to be valid it must reference its history on the blockchain. Therefore the blockchain must be present in its entirety and can't be cut up easily.


## Consensus Mechanisms

+ *Proof of Work*
Mining is the central part of securing a blockchain through proof of work. Miners need to spend some form of ressource, electricity, processing power, to confirm transactions and get compensation in form of tokens. This reward for securing the network serves as an incentive to rather play by the rules than use the ressources to attack the network. Also by spending fiat for electricity it converts fiat into cryptocurrency by design.
+ *Proof of Stake*
Similarly to shareholders having the privilege to partake in consensus mechanisms, a proof of stake mechanism gives someone who holds an amount of coins a voting right. This can decrease the needed electricity and computing power for the proof of work substantially. It also makes attacking the network harder because to attack it one needs a big stake in the coin supply to begin with.
On Ethereum 2.0 everyone can lock up some ether to stake it. Now one can bet on a block. If the block isn't valid the node will lose its bet ether or if the block is valid it gets a reward.
To ensure no hard fork of the blockchain occurs ethereum uses the *Casper* protocol. Here when someone bets on an invalid block they lose all their staking ether.
+ *Delegated Proof of Stake*
To scale up the proof of stake to a large number of exchanges per second the coin *EOS* for example uses a delegated proof of stake. Every token holder can vote for a block maker. The entity with most votes can then issue a new block.
+ *Proof of Burn*
A node can choose the status of the blockchain by burning value they are holding. By sending the coin in for example bitcoin to an unspend address it can get a reward in the local coin. This would burn the inital coin and generate the local coin for it in exchange.
+ *Practical Byzantine failt tolerant Mechanism*
Every node distributes a public key. A node can confirm messages getting through it and with enough reactions a consensus is met.
+ *Proof of Elapsed Time*
Every node asks for a hold-up time from its local group. The node with the briefest hold-up time is next to offer a block. Every privately trusted group sign the potential block and others can then confirm it.
+ *Proof of Importance*
Here a node's influence does not only depend on the number of coins but on other factors as well. Users are given a utility rating for the network by the network's algorithm.