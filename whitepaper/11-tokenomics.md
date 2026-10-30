# 11. $MFT Tokenomics

$MFT is the utility and coordination token shared by every game on the MetaFishtank platform. Official fish raising, platform spending, staking and partner-game settlement all use $MFT. It is not a guaranteed-yield instrument.

## 11.1 Supply

**Fixed Supply: 1,000,000,000 $MFT** — fully minted at contract deployment, with no further minting.

## 11.2 Allocation

| Category                          | Share |      Amount | Use and release |
| --------------------------------- | ----: | ----------: | --------------- |
| Ecosystem Rewards                 |   60% | 600,000,000 | Game mining (official fish raising), staking mining, partner games and tournaments. Released over 8 years, front-loaded, with an annual cap; the yearly schedule will be published before TGE. |
| Investors · Community Sale        |   10% | 100,000,000 | Terms are published on the official sale page and are not part of this whitepaper. |
| Investors · Institutional Reserve |    5% |  50,000,000 | 12-month lock, then 24-month linear release. |
| Team & Advisors                   |   10% | 100,000,000 | Fully locked for the first 24 months after TGE, then linear release in months 25–72 through a public vesting contract. |
| Testing & Community               |    5% |  50,000,000 | 10 million for test-season game airdrops (see 7.6); the rest for community and partner campaigns. |
| Initial Liquidity                 |    5% |  50,000,000 | Official trading pool; LP locked for 12 months and re-locked on expiry, managed by multisig. |
| Strategic Reserve                 |    5% |  50,000,000 | No automatic release; each use is announced in advance and approved by multisig. |
| **Total**                         |  100% | 1,000,000,000 | Fully minted at deployment; no inflation. |

## 11.3 Utility

- fish raising in official seasons (game mining);
- platform spending: passes, cosmetics, renaming, creator marketplace, tournaments;
- staking and revenue sharing;
- partner-game settlement and ecosystem incentives;
- Anima compute / API credits;
- developer access tiers;
- future governance.

$MFT does not represent a promise of fixed yield, token price or guaranteed appreciation.

## 11.4 Official Fish Raising (Game Mining)

Starting in official Season S1, players commit $MFT to raise fish they have drawn themselves. There are no free fish in the official version.

- **Return period:** for the first 45 days, “commitment ÷ 45” is returned each day and credited the same day;
- **Reward period:** the following 60 days pay variable rewards. The S1 reference is about 40% of the commitment, capped at 100% per fish; actual rewards vary with participation and weight and are not guaranteed;
- **Daily completion:** output is produced only on days the required actions are completed; missed days are deferred, not forfeited.

Each commitment is split as follows: **15% burned, 5% to the staking reward pool, 80% to the return reserve**. The ecosystem pool tops up the remaining 20%, so every fish's 45-day return is 100% funded in advance. The return reserve can only be used for returns.

Scale and fairness:

- at most 8 fish per tank; slot n accepts up to n × 1,000 USDT worth of $MFT;
- the ecosystem pool's annual quota is first come, first served, with a daily cap spread evenly across the year;
- rewards are weight-based and variable so that large holders cannot lock up the quota.

Returns and rewards are counted in $MFT, not in U.S. dollar value.

## 11.5 Staking

- Three terms: 30, 90 and 365 days; longer locks carry higher weight;
- reward sources: 50% of transaction tax, the 25% of service revenue used for buybacks, 5% of fish commitments, 50% of fish transfer fees, early-exit penalties, 70% of realized gains from the tokenized-stock reserve, and the ecosystem pool's staking-mining quota;
- rewards may be claimed in $MFT, USDT or tokenized stocks, depending on what is supported at the time;
- early withdrawal forfeits the current period's rewards and deducts a principal penalty; penalties go to remaining stakers;
- annualized rewards are capped, with any excess held in a smoothing reserve;
- no fixed APR is displayed or promised.

## 11.6 Service Revenue

Platform service revenue (R) comes from passes, cosmetics, renaming, the creator marketplace, tournaments and similar features; some of these burn $MFT directly. R is routed as follows:

- **25% — buy back and burn $MFT**
- **25% — buy back $MFT for stakers**
- **40% — platform operations**
- **10% — service assurance** (AI inference, storage, verification, audits, monitoring, security)

Any change to these ratios will be announced in advance.

## 11.7 Transaction Tax

$MFT trades carry a transaction tax: 50% to the treasury and 50% to stakers. The rate starts higher, steps down over time and eventually reaches zero; it can only decrease. The exact schedule will be published before TGE. The token contract has no blacklist and does not apply different rates to different wallets.

## 11.8 Treasury and Tokenized-Stock Reserve

The treasury is funded by part of the funds raised and half of the transaction tax. Its priorities are market stability and deeper liquidity, and every use is announced in advance.

Part of the idle reserve may be held in **tokenized shares of leading U.S. stocks such as NVIDIA, Apple and Tesla**: 70% of realized gains go to stakers; losses are absorbed by the treasury and do not affect user principal; first-year exposure is capped at 30% of the idle reserve.

## 11.9 Partner Games and Developer Incentives

- Partner pool = 10% of the ecosystem pool's quota each season;
- eligibility: at least 100 unique paying users in the season and 7-day retention of at least 20%;
- default split for co-operated orders: the partner receives 80% of distributable service fees within the co-operation scope, the platform 20%;
- incentive weights consider unique active Agents, retention, ECS, protocol revenue, user satisfaction and integration quality.

## 11.10 Economic Flywheel

Players buy $MFT to raise fish → 15% burn / 80% return reserve / 5% staking pool → returns + variable rewards → re-commit to fish or move to staking → stakers share tax, buybacks and stock-reserve gains → treasury adds liquidity and funds campaigns → more players.

## 11.11 Economic Principles

1. **No guaranteed yield.** All rewards are variable and counted in $MFT.
2. **Returns funded first.** The return reserve is fully funded in advance and can only be used for returns.
3. **Transparent unlocks.** Ecosystem emission never exceeds the published schedule; team and institutional allocations use public vesting contracts.
4. **Reward real contribution.** Distribution follows valid activity and weight, backed by anti-Sybil controls.
5. **Utility before emission. Revenue before narrative.**
6. **Compute solvency matters.**
7. **Test-season FP is not a token.** Only the published airdrop rules convert test participation into $MFT.
