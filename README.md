<p align="center"><img src="assets/bashard-mark.png" width="112" alt="Bashard logo"></p>

# Bashard Developers

**Open-source tooling for verifiable object storage on BNB Smart Chain.**

We build the contracts, encoding libraries, storage infrastructure and
interfaces behind Bashard. Our focus is explicit protocol boundaries,
verifiable file commitments and practical developer tooling.

## Explore the project

| Repository | What you will find |
| --- | --- |
| [bashard-protocol](https://github.com/bashard-dev/bashard-protocol) | Solidity contracts, erasure coding, Merkle commitments and the TypeScript SDK |
| [bashard-node](https://github.com/bashard-dev/bashard-node) | Storage operators, cloud custody and the read-only indexer |
| [bashard-web](https://github.com/bashard-dev/bashard-web) | Landing website, storage App, Scan and protocol documentation |

## How Bashard works

Files are encoded into **20 shards**; **any 7 verified shards** reconstruct the
original bytes. BSC coordinates tapes, track commitments, committees and
stake. Nodes serve the bytes and produce storage certificates.

Encoding is not encryption. A single bootstrap operator is not independent
redundancy. Mainnet setup does not by itself establish production readiness.

## Current focus

Bootstrap validation, durable custody, reproducible developer tooling and
clear operational safeguards. See the repository readiness guides for the
distinction between deployed contracts and publicly available storage.

## Build with us

Start with an issue or a focused pull request. Read each repository's
contribution guide and security policy. Please do not include private keys,
access tokens or customer files in reports.

## Official links

- **Website:** https://bashard.com
- **Storage App:** https://app.bashard.com
- **Network explorer:** https://scan.bashard.com
- **Documentation:** https://bashard.com/docs
- **X:** https://x.com/Bashard_
- **Developer contact:** [support@bashard.com](mailto:support@bashard.com)

Apache-2.0 · BNB Smart Chain · TypeScript · Solidity

## Verifiable bootstrap activity

See the [integration validation report](docs/BOOTSTRAP_VALIDATION.md) for
public transaction receipts, file-integrity evidence and explicit limitations.
