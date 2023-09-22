---
id: what-is-edge
title: What is Polygon Edge?
sidebar_label: What is Edge
description: "An introduction to Polygon Edge."
keywords:
  - docs
  - Polygon
  - edge
  - cdk
  - childchain
  - network
  - modular
---

## Introduction

Edge provides infrastructure for application-specific chains that operate with [PolyBFT consensus](/docs/cdk/edge/design/consensus/polybft/overview.md). They leverage a [native bridge](/docs/cdk/edge/design/bridge/overview.md) to connect with an associated rootchain, enabling them to inherit its security and capabilities. Additionally, Edge extend the block space available on the rootchain, providing scalability and interoperability for decentralized applications. With on-chain governance mechanisms, Edge empower communities to make decisions and upgrade the network in a transparent and compliant manner.

The following table offers a comprehensive overview on what Edge chains are through different perspectives.

| Edge chains are | Description |
|-----------|-------------|
| Application-specific blockchain networks designed for specific use cases. | Appchains are customizable blockchain networks that developers can tailor to meet specific enterprise or application use cases. With appchains, developers can create high-performance blockchain networks that are fast and low-cost. |
| The next phase of Polygon PoS and Ethereum scaling. | Edge chains empower projects and enterprises to create highly scalable blockchain networks that meet their specific block space requirements while inheriting the security and integrity of the Polygon PoS and Ethereum mainnet. |
| Modular and complex-minimized blockchain development. | Edge offer a modular framework that simplifies blockchain development, providing developers with the tools necessary to create customizable blockchain networks that are scalable, secure, and interoperable. Developers can use the Edge stack to create high-performance blockchain networks with advanced capabilities without worrying about complex integrations or intermediaries. |
| Customizable blockchain networks for reliable business logic. | A customizable virtual machine provides full Ethereum Virtual Machine (EVM) support out of the box, enabling developers to tailor the virtual machine to their specific needs and requirements. This feature includes customizing gas limits, adding new opcodes, and integrating with other technologies. |
| The most supported blockchain infrastructure in the web3 space. | The Edge ecosystem includes the most extensive suite of premium service providers, who offer various node and deployment infrastructure, indexers, explorers, oracles, and many other world-class tools necessary for building and deploying Edge chains and their associated applications. |
| Adaptive and compliant blockchain networks that thoroughly reflect their maintainers. | Edge features an on-chain governance mechanism that enables community-driven decision making and management of the blockchain. This mechanism supports hybrid governance models and allows for the design of either permissionless networks or permissioned networks with varying degrees of sovereignty based on user and maintainer needs, including the ability to allowlist validators and network admins. |
| Interoperable and multichain driven | A native bridging solution enables the seamless transfer of assets from various EVM-compatible blockchains back to the Polygon ecosystem. This bridging solution allows developers to customize bridge plugins to meet specific requirements, facilitating interoperability between blockchains and different layers. |

## Unstoppable Networks

Edge is pioneering unstoppable networks for the internet, where decentralized and secure applications can thrive.

<div align="center">
  <img src="/img/edge/supernets-together.excalidraw.png" alt="bridge" width="90%" height="40%" />
</div>

The diagram above demonstrates how Edge chains are interconnected with the Polygon PoS network, which benefits from the security properties of Ethereum. By leveraging blockchain technology, Edge provide a strong foundation for building decentralized and blockchain-based solutions that can withstand adversarial conditions, resist censorship, and scale to meet the increasing demand for processing power, data storage, and transaction throughput.

Edge employs a multi-faceted approach that leverages a combination of complementary scaling solutions to achieve maximum scalability. These solutions include layer-2 scaling techniques, parallelization, and, eventually, ZK technology.

By integrating these methods, Edge can efficiently accommodate the increasing demand for processing power, data storage, and transaction throughput as the number of users and applications on the network grows.

## Polygon Labs Program

### Implementation partners and service providers

To elaborate further, a Support program offers a range of service providers that can assist with various aspects of blockchain development, deployment, and maintenance. These include:

- **Node Providers**: These providers offer node infrastructure services that support the operation and maintenance of Edge-based networks. Node providers can help ensure network stability, security, and scalability by providing reliable and optimized node infrastructure.

- **RPC Providers**: These providers offer remote procedure call (RPC) services that allow developers to interact with Edge-based networks (childchains) and rootchain networks like the Mumbai PoS testnet and Polygon PoS. RPC providers can provide easy and reliable access to network data and functionality.

- **Smart Contract Monitoring**: This service enables real-time monitoring of smart contracts deployed on Edge-based networks. This can help detect and respond to potential issues, vulnerabilities, or attacks on the network.

- **Oracle Services**: These services offer real-time data feeds and external information that can be used to support smart contract execution on Edge-based networks. Oracles can help enable the development of more complex and advanced decentralized applications that rely on off-chain data and information.

- **Block Explorers**: These tools provide an interface for users to explore and visualize the blockchain's contents, including blocks, transactions, and other network data. Block explorers can help improve network transparency and accessibility and can be used by developers, users, and other stakeholders to gain insights into network activity and performance.

- **KYC Providers**: These providers offer Know Your Customer (KYC) and Anti-Money Laundering (AML) compliance services, which can help ensure that Edge-based networks comply with regulatory requirements and mitigate risk for network participants.

- **Fiat On-Ramps**: These services bridge fiat currencies and digital assets, enabling users to purchase and use digital assets on Edge-based networks. Fiat on-ramps can help increase accessibility and adoption of Edge-based networks.

### Easy deployments

Edge provides hassle-free deployment for blockchain networks with Terraform scripts "one-click" deployments, allowing developers to seamlessly set up a childchain.

### Cloud deployments

Edge supports cloud deployment options that enable developers and enterprises to easily and securely deploy a childchain to the cloud. With cloud deployment options, users can take advantage of the scalability and flexibility of cloud infrastructure, without having to worry about the complexities of managing their own infrastructure.

Edge supports deployment to various cloud platforms and allow users to choose the cloud platform that best suits their needs and preferences.

Edge cloud deployment options also come with a range of features and capabilities, such as auto-scaling, load balancing, and disaster recovery, that can help ensure network stability, security, and availability. These features can be especially important for enterprise-level deployments that require high levels of reliability and performance.

:::note Check out the local cloud deployment options

Get started with deploying a local private Edge chain on the cloud by checking out our cloud deployment guides
available [<ins>here</ins>](/cdk/edge/operate/deploy/index.md#cloud-deployments).

:::

## Why Edge?

### Regulatory Compliance and Network Sovereignty

Edge offers network sovereignty and regulatory compliance by allowing maintainers to select network administrators that meet local regulations. This enables global networks to tailor their configurations to maintain compliance with regional regulatory requirements.

### A New Approach to Infrastructure

Edge offers a cutting-edge approach to system infrastructure, backed by an ecosystem of premium service providers. This empowers organizations with control over network properties and access while applying permissioned or permissionless infrastructure models. The integration of blockchain technology and industry-leading partners provides additional guarantees in security and efficiency, transforming traditional infrastructure designs and models.

### Tokenization and Asset Management

Edge facilitates the creation and management of utility tokens, incentivizing network participation and promoting efficient transactions. The ability to mint additional tokens provides flexibility to adjust token supply and distribution dynamically, ensuring network incentives remain aligned with user needs.

### EVM Compatibility and Customization

Edge focusses on flexibility, adaptability, and EVM compatibility, streamlining the development process for developers. This design enables tailored blockchain solutions optimized for specific use cases while allowing the use of existing code and familiar programming languages. Developers can customize their networks with features such as default transaction fees and their own gas tokens, fine-tuning network performance and user experience.

### Robust Consensus

Edge utilizes the PolyBFT consensus mechanism for exceptional throughput, minimal latency, and immediate network finality. This positions them as a highly suitable platform for a variety of use cases.

### Cross-Chain Interoperability for Enhanced Efficiency

Edge supports cross-chain interoperability through their native bridge, enabling seamless asset transfers between different blockchains. This interconnected ecosystem allows developers to build on existing blockchain infrastructures and provides users with access to a broad range of applications and services. Cross-chain interoperability also facilitates increased collaboration and innovation between various blockchain networks.

### On-chain Governance

Edge enables on-chain governance, enabling participants to vote on changes to system parameters and promote transparency, accountability, and fairness. On-chain governance also allows for the creation of proto-jurisdictions to meet the needs of the community, defining rules and protocols for network operation, and promoting stability, security, innovation, and growth.
