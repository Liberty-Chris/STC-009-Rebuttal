# Rebuttal and Critical Analysis of the STC-009 Blockchain Analysis Report

**Prepared for:** Wyoming Stable Token Commission  
**Date:** February 1, 2025  
**Author:** Christopher Hockaday

---

## 1. Introduction
The STC-009 Blockchain Analysis Report, prepared for the Wyoming Stable Token Commission, aims to evaluate various blockchain networks for the deployment of the Wyoming Stable Token (WST). While the report attempts to provide a structured assessment, it suffers from multiple logical inconsistencies, technical inaccuracies, and notable omissions. This rebuttal highlights critical flaws in the report’s methodology, selection criteria, and conclusions, offering a more balanced perspective on the strengths and weaknesses of different blockchain ecosystems.

---

## 2. Inconsistent Selection Criteria
One of the most significant issues with the report is its lack of a clear and consistent methodology for including or excluding blockchains. The report states that some networks were omitted due to legal or technical concerns, with Tron specifically mentioned as being excluded for regulatory reasons. However, it does not apply this same level of scrutiny to other networks.

Several included blockchains, such as Solana, NEAR, and MATIC, have also faced regulatory scrutiny from the SEC. Despite this, they are still part of the analysis without any clear justification for their inclusion. If regulatory concerns were a primary consideration, all blockchains under SEC investigation should have been addressed with the same level of caution. The inconsistent application of selection criteria raises concerns about the objectivity and rigor of the evaluation process.

---

## 3. Failure to Address Network Uptime and Stability
A critical factor in selecting a blockchain for a state-backed stable token is reliability, yet the report fails to analyze network uptime and historical performance. Some of the blockchains under consideration, such as Solana and Ethereum, have suffered multiple outages and finality issues.

- **Solana** has experienced several complete network failures, with validators needing to manually restart the chain. This instability raises serious concerns about its suitability for hosting a state-backed digital asset.
- **Ethereum** has encountered finality issues that temporarily disrupted transaction processing.
- **Cardano**, in contrast, has never experienced a network outage, yet this key distinction is omitted entirely.

A comprehensive evaluation should prioritize stability as a core requirement. The omission of network uptime as a selection criterion is a major oversight.

---

## 4. Misleading Metrics on Adoption
The report relies heavily on Daily Active Addresses (DAA) as a measure of adoption, but this metric is flawed and can be misleading. DAA does not necessarily reflect genuine user engagement, as it can be inflated through Sybil attacks, spam transactions, or bot activity.

A more accurate assessment of adoption should include:
- Transaction value distribution
- Unique wallet growth over time
- Active stake participation by independent entities

By failing to incorporate these more reliable indicators, the report presents an incomplete, tailored, and distorted view of blockchain adoption.

---

## 5. Technical Inaccuracies in Finality and Performance Metrics

Several technical inaccuracies in the report call into question its credibility. One of the most significant errors is the claim that Cardano’s time to finality is one day. This is incorrect.

Cardano follows a **probabilistic finality model**, meaning that transactions are considered **increasingly irreversible** as more blocks are added over time. Specifically, a transaction on Cardano is considered **final** and **immutable** once **three blocks** have been appended to the block containing the transaction. This ensures a high degree of certainty regarding the finality of the transaction.

While finality is not guaranteed immediately after a transaction is submitted, the probability of a reversal significantly decreases after three additional blocks have been added. This makes Cardano’s finality model both **secure** and **efficient**, with the finality becoming increasingly reliable over time.

**probabilistic finality** on Cardano, with its quick convergence over time and improvements in throughput and decentralization, provides a **highly reliable and secure finality** model.

## References

1. Cexplorer. (n.d.). *Understanding Transaction Finality on Cardano*. Retrieved from [https://cexplorer.io/article/understanding-transaction-finality](https://cexplorer.io/article/understanding-transaction-finality)

---

## 6. Decentralization Metrics and Their Implications
The report provides raw decentralization metrics such as node counts and Nakamoto coefficients but does not properly analyze their real-world implications.

- **Ethereum** is listed as having over eight million nodes, but this figure likely includes all types of network participants, including light clients and validators. The real concern with Ethereum’s decentralization is the high concentration of staking power among a small number of entities, such as Lido, which controls a significant portion of the network’s stake.
- **Solana’s** Nakamoto coefficient of twenty-two is cited as a positive, but the report does not acknowledge that Solana’s validator network has been dominated by a small number of well-funded participants, leading to network instability.
- **Cardano**, with thousands of independently operated stake pools, ensures one of the highest levels of decentralization. This strength is, once again, omitted entirely.

Decentralization is not just a matter of node count; it is about control distribution and resilience to centralization risks. A more nuanced approach is required to assess blockchain decentralization effectively.

---

## 7. Contradictions in Strategic Recommendations
The report suggests that the Wyoming Stable Token should adopt a multi-chain approach while also acknowledging the commission’s limited budget and resources. Deploying across multiple blockchains increases technical complexity, security risks, and liquidity fragmentation.

If resource constraints are a major consideration, a multi-chain strategy should have been critically analyzed rather than simply assumed to be beneficial. The lack of cost-benefit analysis on this strategy is a significant gap in the report’s recommendations.

---

## 8. Missing Security Considerations
Security is a fundamental requirement for any blockchain handling stable tokens, yet the report does not meaningfully address the history of smart contract exploits, bridge vulnerabilities, or security risks across different networks.

- **Ethereum** and **Solana** have been at the center of some of the largest DeFi and bridge-related exploits that have amounted to billions of dollars in losses for end users, yet these risks are not assessed.
- **Cardano’s** eUTXO model provides inherent security benefits by minimizing smart contract attack surfaces, yet this is not highlighted as an advantage.

A proper security assessment should be a core part of any blockchain selection process, and its omission here is a major failing.

---

## 9. Conclusion
The STC-009 Blockchain Analysis Report presents itself as a thorough review but falls short in multiple key areas. It applies inconsistent selection criteria, fails to assess network stability, relies on misleading adoption metrics, contains technical inaccuracies, and does not properly analyze decentralization or security risks. A well-informed evaluation should prioritize reliability, decentralization, and security above simplistic metrics like daily active addresses or market capitalization.

For the Wyoming Stable Token to succeed, it is critical that decision-making is based on rigorous, objective analysis rather than incomplete or misleading data. The failure to account for these fundamental considerations not only jeopardizes the effectiveness of the Wyoming Stable Token but also exposes the state and the commission to reputational, financial, and legal risks that could have long-lasting consequences.
