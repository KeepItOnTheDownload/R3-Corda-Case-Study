# R3 Corda – A Next Generation Blockchain Platform
<img class="size-full wp-image-3728 alignleft" src="https://www.cointrust.com/wp-content/uploads/2018/07/r3.jpg" alt="" width="380" height="250">

## Introduction:

In the evolution of current FinTech technology trends, there has been much to talk about since the release of the implementation paper of Bitcoin 2008, and the underlying blockchain technology. The globe slowly but surely started to take notice of the attention paid by major institutions world-wide investing in this technology, and the disruptions it caused in our financial markets. Quickly, major tech companies and banks began a race to find the best solutions utilizing this tech to solve costly business functions caused by the evolution of the internet and global technological advancements. 

This case study delves into R3 Corda–a next generation blockchain platform–describing their core technologies, history and the unique attributes the Corda platforms offers, versus the competing platforms–Ethereum and Bitcoin Blockchain. It also delves into the technologies within blockchain, smart contracts and distributive ledger technology (DLT). 

## R3 Beginnings:

If you were to walk into the R3 London Wall office, not only are you met with breath taking views of the center of London, you will be met with an energy of creativity buzzing about. Code and flow charts span the walls, and all the desks are open so as you walk by you can see the work in its process. R3 Corda was founded in 2013 (originally R3CEV) by David Rutter.  Since then, R3 Corda has managed to raise over $120 million dollars to fund the creation of its cutting edge platform, with a consortium of over 300 firms working together to build distributed applications across not only the financial services industry, but insurance, healthcare, trade, finance, supply chain, and digital assets. They now have over 200 hundred employees in offices in New York, Dublin, Hong Kong, London, Singapore and Brazil. Their business model is still evolving due to the nature of the consortium and the changing needs of their clients. They have the options to monetize under the models of software-as-a-service, full-stack, vertically-integrated, and/or platform as a service. For the purpose of this study I will not go into this further, as the true profitability and value of Corda is still evolving, and should not be a metric of success yet, as they continue to gain wide support and funding to date. 

Michael King, an employee of R3, in 2018 wrote a study, “R3 Corda: A Distributed Ledger Technology For Financial services”.  In it, he goes in-depth into the exciting but lengthy process to build the platform. The roadmap was as follows: In 2013, Rutter started R3CEV, where the initial R represents Rutter's name, 3 represents the total number of partners (David Rutter, Todd McDonald and Jesse Edwards) and CEV captures the focus of investing in the evolution of crypto, exchanges, and venture technologies. He also started  Liquidity Edge LLC at the same time, which focused on developing an electronic trading platform for U.S Treasuries. All this was after a successful career as the chief executive officer of the British Brokerage firm ICAP Plc's. In this role, Rutter had been responsible for pitching to bank clients the adoption and implementation of ICAPS Plc's electronic trading platforms, Brokertec and the foreign exchange platform, EBS. 

During Rutter’s successful career, he identified that each year financial market participants spent billions of dollars on the complex and time-consuming process of clearing, settlement and record keeping when trading financial assets through an exchange, intermediary, or 'over-the-counter' trades made directly through counterparties.  Differing trade processes and regulation within each specific financial asset creates unharmonized standards throughout the industry. This complex process leads to post-trade processing problems and settlement risk–the risk that a counterparty failed to deliver a security or transfer payment by the settlement date. Ultimately, the underlying issue is an inability to reach consensus between distrusting financial parties.

Rutter believed the solution to reaching a consensus between banks could be solved faster if they pooled their resources together to collectively develop a solution to the problem, rather than each institution tackling it themselves.  Rutter then formed the R3 Consortium. Initially, he hosted three roundtables to debate blockchain and its applications with bankers, venture capitalists, technology companies, and other stakeholders. On September 15, 2015, R3CEV issued a press release announcing that nine of the world's leading banks had formed a partnership to design and deliver an advanced encrypted distributed ledger for the global financial markets. The initial banks were a mixture of leading global banks: Barclays, BBVA, Commonwealth Bank of Australia, Credit Suisse, Goldman Sachs, J.P. Morgan, State Street, Royal Bank of Scotland, and UBS. However, Rutter prefers to describe the consortium as a massive collaboration among a network of partners. Then, in November, 2016, the CEV initials were formally dropped and the company became known simply as R3 Corda. (King, 2018)

## Corda The Solution:
In 2018, Brown released “The Corda Platform – An Introduction”, stating the vision of Corda:
“…a future where legal agreements such as business contracts are recorded and automatically managed without error, where anybody can transact seamlessly for any contractual purpose without friction. We believe markets will move towards models where parties to contracts collaborate to maintain accurate, shared records rather than maintaining their own independent and inconsistent systems which require extensive reconciliation processes to ensure consistency. Duplicates, reconciliations, failed matches and breaks will be things of the past. Isolated pools of trapped assets will be no more.” 

### *Project Genesis*
In order to get to the above vision, R3’s team and members mapped out the problem and functional requirements of the member banks and set out to find the solution. Rutter then divided the banks into two working groups, Lab and Research Center (LRC), based out of New York and Architecture Working Group (AWG), based out of London. Between January 19 and February 29, 2016, the LRC group led Project Genesis, using five vendors: Chain, Eris Industries, Ethereum, IBM Hyperledger, and Intel Sawtooth, alongside 42 bank members to evaluate the strength and weakness of previous DLT solutions to simulate both bilateral trades between two counterparties and multilateral trades between multiple counterparties. With this collaborative project they identified four key insights:

•	By deploying smart contracts for actively traded asset classes, DLT could be applied to real-world financial market processes. 

•	There was already historically a wide range of experience and understanding of DLT across the banks. 

•	With the right structure and governance, it was possible not only for banks but other partners to collaborate on the development of a shared distributed ledger. 

•	R3’s members prefer an open-source industry standard that included opportunities for hands-on development, code review and testing against a comprehensive set of evaluation criteria.  (King, 2018)

### *The Corda Model and Global Network*

Rutter then recruited Richard Gendal Brown as the chief technology officer, previously the executive architect for banking and financial market industry innovation at IBM, United Kingdom. In mid-September 2015 Brown led the AWG to understand what current technology would be appropriate for the financial markets, from a transaction process and an information security point of view. 

Brown explained the need for creating the right technology: 
The reality is that solutions based on selecting the design first and then trying to apply it to arbitrary problems never work out well. Every successful project I’ve worked on started with the requirements, not some cool piece of technology, and I was determined to bring that discipline into our work at R3. 

In 2016, the AWG introduces Corda: A DLT for the financial services, with the unique attributes utilizing existing distributed ledger technology. King in 2018 notes, the underlying goals that Brown and the AWG used as a framework for the development of the platform was;

•	to provide an immutable record of financial events that encompassed the banks’ decision-making logic. 

•	 to solve the problem of untrusting nodes by combining cryptography and smart contracts with features such as privacy and interoperability to reach a consensus.

•	lastly, to satisfy the risk and compliance requirements demanded in the highly-regulated, financial service industry. 

Richard Brown further goes on to explain in his paper, “The Corda Platform: An Introduction” in 2018, Corda provides three main tools to achieve global distributed consensus: 

•	 Smart contract logic which specifies constraints that ensure state transactions are valid according to pre-agreed rules, described in contract code as part of CorDapps. 

•	Uniqueness and timestamping services known as notary pools to order transactions temporally and eliminate conflicts.

•	A unique component called the flow framework which simplifies the proccess of writing complex multi-step protocols between multiple mutually distrusting parties across the internet. 

Corda executes the smart contract logic via the powerful Java Virtual Machine (JVM) that allows for the building of an array of decentralized applications and complex contract code. According to Brown, they are legally enforceable under the definition of Clack, Jakshi, Braine; our smart contract is an agreement whose execution is both automat-able by computer code working with human input and control, and whose rights and obligations, as expressed in legal prose, are legally enforceable. (Brown, 2018)

Moreover, the Corda platform, is not a true blockchain, unlike popular belief and offers more than what current distributive ledger technology can offer, the differences between the two are discussed in deoth below. However, it is key to mention that Corda offers the unique attribute that transactions can contain multiple notaries, that can use varying algorithms to reach a consensus. Thus, it is not tied to one specific consensus algorithm like competing platforms (see Corda Vs. the Competition)  The flow framework gives Corda the uniqueness of creating its own network, wherein; a group of participants who collaborate for a specific business purpose can also participate in other business networks or transactions with other nodes at the same time and with the same infrastructure. (Hearn, 2016) 

With these advancements, it became clear to Brown that this technology was not only applicable to the financial industry, but has demonstrated that Corda has broad applicability, well beyond banking and was truly the next generation of blockchain. Corda network is intended to enable a large number of overlap- ping, competing and collaborating Business networks to form, unified by just enough commonality to facilitate interoperability of nodes, and compatibility of assets and other contracts managed by those nodes. (Brown, 2018) R3 Corda thus became a top competitor in the game. 

## Blockchain, DLT & Blockchain Enterprise Software Development: 

Since the invention of the Internet, the world economy has benefited from the economic, financial, and social evolutions made by the creation of email, the World Wide Web, dot-coms, social media, the mobile web, big data cloud computing, the early days of the Internet of Things ("IoT"), and peer-to-peer network payment systems, i.e., PayPal, Venmo (Ashraf and S Adrash 2017). In the last decade, interest in Blockchain Technology has gained the attention of regulators, consultants, technology firms, and academia, as they debate the power the innovation of the technology has to disrupt the current financial and regulatory markets, reminiscent of the disruption the Internet and IoT has achieved.

Blockchain technology has been inextricably linked to the reference implementation of the widely growing cryptocurrency Bitcoin. In 2008, the illusive creator(s) Satoshi Nakamoto published a white paper, "Bitcoin: A Peer-to Peer Electronic Cash System." The paper was published on The Cryptography Mailing list on the site metzdowd.com. He combined the already established concepts developed since the 1970s such as peer-to-peer networks and cryptography.  Blockchain is the first software capable of mining the units phic signatures, hashing, and Merkle tree implementations. The term blockchain was then coined as the back-end system for a network of users that could engage in secure peer-to-peer financial transactions, using the internet and eliminating the need for financial intermediaries. This gave rise not only to the notion of decentralized trustless transactions but. a single public distributed ledger that is accessible across the network.
 
The emerging blockchain technology has powers far beyond currencies and, in fact, allows for parties to send, receive, and record value or information, using private or public key encryptions that are secure, verified, and decentralized. The open source code of the blockchain allows developers to continue to update and build new code which moves the technology beyond crypto currencies like Bitcoin. For example, applications have been built for: capital raising, trading, clearing and settlement, global payment, deposits and lending, property and casualty claims processing, digital identity management and authentication, and RegTech solutions. 

### *Blockchain & Distributive Ledger Technology*
 
A ledger is originally a term used in accounting referring to a record of the ownership of a particular asset/s. With the rise of computers, ledgers became electronic or digital for speed and accuracy. Where aggregated, the data, particular surrounding financial assets, would be entrusted to a third party such as a custodian or securities depository. to maintain the accuracy of the centralized ledger. However, this leaves issues of human error, fraud, misstatements or hacks. For example, in any given organization with multiple locations each branch reconciles its own decentralized ledger–a ledger held and updated in different locations–and then updates to the master centralized ledger for reconciliation. However, if any one decentralized ledger is inaccurate the validity of the information is compromised.  
 
Whereas, a distributed ledger is a database of records which isn't stored or reconciled by any one central body; a complete record of ownership and transactions for any given asset can have multiple identical copies held in different locations. Effectively, this eliminates the need to hold multiple copies and reconcile to a master. However, in order to accomplish this, the technology must update the ledger frequently to ensure its accuracy. Distributed Ledger Technology–or DLT–is compromised of computer programs and protocols that are used for the recording, sharing and synchronizing of distributed ledgers. This technology has been referred to by information technology specialties as middleware. Middleware addresses the downside of possible information silos occurring due to a complex organizational data infrastructure. For example, companies who have different IT systems in place who go through a merger, will experience silos of information that cannot be transferred.  Middleware software acts as a bridge between the applications and the database, eliminating silos.
 
In contrast, a Blockchain is a distributed ledger with a very specific technological foundation, hence, the terms are not interchangeable. A blockchain consists of chronological data points that are recorded by a network of computers on individual storage units called blocks. Each block has a list of transactions, a block header, and at least three sets of metadata which includes information regarding the transaction within the block, the data, and a timestamp regarding the proof-of-work algorithm and a “hash” reference to the parent block or the preceding block. A distributed ledger is thus a component of blockchain, but not all distributed ledgers necessarily batch unrelated transaction together into blocks. 
 
Transactions on the blockchain transpire between two parties using public and private key cryptography, which are both compromised of two uniquely related cryptographic keys (or long arbitrary numbers). The public key, as its name implies, is made public so it can function as a reference to a depository (i.e. ATM Cash Deposit), The private key must remain confidential to its owner, as it holds the true value of the transaction (i.e. Bitcoin). The two keys are mathematically tethered to each other as you need one to create the other, which determines its verifiability and its security.
 
This technology allows users to not only securely send currency such as Bitcoin, but also authenticate a message or transaction in such a way that the receiver can verify if it has been altered at any time during the transaction, giving rise to the notion of trustless transactions. Through this process, the Blockchain is creating a “worldwide ledger” that must be reconciled to continuously include the new transaction entered from the multiple computing nodes. As it will be copied multiple times in multiple computing devices with the trait of being in real time, this typically would make the network susceptible to the “double-spending problem” or Byzantine Generals’ Problem. The risks are that digital currency can be spent twice or fraudulently or that multiple copies of information exist.
 
Thus, to ensure accuracy, the process happens via a consensus model. Everyone concerned with the outcome in a group needs to agree on some X, which then means an action Y can take place. In the case of Bitcoin, to establish a distributed trustless consensus, the proof-of-work concept discussed in Nakamoto’s white paper involves scanning for a value that can be verified by executing a single hash. For example, for SHA-256, the hash begins with a number of zeroes. This complicated mathematical equation is believed to ensure transactional verifiability. Providing access to the key is seen as providing consensus for the transaction, wherein a majority of nodes must accept the new transaction for it to be a valid one and be included in the blockchain.
 
Moreover, distributed ledgers were originally designed to be public and accessible to everyone. However, due to varying needs, the ledgers can now be private or public. In private general ledgers, only authorized entities or personnel can access the ledger. This capability does slightly contradict the true purpose of DLTs in that it should be available to everyone on the network. However, it gives a corporation the privacy and security that its members seek and the ability to verify and use the information without exposure to outsiders.

### *Bitcoin Blockchain*
 
Bitcoin is a decentralized peer-to-peer payment system that enables instant online payments to be sent directly from one party to another without going through a financial institution (Nakamoto 2008). In the mining process, a bitcoin is the reward for successful mining, which then can be exchanged for other currencies, products, and services in legal or illegal markets. The mining process can be described as a record-keeping service, and miners are truly keeping the blockchain complete, consistent, and in theory unalterable. Using the Bitcoin software, miners use large amounts of computer power to carry out the proof-of-work method, requiring miners to find a nonce (an arbitrary number only used once) to solve the cryptographic hash in each block that in turn verifies the previous block and adds it to the chain, hence the term blockchain.
  
### *Ethereum & Smart Contracts*
 
Smart contracts are a piece of computer code or agreement capable of verifying, executing, and enforcing a set of instructions. The phrase “smart contracts” was coined by Nick Szabo in 1996 in his first publication, “Smart Contracts: Building Blocks for Digital Free Markets.” The computer code reviews a pre-determined set of inputs, matches them against conditions written in the code, and allows a transaction to be executed only if all necessary conditions are met, creating a decentralized agreement.
  
Vitalik Buterin, a cryptocurrency researcher and programmer, proposed Ethereum in late 2013. Ethereum went live July 30th, 2015, after capital was raised in a crowd sale in the summer of 2014. Ethereum is described as a distributed public Blockchain network that, unlike Bitcoin, focuses on running the programming code of any decentralized application (DAPP) utilizing smart contracts. An Ethereum core innovation, the Ethereum Virtual Machine (EVM) is a Turing complete software that runs on the Ethereum network, it enables anyone to enforce legal documents or run any program or from gambling sites, financial application, insurance companies, social networks, and so on, regardless of the programming language, given enough time and memory. 
 
The mining process is similar to that of Bitcoin; for each block of transaction, miners use hash functions and proof of work. The specific proof-of-work algorithm that Ethereum uses is called “ethash,” once the mathematical equation is solved, miners are rewarded in Ether instead of Bitcoin. Miners in Ethereum do not just verify the transaction as “record-keepers,” as in the case of Bitcoin, but also execute the smart contracts or transactions that need to be verified on the block. They, like Bitcoin miners, are paid in transaction fees (as stated above). As each contract is executed, the price is determined using a mechanism called Gas, which is an internal virtual machine token to detect the relative cost between operations (calculations, storage, memory access, etc.). 

## Corda Vs the Competition:

The R3 team has noted that Corda is not truly a blockchain. As mentioned above, not all distributed ledgers necessarily batch unrelated transaction together into blocks as blockchain distributive ledgers do. Corda is unique in that it also does not bundle transactions into blocks but instead validates each transaction (smart contract) individually, speeding up the processing time that we see as an issue in Bitcoin Blockchain. Instead of mining transactions like in Bitcoin to reach consensus, Corda distributive ledger uses notaries, instead of trusted intermediaries, to record data on an immutable ledger. Instead of global sharing, like Bitcoin Blockchain, Corda maintains privacy within the Corda Network nodes that is permissioned to transact with, not between all participants. Furthermore, Bitcoin transactions have a single, rigid data format and can’t hold the type of data Corda’s contracts (smart contracts) can, because the business logic within the framework can handle higher level tasks, beyond solely transaction verification, which limits Bitcoin applications. 

Ethereum has acquired the second largest market cap in the cryptocurrency world. The blockchain project continues to elicit strong interest from investors, in part because of its application in powering decentralized applications. In comparison, the Corda platform utilizes the powerful Java virtual machine (JVM), similar to Ethereum’s EVM, to run code within CorDapps: decentralized applications that extend the global Corda database with new capabilities beyond the finance industry. Such apps define new data types, new internode protocol flows and the smart contracts (flows) that determine allowed changes. Thus, they, like Ethereum, are able to process financial contracts which Bitcoin is inherently incapable of doing, even though it has been attempted. 

In contrast to Ethereum, Brown notes:
“…The term ‘contract’ in Ethereum refers to an instantiation of a program that is replicated and maintained by every participating node. This instantiation is very much like an object in a Object Oriented program, it can receive and send messages, update local storage and so on. In contrast our implementation of the smart contract in code refers to a set of functions, only one of which is a part of keeping the system synchronized (the verify function). That function is pure and stateless (i.e., it may not interact with any other part of the system whilst executing). As contracts do not have any kind of mutable storage, there is no notion of a “message”. This model means it is possible to analyze a Corda transaction statically and not only determine whether it can be processed in parallel with other transactions but know what data must be available on the processing node, enabling both higher throughput and finer- grained data privacy.”
 
In the evolution of the technology R3 was not the first player to the game. However, they claim to offer the ability to ensure that information silos do not occur as its competitors–Enterprise Ethereum and Quorum (utilizing the Ethereum platform) built by J.P Morgan and Hyperledger’s Fabric platform–will experience. These products’ networks only offer a standalone network that is incompatible with all others, unlike Corda’s Network notary pool feature that allows a flow between any given network.  

## The Road Ahead:

Currently, Corda offers the Corda Enterprise software, according to their publication in 2019; it is compatible with the open-source corda Platform to manage the requirements around quality of service and the network infrastructure in an enterprise, fine-tuning performance and reducing operational costs for complex environments as their business model. Furthermore, this year, they released Token SDK, a project run by the Digital Asset Working Group (DAWG)  -  a standard interface to tokenize assets and re-imagine business transaction with Corda. Acting as an intermediary for regulated institutions to utilize smart contracts for the tokenization of securities. They provide a standard library and back-end assistance to issue, list, exchange and settle digital assets on the Corda platform. 
 
Corda continues to do mass amounts of research through it’s working groups and library facilities. They show great potential in revolutionizing the processes upon which they execute a legally enforceable financial contract on a trusted network. Futhermore, within trade-finance, insurance, healthcare, and digital assets for all of which the R3 team and members are currently developing use cases and Cordapps. As mentioned in the beginning of this study, Corda truly has many options to monetize under varying models. 

Corda has shown an exponential amount of growth as they continue to meet stakeholder and shareholder expectations. The success of Corda will depend greatly on the market peer participants, the evolution of regulation and its ability to meet market demands. However, as Brown alluded to above, if companies build different solutions on competing platforms, they could be creating more problems than they are solving. It would be better that platforms find a way to increase interoperability between network flow and reach, so each company can utilize the specific attributes each software offers that best matches the application requirements. Thus it is recommended that R3 keep to the claim that they will offer such interoperability, and not create more complex and costly systems. If they are able to offer true interoperability and consensus between distrusting parties, they are poised to grow right alongside the evolution. 

# References
https://www.corda.net/content/corda-platform-whitepaper.pdf
https://www.corda.net/content/corda-technical-whitepaper.pdf
ww.r3.com/wp-content/uploads/2018/07/
US_10_CryptoBLK_CS_JULY5_final_v3.pdf
https://www.mckinsey.com/industries/financial-services/our-insights/banking-matters/scanning-the-fintech-landscape
The Future of FinTech and Banking, Accenture](https://www.accenture.com/us-en/insight-future-fintech-banking)
[Scanning the FinTech Landscape: 10 Disruptive Models, McKinsey & Company](https://www.mckinsey.com/industries/financial-services/our-insights/banking-matters/scanning-the-fintech-landscape)
https://www.forbes.com/sites/michaeldelcastillo/2019/04/16/blockchain-50-billion-dollar-babies/#55399acc57cc
https://www.r3.com/wp-content/uploads/2019/04/Spunt_CS_R32018.pdf
https://www.r3.com/wp-content/uploads/2019/04/Synechron_CS_R32018.pdf
https://www.r3.com/wp-content/uploads/2019/04/CryptoBLK_CS_Jan2019.pdf
https://aws.amazon.com/partners/apn-journal/all/tradewind/
https://aws.amazon.com/partners/apn-journal/all/guildone/
https://www.r3.com/wp-content/uploads/2019/04/Gemalto-Case-Study-Sept-2018.pdf
https://www.r3.com/blog/when-is-blockchain-not-a-blockchain/
https://101blockchains.com/corda-blockchain/
https://www.r3.com/press-media/r3-doubles-down-on-london-as-post-brexit-technology-hub/
https://www.owler.com/company/r3
https://www.ledgerinsights.com/enterprise-blockchain-technology-war-r3/
https://www.hyperledger.org/blog/2019/08/29/announcing-hyperledger-besu
https://talkingtech.cliffordchance.com/content/micro-cctech/en/emerging-technologies/blockchain---distributed-ledger-technology/innovating-in-sukuk-capital-markets/_jcr_content/text/parsysthumb/download/file.res/Sukuk%20Capital%20Markets.pdf
https://www.r3.com/wp-content/uploads/2019/07/DigitAssetWorkingGroupReport.June2019.pdf
https://www.r3.com/wp-content/uploads/2019/08/R3.2019.MidYear.InsuranceMarket.Report.pdf
https://www.r3.com/wp-content/uploads/2019/06/DigitalAssets.Transforming.CapitalMarkets.R3.May-2019-copy.pdf
Clack, Bakshi, Braine. Smart Contract Templates: foundations, design land- scape and research directions. http://arxiv.org/abs/1608.00771, 2016. 
https://blockgeeks.com/guides/what-is-ethereum/. 
https://themerkle.com/smart-contracts-ethereum-vs-lisk-vs-bitcoin/"
https://www.ethereum.org 
https://www.finra.org/sites/default/files/Blockchain-R3-Comment.pdf
https://medium.com/swlh/silicon-valley-spotlight-r3-corda-2b9ced92a646
https://www.capgemini.com/es-es/wp-content/uploads/sites/16/2019/06/World-FinTech-Report-WFTR-2019_Web.pdf
Wright, Aaron and De Filippi, Primavera, Decentralized Blockchain Technology and the Rise of
Lex Cryptographia (March 10, 2015). Available at SSRN: https://ssrn.com/abstract=2580664
Nakamoto, S., 2008. Bitcoin: A peer-to-peer electronic cash system.
Peters, G.W. & Panayi, E., 2015. Understanding Modern Banking Ledgers through Blockchain
Technologies: Future of Transaction Processing and Smart Contracts on the Internet of Money.
