OTC Trading: Custodians and counterparties can settle massive trades securely without tipping off the broader market.
Read the full breakdown by Miden: https://miden.xyz/blog/practical-privacy
By leveraging ZK proofs, we can ensure application-level compliance and protocol-level evasion-resistance, protecting honest users while deterring bad actors.
The future of blockchain isn't total transparency (surveillance) or absolute anonymity (compliance nightmare)—it’s Practical Privacy.
aiming to protect the vast majority of honest users while providing better evasion-resistance than the traditional financial system
They are building a decentralized protocol that phases in privacy incrementally
The "Practical Privacy" Philosophy: Miden rejects the extremes of total transparency and total anonymity.
while massive transfers or funds originating from sanctioned addresses face restrictions, delays, or required proofs.
For example, small transactions remain fully private (like physical cash),
To deter illicit finance, the base protocol can impose conditional privacy based on "transaction risk
Evasion-Resistance (Protocol Level)
ZK-Enforced Compliance (Application Level)
Blockchains are global and shouldn't enforce one country's laws at the base layer
Instead, Zero-Knowledge proofs allow individual applications and assets to enforce specific jurisdictional rules without ever collecting or revealing users' underlying personal data.
Blockchains are global and shouldn't enforce one country's laws at the base layer.
While privacy is essential for honest users, unconditional privacy shields criminals and makes it impossible for legitimate businesses to comply with localized regulations (like AML/KYC or sanctions).
The Dilemma of Absolute Privacy
this total transparency risks becoming a massive surveillance apparatus that can be exploited by malicious actors.
The Transparency Problem: "Pseudo-anonymous" blockchains act as permanent public ledgers
Ultimately, Miden aims to emulate the privacy model of physical cash: full privacy for everyday users and added friction for high-risk or massive transactions.
By utilizing Zero-Knowledge (ZK) proofs, blockchains can enforce regulatory compliance at the application level (allowing businesses to meet jurisdictional laws without exposing user data) while maintaining "evasion-resistance" at the protocol level (deterring bad actors by making privacy conditional based on transaction risk)
To solve this, Miden proposes a middle-ground approach called "practical privacy.
absolute privacy is also problematic because it complicates regulatory compliance for businesses and attracts illicit activities.
The article argues that the current state of public blockchains—where all transactions are completely transparent and traceable—creates severe surveillance risks that will hinder long-term adoption. Conversely
he goal is simply to build a system that is better than the traditional financial system (where an estimated 5% of global GDP is currently laundered), protecting the privacy of the masses while severely bottlenecking large-scale illicit finance.
Any system that provides true privacy for honest users will inevitably provide some cover for bad actors. However, perfection isn't the goal
Miden acknowledges that 100% evasion-resistance is impossible.
A major hurdle the article points out is the "Sybil problem."
If large transactions are restricted, a criminal could just split a $100 million transfer into 100,000 smaller $1,000 transactions to evade detection.
To solve this, the blockchain industry still needs to develop a robust, permissionless, decentralized identity system to prevent users from spinning up thousands of fake accounts.
Imposing Friction on Massive Transfers: For exceptionally large or high-risk transfers, the protocol could enforce built-in delays, require a ZK-based "proof of funds"
(to prove the money didn't just come from a recent smart contract hack), or require the transaction to be encrypted in a way that allows a decentralized group of validators to decrypt it if absolutely necessary (threshold-based viewing keys).
Emulating Physical Cash (Amount-Based Conditions): Moving $1,000 should be easy and completely private, much like handing someone cash.
However, moving $100 million privately should require significant effort.
Blocking Known Bad Actors: The protocol could simply refuse to accept deposits that originate from known, sanctioned addresses.
If the funds aren't from a sanctioned source, they enter the privacy pool and can transact freely.
The article outlines several technical approaches a protocol could take to enforce this:
How Evasion-Resistance Could Be Implemented
High-Risk Transactions: Transactions that display characteristics common to illicit finance are subjected to additional constraints or friction.
Low-Risk Transactions: Ordinary, everyday transactions are granted absolute privacy.
Instead of treating every transaction exactly the same, the protocol evaluates the "risk" of a transaction to determine its level of privacy:
In the context of Miden's "practical privacy," evasion-resistance refers to built-in, base-layer mechanisms designed to make it as difficult as possible for bad actors to use the network for illicit activities (like money laundering or hacking), without destroying privacy for everyday users.
Here is a deeper dive into Evasion-Resistance at the Protocol Level, based on the article's breakdown:
ZK-compliance allows businesses to follow the law perfectly while remaining completely blind to their users' actual personal data.
In traditional finance, users must hand over sensitive personal data to third parties, creating massive "honeypots" of data that inevitably attract identity thieves and state-level hackers.
The article highlights that ZK-enforced compliance is vastly superior to the traditional financial system's "audit-based compliance.
If the base protocol isn't enforcing compliance, what is its job? According to the article, the protocol’s responsibility is to provide developers with highly flexible programmable privacy tools. The base layer must be powerful enough so that a developer can build a private stablecoin where nobody knows who owns what, but the issuer still retains the programmable ability to freeze malicious accounts, impose daily transfer limits, or force compliance checks.
A U.S. business accepting crypto payments could require ZK-based AML/KYC proofs from its partners before a smart contract executes, while a business in another region might not require those checks.
Circle could enforce U.S.-specific regulations for USDC, requiring anyone who holds it to pass specific ZK-checks. Meanwhile, a different stablecoin issuer in Dubai or South Korea could enforce a completely different set of ZK-checks tailored to their local laws.
Because laws are local, compliance must be enforced by the specific applications or assets operating within those jurisdictions.
A user can prove they meet specific income or accreditation requirements without revealing their bank statements.
