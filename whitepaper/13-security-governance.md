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
- third-party audit of core contracts completed before launch, with the report published;
- verified deployment addresses;
- incident-response procedures.

## 13.2 Administrative Security

Administrative control uses:

- a 3-of-5 multisig with a public address;
- a 48-hour timelock for high-impact changes;
- scoped roles;
- explicit adapter revocation;
- public change logs;
- progressive minimization of privileged permissions.

Pause boundaries:

- the $MFT token contract has **no trading pause switch**, no blacklist and no wallet-specific tax rates;
- MAP game adapters can, under defined permissions, pause or revoke write access for an individual game without affecting Agent ownership or $MFT trading.

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
- public campaign rules;
- one daily-task allowance per identity per day;
- independent identity review before airdrops and rewards;
- linked accounts do not count toward contribution.

## 13.6 On-Chain Transparency

- **On-chain dashboard:** return-reserve coverage (at least 100%), reward pools, treasury, buybacks and burns, and ecosystem emission;
- **key rules in contracts:** transaction tax can only decrease, the return reserve can only be used for returns, and ecosystem emission cannot exceed the annual cap;
- **parameter ranges:** adjustable parameters can only move within published ranges, behind a timelock;
- **public vesting:** team and institutional allocations use public vesting contracts;
- **open data:** real test-season data is published and used to calibrate the official model.

## 13.7 Governance Direction

Governance should mature alongside real usage.

Early phases may use a multisig plus transparent operating policy. Over time, selected parameters may transition to broader token or community governance once:

- contracts are battle-tested;
- participation is sufficiently distributed;
- governance attacks are understood;
- token concentration and voting design are appropriate.

Decentralization is treated as a security and coordination process, not a marketing deadline.
