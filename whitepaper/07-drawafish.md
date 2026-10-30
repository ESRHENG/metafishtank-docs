# 🎨 7. Drawafish — The Agent Bootstrap Application

Drawafish is the genesis application for MetaFishtank. Its purpose is larger than minting a collection: it bootstraps the first meaningful population of User-Generated Agents, the first behavioral dataset and the first recurring user loop.

## 7.1 Creation Flow

1. Connect an EVM-compatible wallet.
2. Draw a Fish using the creation canvas.
3. Anima validates the input.
4. Feature extraction produces a structured vector.
5. The Trait Compiler generates bounded Agent traits.
6. The user previews the Agent profile.
7. A signed Agent payload is generated.
8. MAP records ownership-critical state on BSC.
9. The Agent becomes available to compatible Tank applications.

## 7.2 Daily Interaction Loop

The original “attention” mechanic is retained as a product loop, but V3.3 removes guaranteed continuous mining and APY-style promises.

A typical daily loop may include:

- feed or nurture your own Agent;
- visit or interact with neighboring Agents;
- vote in aesthetic / uniqueness discovery;
- complete an Arena or gameplay task;
- participate in creator or seasonal challenges;
- maintain streaks or consistency goals.

Outputs can include:

- **Activity Score**
- **XP**
- **Seasonal Points**
- **Agent Evolution**
- **Collectibles / Badges**
- **Rankings**
- **Seasonal Rewards**

During test seasons these activities settle only in FP (Fish Points); see 7.6. Official-season $MFT rules are described in Section 11 and do not imply fixed yield.

## 🐟 7.3 Squad Activation

Instead of the legacy “4 Fish = double yield” mechanic, V3.3 uses a game-oriented threshold:

> **4 Agents → Squad Activation (four-fish synergy)**

- **1 Agent — Solo Tank:** core nurturing and social features.
- **2–3 Agents — Growing Tank:** expanded daily combinations and collection goals.
- **4 Agents — Squad Activation:** formation-based gameplay, team quests, Arena compositions, squad achievements and seasonal leaderboards.
- **5+ Agents — Advanced Squad:** deeper synergy and specialization. In test seasons up to 9 fish produce FP (slots 10–12 are display-only); in the official version each tank holds at most 8 fish.

Output increases step by step but stays capped, preserving the satisfaction of collection growth without turning the system into a fixed-return mining loop.

## 7.4 Beauty & The Beast Discovery

Creative assets should have social value beyond financial speculation.

Community discovery categories can include:

- Most Beautiful;
- Weirdest;
- Most Unique;
- Community Favorite;
- Most Evolved;
- Seasonal Theme Winner.

The purpose is to make creation itself a source of distribution.

## 7.5 Tank as Identity Surface

A user's Tank evolves into a Web3-native Agent profile.

It can display:

- owned Agents;
- featured Squad;
- creator history;
- achievements;
- favorite games;
- Agent evolution highlights;
- guild affiliation;
- seasonal trophies;
- cross-game badges.

The Tank therefore becomes both a social identity surface and a gateway into the broader ecosystem.

## 🧪 7.6 Test Seasons T1–T3 (Public Beta Season 2)

The test phase runs three seasons (T1, T2, T3). Each season has 42 days of play plus 7 days of review, 147 days in total. Test seasons produce **only FP (Fish Points)**. FP cannot be transferred, sold or purchased.

### Fish slots and daily tank FP output

| Slot       | How to obtain                              | Daily tank FP   |
| ---------- | ------------------------------------------ | --------------: |
| Fish 1     | Free on day one                            |             150 |
| Fish 2     | Free on the 2nd cumulative valid day       |             250 |
| Fish 3     | Free on the 3rd cumulative valid day       |             350 |
| Fish 4     | 3,000 FP; activates four-fish synergy      |             850 |
| Fish 5     | 4,500 FP                                   |             950 |
| Fish 6     | 6,000 FP                                   |           1,050 |
| Fish 7     | 8,000 FP                                   |           1,150 |
| Fish 8     | 10,500 FP                                  |           1,250 |
| Fish 9     | 13,500 FP                                  |           1,350 |
| Fish 10–12 | Display slots: 17,000 / 21,000 / 25,500 FP | No extra output |

### FP spending

- Nutrition renewal: 800 FP per fish every 40 days;
- decorations: 500 FP;
- auto-care: 300 FP per 24 hours; it does not replace the player's own daily activity.

### Valid days, tasks and invites

- A day counts as valid, and output is settled, only after the player personally completes care or patrol plus the basic mini-game;
- missed days are not backfilled;
- daily tasks give at most 50 FP;
- when an invited user completes 7 valid days, the inviter earns 50 FP, up to 10 invitees per season;
- popularity rankings award only badges and decorations, not FP or tokens.

FP balance, cumulative earnings and spending are recorded separately. Airdrop contribution is based on **cumulative valid FP earned** and is not reduced by spending.

### Game airdrop

- Budget: 10 million $MFT — T1 2 million, T2 3 million, T3 5 million;
- cap: 5,000 $MFT per person per season;
- eligibility: complete an original fish, at least 14 valid days in the season, and pass independent identity review. No subscription, payment or token purchase is required;
- individual airdrop = min(season pool × personal cumulative valid FP ÷ total cumulative valid FP of all eligible users, 5,000 $MFT); any undistributed amount rolls over to the next season;
- results are published after each season, followed by a 7-day appeal window;
- claim and release arrangements will be published before TGE.

### Season reset and transition

- FP and fish progression reset each season. Artwork, badges and confirmed $MFT airdrops are kept;
- test-season FP and fish do not migrate to the official version;
- users in the top 15% by cumulative FP across all three seasons receive 5% off their first official fish.

The test seasons also measure creation completion, retention, social interaction, state persistence, anti-Sybil effectiveness, indexer performance and SDK feedback.
