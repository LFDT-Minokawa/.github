# Minokawa

Welcome to **Minokawa**, a project of the [Linux Foundation Decentralized Trust](https://www.lfdecentralizedtrust.org) building open source developer tooling for zero-knowledge blockchains.

You can find more information on the [Minokawa project page](https://www.lfdecentralizedtrust.org/projects/minokawa).

<!-- TODO: Add a Minokawa banner image here -->
<!-- ![Minokawa Banner](link-to-banner-image) -->

## What is Minokawa?

Zero-knowledge blockchains let applications prove that a computation was performed correctly without revealing the data behind it. Building on them today usually means hand-writing circuits, wiring up proof generation, and managing the boundary between private off-chain data and public on-chain logic by hand.

Minokawa exists to make that work unnecessary. The project develops languages, compilers, runtimes, and supporting tooling so that developers can write privacy-preserving smart contracts as ordinary application logic and let the toolchain handle the cryptography underneath.

The project's goal is for this tooling to serve the zero-knowledge ecosystem broadly rather than any single chain.



## What Minokawa's Tooling Enables

With Minokawa's tools, developers can:

- Build smart contracts where data remains private unless intentionally disclosed
- Use zero-knowledge capabilities without writing circuits manually
- Compose public and private logic within a single contract
- Implement selective disclosure for compliance and privacy-sensitive workflows
- Build verifiable applications with stronger privacy guarantees and preserved user agency


## Repositories
| Repository | Description |
|---|---|
| [**compact**](https://github.com/LFDT-Minokawa/compact) | is the smart contract language developed by the Minokawa project. It compiles to zero-knowledge circuits and currently targets the **Midnight** blockchain; supporting further zero-knowledge blockchains is an explicit aspiration of the project. Repository contains the Compact language, compiler, runtime, documentation, examples, editor support, tests, and toolchain |
| [**governance**](https://github.com/LFDT-Minokawa/governance) | Governance materials and project configuration for Minokawa. |

## Resources

The following documents will help you understand Minokawa's vision, workflows, and community.

- The [Minokawa project page](https://www.lfdecentralizedtrust.org/projects/minokawa) gives an overview of the project, architecture, and use cases.
- The LFDT blog post [Compact smart contract language is now Minokawa](https://www.lfdecentralizedtrust.org/blog/compact-smart-contract-language-is-now-minokawa-newest-lf-decentralized-trust-project) explains the project's origin and transition to LFDT.
- The [Compact documentation](https://docs.midnight.network/compact) provides language and developer documentation.
- Watch Minokawa videos through the [LFDT Minokawa video page](https://www.lfdecentralizedtrust.org/projects/minokawa#videos) and the [LFDT YouTube channel](https://www.youtube.com/@lfdecentralizedtrust).
- Watch the Minokawa meetup recording: [Making Zero-Knowledge Smart Contract Development Accessible, Secure & Practical](https://www.youtube.com/watch?v=AT2eO_8yDz8).
- Our [Code of Conduct](https://www.lfdecentralizedtrust.org/code-of-conduct) describes expected behavior across the LFDT community.
- For security related issues, please follow the LFDT security reporting process. Do not post security related content, issues, or discussions publicly in any repository.

## How to contribute

Minokawa welcomes developers, researchers, cryptographers, organizations, and privacy advocates interested in zero-knowledge smart contracts and privacy-preserving applications.

Good ways to get started:

1. Review the [compact repository](https://github.com/LFDT-Minokawa/compact).
2. Join community discussions on [LFDT Discord](https://discord.lfdecentralizedtrust.org) Channel: #minokawa
3. Attend community meetings. Minokawa community calls are open to everyone. These meetings are a good place to ask questions, discuss roadmap priorities, and learn how to contribute.

| Meeting | Calendar Link |
|---|---|
| Minokawa Community Call | https://zoom-lfx.platform.linuxfoundation.org/meeting/92376999403?password=23e83ac5-4334-4da3-9e07-2afb5065fa28  |

Past meeting recordings and presentations can be accessed through:

- [LFX Individual Dashboard](https://openprofile.dev/)
- [LFDT Meeting Calendar](https://zoom-lfx.platform.linuxfoundation.org/meetings/lf-decentralized-trust)

For larger changes, please open an issue first so the community can discuss the design before implementation.

## Current Status

Minokawa is an **incubating** LFDT project. It has an established codebase and tooling through Compact, and the community is working to grow participation, improve documentation, expand examples, evolve the language, compiler, and runtime, and broaden the range of zero-knowledge blockchains the tooling can target.

## License

Minokawa repositories are licensed under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0).