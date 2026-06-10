# IslamicChain™ (IC-01)

Official repository of the IslamicChain™ Sovereign Blockchain.

<img width="400" height="400" alt="Islamicchain Logo" src="https://github.com/user-attachments/assets/27d41fe8-51f3-4781-a1e2-866ffe45b7ab" />

---

## Overview

IslamicChain™ is a sovereign Layer-1 blockchain infrastructure designed to support digital assets, payments, treasury operations, settlement systems, and institutional financial applications through the native IC-01 Asset Standard.

Unlike networks that rely on ERC, BEP, TRC, wrapped assets, or third-party smart contract standards, IslamicChain operates on its own protocol architecture and asset framework, enabling native issuance, transfer, governance, and settlement directly at the blockchain layer.

The network is designed to serve governments, financial institutions, enterprises, and digital economies requiring secure, transparent, scalable, and policy-driven blockchain infrastructure.

---

## Key Features

- Sovereign Layer-1 Blockchain
- Native IC-01 Asset Standard
- Independent Economic Architecture
- Native Multi-Asset Ecosystem
- High-Speed Settlement Network
- Validator-Based Consensus
- On-Chain Governance
- Treasury and Reserve Infrastructure
- Enterprise & Institutional Ready
- Digital Identity Compatible
- Open Source Development

---

## Native Protocol Assets

IslamicChain operates with four protocol-level native assets:

| Asset | Purpose |
|---------|---------|
| **NFUEL** | Network gas, transaction fees, staking, validator incentives |
| **PMCN** | Sovereign reserve and settlement asset |
| **Sovereign USDT** | Stable-value settlement asset |
| **DCMA** | Treasury, ecosystem, and institutional utility asset |

All assets operate natively under the IC-01 standard and are not wrapped, bridged, or mirrored representations of assets from other blockchains.

---

## What is IC-01?

IC-01 is the native digital asset standard of IslamicChain.

The standard provides:

- Native asset issuance
- On-chain settlement
- Treasury integration
- Asset-level governance
- Institutional compliance capabilities
- Reserve asset management
- Financial infrastructure interoperability

IC-01 is an independent blockchain asset framework and is not derived from ERC-20, BEP-20, TRC-20, SPL, or similar token standards.

---

## Why IslamicChain?

| Feature | IslamicChain (IC-01) | ERC-20 | BEP-20 | TRC-20 |
|----------|----------|----------|----------|----------|
| Sovereign Layer-1 | ✅ | ❌ | ❌ | ❌ |
| Native Asset Framework | ✅ | ❌ | ❌ | ❌ |
| Multi-Native Assets | ✅ | ❌ | ❌ | ❌ |
| Built-In Settlement Architecture | ✅ | ❌ | ❌ | ❌ |
| Treasury-Oriented Design | ✅ | ❌ | ❌ | ❌ |
| Independent Economic Model | ✅ | ❌ | ❌ | ❌ |
| Dependency on Another Chain | ❌ | ✅ | ✅ | ✅ |

---

## Network Information

| Parameter | Value |
|------------|--------|
| Network Name | IslamicChain Mainnet |
| Chain ID | islamicchain-1 |
| Asset Standard | IC-01 |
| Consensus | Tendermint-Based Validator Network |
| Native Assets | NFUEL, PMCN, Sovereign USDT, DCMA |

---

## Repository Structure

```text
.
├── app/
├── cmd/
├── proto/
├── x/
├── docs/
├── scripts/
├── tests/
└── README.md
```

---

## Development

### Prerequisites

- Go 1.24+
- Git
- Linux / macOS / Windows

### Clone Repository

```bash
git clone https://github.com/islamicchain/ichain/ichain.git
cd ichain
```

### Build

```bash
make install
```

### Verify Installation

```bash
islamicchaind version
```

---

## Validator Operations

Start a node:

```bash
islamicchaind start
```

Check node status:

```bash
curl localhost:26657/status
```

---

## Documentation

Official documentation:

- https://islamicchain.org
- https://islamicchain.org/ichain/docs

---

## Contributing

We welcome contributions from developers, researchers, institutions, and ecosystem participants.

Please submit issues and pull requests through GitHub.

---

## Security

If you discover a security vulnerability, please report it responsibly through the official IslamicChain channels.

Do not publicly disclose vulnerabilities before coordinated remediation.

---

## License

Copyright © IslamicChain™

All rights reserved unless otherwise specified.

---

## Disclaimer

IslamicChain™, IC-01™, NFUEL™, PMCN™, Sovereign USDT™, and DCMA™ are ecosystem designations and protocol assets operating within the IslamicChain network.

This repository contains open-source software and protocol resources intended for development, research, and ecosystem participation.
