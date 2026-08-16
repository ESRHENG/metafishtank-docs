# 3. Why BNB Chain?

MetaFishtank requires an execution environment that supports frequent asset-state interaction, low-friction onboarding, mature EVM tooling and a growing on-chain Agent ecosystem.

**BNB Smart Chain (BSC)** is the initial settlement and ownership layer for the protocol.

## 3.1 EVM Compatibility and Developer Reach

BSC is EVM-compatible, allowing MetaFishtank to use the existing Solidity ecosystem, widely adopted wallets, established contract tooling, auditing infrastructure, indexers and developer libraries.

For MetaFishtank, this matters because third-party game integration should not require developers to learn a chain-specific programming model. MAP contracts and adapters can be consumed using familiar EVM interfaces.

## 3.2 Fast Finality and Cost-Efficient Interaction

Agent-driven games generate many small state changes: minting, progression checkpoints, achievement commits, ownership transfers, game authorization, verification updates and marketplace activity.

MetaFishtank uses BSC for state that benefits from public ownership, settlement, authorization and verification while keeping real-time gameplay and AI inference off-chain where appropriate.

This separation is intentional: MetaFishtank does not attempt to put every game frame or every model inference on-chain.

## 3.3 Alignment With the On-Chain Agent Economy

MAP remains MetaFishtank's game-asset protocol, but compatible Agents may optionally expose adapters to broader Agent standards.

- **ERC-8004:** Relevant for portable Agent identity, discovery, reputation and validation registries.
- **BAP-578:** An emerging/draft Non-Fungible Agent application standard in the BNB Chain ecosystem. MetaFishtank treats it as a potential compatibility target rather than a hard dependency.
- **Agent Commerce Modules:** Future Agent-to-service or Agent-to-Agent payment flows can be evaluated when they create clear product value.

The goal is compatibility without surrendering MAP's core responsibility:

> **Portable game state and cross-game evolution.**

## 3.4 Optional Scaling Path

The initial protocol is designed for BSC. If specific gameplay or micro-interaction workloads later require a dedicated high-frequency execution surface, **opBNB** can be evaluated as an optional Layer 2 path.

The protocol avoids binding its identity to a single performance feature.

> **Portable Agent state first. Execution optimization second.**
