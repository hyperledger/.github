## ![Hyperledger Fabric Logo](https://github.com/hyperledger/.github/raw/main/Hyperledger_Fabric.svg)

# Hyperledger Fabric

*Hyperledger Fabric is part of [LF Decentralized Trust](https://www.lfdecentralizedtrust.org), which expanded from Hyperledger Foundation into the Linux Foundation's flagship organization for decentralized trust technologies.*

LF Decentralized Trust brings together the full Hyperledger ecosystem, Trust Over IP, Hiero, and a growing landscape of ledger, identity, interoperability, cryptographic, privacy, smart contract, and integration projects.

The Hyperledger Fabric name continues as an important project brand within LF Decentralized Trust. Hyperledger Fabric is an enterprise-grade permissioned distributed ledger framework for developing solutions and applications. Its modular and versatile design satisfies a broad range of industry use cases, offering a unique approach to consensus that enables performance at scale while preserving privacy.

This GitHub organization preserves the Hyperledger namespace and hosts the repositories for Hyperledger Fabric's core platform, SDKs, chaincode libraries, tooling, samples, and documentation, while the current foundation identity, governance, and broader project landscape are represented by LF Decentralized Trust.

## Governance

The governance repository is the home of LF Decentralized Trust TAC processes, policies, programs, and meeting minutes. These materials can also be viewed at:

https://lf-decentralized-trust.github.io/governance/

## Landscape

The LF Decentralized Trust Landscape provides an overview of projects, technologies, members, and ecosystem participants across the broader decentralized trust community, including Hyperledger Fabric. It can be viewed at:

https://landscape.lfdecentralizedtrust.org/


---

## Table of Contents

- [About This Organization](#about-this-organization)
- [Hyperledger Fabric Overview](#hyperledger-fabric-overview)
- [How to Participate](#how-to-participate)
- [Resources](#resources)
- [Repositories](#repositories)
- [Licensing](#licensing)

---

## About This Organization

This is the GitHub organization for **Hyperledger Fabric**. It is designed to serve as an entry point to the project and a guide to all its repositories and resources.

Hyperledger Fabric is a Graduated project under the Hyperledger umbrella. It provides a modular architecture with high levels of confidentiality, resiliency, flexibility, and scalability. Hyperledger Fabric allows for pluggable implementations of various components, accommodating the complexities of different economic ecosystems.

Hyperledger Fabric provides periodic releases with new features and improvements. Certain releases are designated as Long-Term Support (LTS), ensuring that important fixes are backported during overlap periods.

[↑ Back to top](#hyperledger-fabric)

---

## Hyperledger Fabric Overview

Hyperledger Fabric is an enterprise-grade permissioned distributed ledger framework. It is designed for use in developing solutions and applications across a broad range of industry use cases.

Key characteristics include:

- **Modular architecture** — Pluggable consensus, membership services, ledger storage, and chaincode execution.
- **Permissioned network** — All participants have known identities, enabling regulatory and compliance use cases.
- **Confidential transactions** — Channels and private data collections enable data isolation between participants.
- **Smart contracts (chaincode)** — Business logic written in Go, Java, or Node.js, executed in isolated containers.
- **Performance at scale** — Execute-order-validate architecture separates transaction execution from ordering for high throughput.
- **Enterprise readiness** — BFT and Raft consensus, certificate authority integration, and LTS release support.

[↑ Back to top](#hyperledger-fabric)

---
## How to Participate

1. Review the [Hyperledger Fabric GitHub organization](https://github.com/hyperledger).
2. Read the [Hyperledger Fabric documentation](https://hyperledger-fabric.readthedocs.io/).
3. Join community discussions on [LFDT Discord](https://discord.gg/hyperledger) — channel `#fabric`.
4. Attend community meetings — Fabric contributor meetings are open to all interested participants. See the [meeting calendar](https://zoom-lfx.platform.linuxfoundation.org/meetings/fabric?view=month).
5. Try the [fabric-samples](https://github.com/hyperledger/fabric-samples) to get hands-on experience with the platform.
6. Choose a repository that matches your area of interest from the tables above.
7. Open issues for bugs, documentation gaps, or feature ideas.
8. Submit pull requests with clear descriptions and links to related issues.

For larger changes, please open an issue first so the community can discuss the design before implementation.

[↑ Back to top](#hyperledger-fabric)

---

## Resources

- The [Hyperledger Fabric documentation](https://hyperledger-fabric.readthedocs.io/) is the official source for tutorials, concepts, operations guides, and API references.
- The [LF Decentralized Trust project page](https://www.lfdecentralizedtrust.org/projects/fabric) gives an overview of the project within the broader LFDT landscape.
- The [Fabric GitHub releases](https://github.com/hyperledger/fabric/releases) provide release notes, changelogs, and downloadable binaries.
- The [fabric-samples](https://github.com/hyperledger/fabric-samples) repository is the best starting point for hands-on experimentation.
- Watch community presentations through the [LFDT YouTube playlists](https://www.youtube.com/c/Hyperledger/playlists), which include Hyperledger Fabric content.
- Our [Code of Conduct](https://www.lfdecentralizedtrust.org/code-of-conduct) describes expected behavior across the LFDT community.
- For security related issues, please follow the LFDT security reporting process. Do not post security related content, issues, or discussions publicly in any repository.

[↑ Back to top](#hyperledger-fabric)

## Repositories

The repositories in this organization cover the Hyperledger Fabric core platform, client SDKs and APIs, chaincode libraries, tooling, samples, extended platform work (Fabric X), and documentation. Below is a guide to the key repositories.

### Core Platform

| Repository | Description |
|---|---|
| [fabric](https://github.com/hyperledger/fabric) | Core Hyperledger Fabric peer, orderer, and platform code. |
| [fabric-ca](https://github.com/hyperledger/fabric-ca) | Hyperledger Fabric Certificate Authority for identity management. |
| [fabric-config](https://github.com/hyperledger/fabric-config) | Go packages for channel configuration transactions. |
| [fabric-protos](https://github.com/hyperledger/fabric-protos) | Protocol Buffer definitions for Hyperledger Fabric. |
| [fabric-protos-go-apiv2](https://github.com/hyperledger/fabric-protos-go-apiv2) | Generated Go bindings for fabric-protos (API v2). |
| [fabric-protos-go](https://github.com/hyperledger/fabric-protos-go) | Generated Go bindings for fabric-protos (legacy). |
| [fabric-lib-go](https://github.com/hyperledger/fabric-lib-go) | Shared Go libraries used across Fabric components. |

### Client SDKs and APIs

| Repository | Description |
|---|---|
| [fabric-gateway](https://github.com/hyperledger/fabric-gateway) | Go, Node.js, and Java client API for Hyperledger Fabric v2.4+. |
| [fabric-admin-sdk](https://github.com/hyperledger/fabric-admin-sdk) | Hyperledger Fabric admin SDK for network management. |
| [fabric-sdk-py](https://github.com/hyperledger/fabric-sdk-py) | Hyperledger Fabric Python SDK. |

### Chaincode (Smart Contracts)

| Repository | Description |
|---|---|
| [fabric-chaincode-go](https://github.com/hyperledger/fabric-chaincode-go) | Go packages for writing Fabric chaincode. |
| [fabric-chaincode-java](https://github.com/hyperledger/fabric-chaincode-java) | Java contract and chaincode implementation. |
| [fabric-chaincode-node](https://github.com/hyperledger/fabric-chaincode-node) | Node.js smart contract implementation. |
| [fabric-contract-api-go](https://github.com/hyperledger/fabric-contract-api-go) | Go contract API packages for chaincode development. |
| [fabric-private-chaincode](https://github.com/hyperledger/fabric-private-chaincode) | Confidential chaincode execution using Intel SGX. |

### Fabric X (Extended Platform)

| Repository | Description |
|---|---|
| [fabric-x](https://github.com/hyperledger/fabric-x) | Fabric X core platform. |
| [fabric-x-orderer](https://github.com/hyperledger/fabric-x-orderer) | Fabric X ordering service. |
| [fabric-x-committer](https://github.com/hyperledger/fabric-x-committer) | Fabric X committer component. |
| [fabric-x-endorser](https://github.com/hyperledger/fabric-x-endorser) | Fabric X endorser component. |
| [fabric-x-evm](https://github.com/hyperledger/fabric-x-evm) | Fabric X EVM compatibility layer. |
| [fabric-x-sdk](https://github.com/hyperledger/fabric-x-sdk) | Fabric X client SDK. |
| [fabric-x-common](https://github.com/hyperledger/fabric-x-common) | Shared libraries for Fabric X components. |
| [fabric-x-samples](https://github.com/hyperledger/fabric-x-samples) | Sample applications for Fabric X. |
| [fabric-x-rfcs](https://github.com/hyperledger/fabric-x-rfcs) | RFCs and design proposals for Fabric X. |

### Samples, Testing, and Documentation

| Repository | Description |
|---|---|
| [fabric-samples](https://github.com/hyperledger/fabric-samples) | Sample applications and network configurations for getting started. |
| [fabric-test](https://github.com/hyperledger/fabric-test) | Test utilities for the core Hyperledger Fabric projects. |
| [fabric-docs-i18n](https://github.com/hyperledger/fabric-docs-i18n) | Internationalized Fabric documentation. |

### Organization Infrastructure

| Repository | Description |
|---|---|
| [governance](https://github.com/hyperledger/governance) | LF Decentralized Trust TAC governance materials. |
| [.github](https://github.com/hyperledger/.github) | Organization profile, templates, and shared configuration. |
| [hyperledger.github.io](https://github.com/hyperledger/hyperledger.github.io) | Hyperledger GitHub Pages site. |

[↑ Back to top](#hyperledger-fabric)


---

## Licensing

Hyperledger Fabric repositories are primarily licensed under the Apache License 2.0. Documentation repositories may use Creative Commons Attribution 4.0 International. Please check the license file in each repository before reuse.

[↑ Back to top](#hyperledger-fabric)

---

*This README is the umbrella index for Hyperledger Fabric. Source code, SDKs, chaincode libraries, samples, and documentation live in the individual repositories linked in the tables above.*
