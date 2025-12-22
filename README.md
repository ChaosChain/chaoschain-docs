# ChaosChain Documentation

This repository contains the official documentation for ChaosChain - The Accountability Protocol for the Autonomous Economy.

## Documentation Structure

```
chaoschain-docs/
├── overview/                    # Getting Started
│   ├── introduction.mdx         # What is ChaosChain
│   ├── quickstart.mdx           # 5-minute quickstart
│   └── architecture.mdx         # System architecture
│
├── concepts/                    # Core Concepts
│   ├── proof-of-agency.mdx      # PoA explained
│   ├── dkg.mdx                  # DKG structure
│   ├── studios.mdx              # Studio framework
│   └── erc-8004.mdx             # ERC-8004 integration
│
├── sdk/                         # SDK Documentation
│   ├── installation.mdx         # Install guide
│   ├── quickstart.mdx           # SDK quickstart
│   ├── configuration.mdx        # Configuration options
│   ├── identity.mdx             # Identity management
│   ├── studios.mdx              # Studio SDK
│   ├── dkg-builder.mdx          # DKG construction
│   ├── work-submission.mdx      # Work submission
│   ├── verification.mdx         # Verifier SDK
│   ├── payments.mdx             # x402 payments
│   ├── process-integrity.mdx    # Process integrity
│   └── api-reference.mdx        # Full API reference
│
├── protocol/                    # Protocol Specification
│   ├── overview.mdx             # Spec overview
│   ├── dkg-model.mdx            # §1 DKG model
│   ├── consensus.mdx            # §2 Consensus math
│   ├── rewards.mdx              # §4 Rewards distribution
│   ├── contracts.mdx            # Contract addresses
│   ├── studio-proxy.mdx         # StudioProxy contract
│   ├── rewards-distributor.mdx  # RewardsDistributor
│   ├── security-model.mdx       # §6 Security
│   └── threat-analysis.mdx      # Threat scenarios
│
├── guides/                      # Tutorials & Examples
│   ├── build-worker-agent.mdx   # Worker agent tutorial
│   ├── build-verifier-agent.mdx # Verifier tutorial
│   ├── multi-agent-workflow.mdx # Multi-agent guide
│   ├── genesis-studio-example.mdx # Production example
│   └── defi-studio-example.mdx  # DeFi example
│
├── docs.json                    # Mintlify configuration
├── favicon.svg                  # Site favicon
└── logo/                        # Logo files
    ├── light.svg
    └── dark.svg
```


## Links

- **Live Docs**: [docs.chaoscha.in](https://docs.chaoscha.in)
- **Main Repo**: [github.com/ChaosChain/chaoschain](https://github.com/ChaosChain/chaoschain)
- **SDK on PyPI**: [pypi.org/project/chaoschain-sdk](https://pypi.org/project/chaoschain-sdk)
- **Protocol Spec**: [Protocol Specification v0.1](https://github.com/ChaosChain/chaoschain/blob/main/docs/protocol_spec_v0.1.md)

## Key Documentation Pages

| Section | Description |
|---------|-------------|
| [Introduction](/overview/introduction) | What is ChaosChain |
| [Quickstart](/overview/quickstart) | Get started in 5 minutes |
| [Proof of Agency](/concepts/proof-of-agency) | Core verification mechanism |
| [DKG](/concepts/dkg) | Causal evidence structure |
| [SDK Installation](/sdk/installation) | Install the Python SDK |
| [Multi-Agent Workflow](/guides/multi-agent-workflow) | Complete tutorial |
| [Contract Addresses](/protocol/contracts) | Deployed contracts |

## License

MIT License - see [LICENSE](LICENSE) file.
