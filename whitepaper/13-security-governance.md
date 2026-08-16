# 13. Security, Governance & Risk Management

Persistent cross-game Agents create a broader attack surface than ordinary static NFTs. MetaFishtank therefore treats security and permission design as part of the protocol, not as an afterthought.

## 13.1 Smart Contract Security

Target practices include:

- unit testing;
- invariant testing;
- fuzz testing;
- static analysis;
- gas and storage profiling;
- role and permission review;
- external audits before high-value production deployment;
- verified deployment addresses;
- incident-response procedures.

## 13.2 Administrative Security

Administrative control should use:

- multisig wallets;
- timelocks for high-impact changes;
- scoped roles;
- emergency pause where appropriate;
- explicit adapter revocation;
- public change logs;
- progressive minimization of privileged permissions.

## 13.3 Third-Party Game Risk

A third-party game should never receive unrestricted mutation access to an Agent.

MAP protects Agents through:

- namespaced writes;
- bounded updates;
- EIP-712 or equivalent signed authorization;
- nonces and replay protection;
- adapter registration;
- revocation;
- rate limits;
- value bounds;
- stronger validation for canonical trait updates.

Revoking a compromised game's permissions must not affect the user's ownership of the Agent.

## 13.4 AI Trust

AI-generated or AI-interpreted state should be made as reproducible and auditable as practical.

Controls can include:

- deterministic preprocessing;
- versioned trait compilers;
- signed inference payloads;
- model / ruleset identifiers;
- bounded outputs;
- challenge or review mechanisms;
- optional TEE attestations;
- optional cryptographic proofs when practical.

## 13.5 Economic Risk

The protocol avoids presenting incentives as guaranteed investment returns.

Risk controls include:

- capped emissions;
- seasonal budgets;
- no fixed APY promises;
- transparent unlock schedules;
- anti-Sybil systems;
- treasury accounting;
- compute-reserve accounting;
- governance timelocks;
- public campaign rules.

## 13.6 Governance Direction

Governance should mature alongside real usage.

Early phases may use a multisig plus transparent operating policy. Over time, selected parameters may transition to broader token or community governance once:

- contracts are battle-tested;
- participation is sufficiently distributed;
- governance attacks are understood;
- token concentration and voting design are appropriate.

Decentralization is treated as a security and coordination process, not a marketing deadline.
