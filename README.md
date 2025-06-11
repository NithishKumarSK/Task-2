| Blockchain Name            | Type       | Consensus Mechanism Used                 | Permission Model | Speed / Throughput   | Smart Contract Support  | Token Support        | Typical Use Case                   | Notable Technical Feature               |
| -------------------------- | ---------- | ---------------------------------------- | ---------------- | -------------------- | ----------------------- | -------------------- | ---------------------------------- | --------------------------------------- |
| Ethereum                   | Public     | Proof of Stake (PoS)                     | Open             | \~15–30 TPS          | Yes (Solidity, Vyper)   | Yes (Ether – Native) | Decentralized applications (dApps) | EVM, large developer ecosystem          |
| Hyperledger Fabric         | Private    | Pluggable (default: RAFT)                | Permissioned     | 1000+ TPS            | Yes (Go, Java, Node.js) | No native token      | Enterprise/internal systems        | Modular, private channels, pluggable    |
| R3 Corda (Consortium Mode) | Consortium | Notary-based (validating/non-validating) | Permissioned     | \~170 TPS (scalable) | Yes (Kotlin, Java)      | No native token      | Financial institutions, inter-bank | Peer-to-peer, contract validation logic |


Short Report

Ethereum is a public blockchain that utilizes Proof of Stake and supports smart contracts in Solidity. It is ideal for decentralized applications because it offers openness, token support, and a vast developer community, though it is limited in throughput (15–30 TPS).
Hyperledger Fabric is a private blockchain designed for enterprise use. It supports modular architecture and private channels, with a high throughput of over 1000 TPS. Its permissioned model and pluggable consensus make it well-suited for secure business processes.
R3 Corda, used in consortium mode, is tailored for financial institutions. It emphasizes privacy and uses a notary-based consensus mechanism. It supports smart contracts written in Kotlin or Java and enables direct peer-to-peer communication without broadcasting all transactions to the network.
Best Platform Recommendations:
Decentralized App: Ethereum – Open, tokenized, supports advanced smart contracts.
Supply Chain Network (Known Partners): Hyperledger Fabric – High performance, private, secure.
Inter-bank Financial Application: R3 Corda – Privacy-focused, legally enforceable contracts, financial-grade architecture.
