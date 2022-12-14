# DecentralizationIndex
Blockchains by Number of Nodes / Validators.

My notes from SoK: Blockchain Decentralization (https://arxiv.org/pdf/2205.04256.pdf)

1. Protocol-based:
- Consensus & Network
- Governance
2. User-based:
- Wealth
- Transaction

1. Wallet user growth, 
2. Active address growth, 
3. Transaction count
4. Growth, and payment count growth are strongly associated with returns.

In light of the existing blockchain decentralization literature and to comprehensively analyze the decentralization of blockchain systems, we further elaborate on the three layers of infrastructure, incentive, and application that consolidate the layers used in the blockchain modeling and security literature. 

3 layers

1. Infrastructure: The infrastructure layer consists of data, network, and consensus layers that include the collection of data into blocks, the communication model (distributed networking, data forwarding, and verification), and the consensus mechanism (e.g. PoW, DPoS).
2. Incentive: The incentive layer consists of economic rewards to the blockchain system, including incentive mechanisms of the block creation process and token/asset distribution.
3. Application: The application layer consists of contract and application layers that include smart contracts, algorithms, and mechanisms that are used to facilitate high-level applications built on top of the blockchain system and all blockchain use cases, such as DeFi.

- Consensus and network decentralization are connected to the infrastructure layer.
- Wealth decentralization is connected to the incentive layer.
- Governance and transaction decentralization are connected to the application layer.

1. Consensus Decentralization:

- a state where all the entities or nodes of a blockchain system maintain the same distributed ledger. Decentralization of consensus is crucial to the security of a blockchain system.
- the “evenness” in the distribution of “mining power” in proof of work (PoW) permissionless blockchains.
- the distribution in voting delegation power (the power to delegate creators of blocks) for delegated proof of stake (DPoS) blockchains.
- the decentralization in the participation of consensus processes, such as mining in PoW protocols and staking or voting in proof of stake (PoS)
protocols.

Metrics to measure consensus decentralization: Gini coefficient, Shannon entropy, and the Nakamoto coefficient. And game theory to model consensus participation and equilibrium methods.
 
2. Network Decentralization:

- Fragmentation of control over the network, manifested in the security and fairness of a network system.
- Depicts decentralization in the underlying blockchain peerto-peer network infrastructure, such as how users communicate with the network and how nodes communicate with each other.

Metrics to measure network decentralization: Geographical distribution of nodes.

3. Wealth Decentralization:

- the evenness in the distribution of wealth in the blockchain literature.
- captures the decentralization of monetary assets in tokens and native cryptocurrencies distributed across blockchain users.

Metrics to measure wealth decentralization: Gini coefficient.

4. Governance Decentralization:

- the means of achieving the direction, control, and coordination of stakeholders within the context of a given blockchain project to which they jointly contribute.
- the extent to which control over the blockchain is shared between platform owners and participants.
- a fully decentralized governance structure where platform users collectively have full governance control and can represent their perspectives.
- the decentralization of ownership and decisionmaking power on blockchain platforms and how they are shared between owners and participants.

5. Transaction Decentralization

- when all financial assets in a given market are traded in multiple coexisting and interconnected trading venues.
- proportion of transactions conducted by the top nodes in value transacted.
- the evenness in the distribution of transactions across users of a blockchain.

In reality, most blockchain projects have a “foundation” or community of developers that have disproportionate levels of influence on decision making and governing.

..blockchains are often subject to a few parties who actually operate the system.

..market capitalization often has a U-shaped relationship with governance decentralization, where the best market performance is associated with a middle level of decentralization.

The Nakamoto coefficient is defined as the number of entities in a given subsystem that is required to reach 51% of the total capacity.

..Bitcoin is 12% more decentralized than Ethereum in terms of mining power and 9% more decentralized in terms of wealth.

..both Bitcoin and Ethereum networks have a few mining pools that govern the whole network and therefore tend to behave like centralized systems.

..the prevalence of voting collusion on DPoS-based blockchains that lead to centralization.

To fill the gap in the literature on the decentralization of transactions, we propose a new index based on Shannon entropy, which is often used to measure decentralization in areas such as consensus decentralization. The index is adapted from Shannon entropy to measure the degree of randomness in the distribution of transactions with, a higher value indicating more disorder in the distribution and more decentralization and a lower value of entropy indicating less disorder and more centralization.

value of each transaction..
weight of each transaction..


..Governance Tokens: tokens that developers create to allow token holders to influence governance decisions in a blockchain system, usually representing voting power in a DeFi protocol.

..tokens with a higher TVL ranking tend to be more decentralized. This again shows that tokens with greater market demand and utilization tend to be more decentralized.

