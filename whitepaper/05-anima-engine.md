# 🧠 5. Anima Engine™ — Intelligence Layer

**Definition:** The interpretation, validation, behavior and state-compilation engine for User-Generated Agents.

Anima converts human expression into structured Agent data while keeping AI computation decoupled from ownership settlement.

## 5.1 Two Sides of Anima

### Anima Creator

The user-facing creation pipeline transforms a human-created input into a structured Agent.

1. **Capture** — drawing strokes, colors, geometry, timing, optional text and other creation inputs.
2. **Validation** — category recognition, anti-abuse checks and creation-rule validation.
3. **Feature Extraction** — conversion of raw expression into normalized visual and behavioral features.
4. **Trait Compilation** — generation of bounded, versioned game attributes.
5. **Behavior Profile** — creation of machine-readable tendencies, preferences and action parameters.
6. **Identity Packaging** — visual hash, DNA hash, behavior profile hash, metadata and signed payload.
7. **MAP Commit** — submission of ownership-critical state to the protocol.

### Anima Developer Runtime

The developer-facing runtime helps studios create or operate Agent-driven content without building a complete AI stack from scratch.

Target capabilities include:

- **Developer Intent → Agent Template**
- **Developer Intent → NPC Configuration**
- structured behavior profiles;
- personality and action parameters;
- controlled memory generation and summarization;
- reusable Agent archetypes;
- validation hooks;
- signed state payload generation;
- runtime adapters for game engines.

The long-term idea is similar to a credible, bounded version of “Text-to-NPC”: developers describe the intended role and behavioral constraints, while Anima compiles the result into structured data a game can actually consume.

MetaFishtank does **not** assume that a single prompt instantly creates production-ready AAA 3D characters, animation rigs and complete behavior trees. High-fidelity rendering remains a separate application layer and long-term research direction.

## 5.2 Feature Extraction Framework

Anima can extract reproducible feature vectors from user expression.

### Geometry

- curvature distribution;
- symmetry;
- aspect ratio;
- stroke density;
- silhouette complexity;
- proportion relationships.

### Color

- hue distribution;
- saturation;
- dominant colors;
- contrast;
- palette structure.

### Creation Behavior

Where consented and product-relevant:

- stroke speed;
- correction frequency;
- drawing sequence;
- spatial attention;
- creation duration.

These features are converted into bounded traits through a versioned compiler.

A conceptual formulation is:

`Trait_k = Clamp(Σ_i w_(k,i) F_i + b_k, L_k, U_k)`

The mapping version can be hashed or versioned so the same input can be reproduced and audited.

## 5.3 Behavior Profiles

Traits answer “what properties does this Agent have?” Behavior profiles answer “how should this Agent tend to act?”

A profile can include bounded parameters such as:

- aggression;
- curiosity;
- exploration tendency;
- cooperation;
- risk tolerance;
- preferred distance;
- resource-seeking behavior;
- social affinity.

Games remain free to interpret those parameters differently through adapters.

## 5.4 Memory Architecture

Anima separates memory into layers:

- **Canonical Memory Anchors** — important identity-relevant checkpoints.
- **Structured Game Memory** — achievements, quests, relationships and game-specific events.
- **Extended Semantic Memory** — off-chain summaries or embeddings when useful.
- **Runtime Context** — temporary session context that does not need permanent persistence.

This prevents the protocol from pretending every dialogue or event belongs on-chain while still allowing important history to become part of the Agent.

## 5.5 Verification Roadmap

Verification is intentionally phased.

### Phase 1 — Signed Inference

- signed inference payloads;
- deterministic validation where possible;
- model/version identifiers;
- replay protection;
- state hashes;
- bounded outputs.

### Phase 2 — Optional TEE

Trusted Execution Environment attestations can be introduced for inference or validation workflows where they improve trust without making the product unusable.

### Phase 3 — Optional zkML

Zero-knowledge machine-learning proofs can be evaluated when proof cost, latency and tooling are practical for a real consumer product.

MetaFishtank does not make mature zkML a launch dependency.

## 5.6 The Data and Model Moat

Over time, MetaFishtank can accumulate a specialized dataset linking:

**Human Expression → Feature Vector → Traits → Behavior → Game Feedback → Evolution**

That dataset can improve Anima's models, mapping quality and developer tooling. In the long term, the resulting intent-to-behavior capability may support B2B developer services or licensing beyond MetaFishtank's own games.
