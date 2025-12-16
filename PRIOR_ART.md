# PRIOR_ART.md — Prior Art & Distinction (SimNap Autonomous Dreaming AI)

## Purpose

Intended for reviewers/historians/examiners
12-15-2025

This document is intended as a prior-art clarification and attribution aid for reviewers, historians, and examiners.

This document exists to (1) acknowledge relevant prior work that uses “dreaming / imagination / simulation” language in AI, and (2) precisely distinguish what SimNap means by **autonomous dreaming** as a *system behavior*.

This is not a “who’s best” doc. It’s a timeline + definitions doc.

---

## Core Definitions (Operational)

### Autonomous (SimNap definition)

**Autonomous** means the system initiates dream cycles on its own (e.g., scheduled/triggered), without requiring a user prompt to begin the cycle, and can persist/continue across sessions.

### Dreaming (SimNap definition)

**Dreaming** means the system runs an internal generative simulation loop that produces **dream artifacts** and **reflection outputs**, and persists them as first-class state (logs/reports/artifacts), not just ephemeral rollouts.

**Important:** This definition is about behavior and workflow, not consciousness.

---

## Relevant Prior Art (Acknowledged)

### 1) DAYDREAMER (Erik T. Mueller, 1983–1988)

DAYDREAMER is a classic AI/cognitive model described as a “computer model of the stream of thought,” explicitly framed around daydreaming and goals/emotions guiding scenario generation.
- CMU AI Repository listing: https://www.cs.cmu.edu/afs/cs/project/ai-repository/ai/new/daydreamer/0new.html  
- “Towards a computational theory of human daydreaming” (Mueller, 1985): https://web-archive.southampton.ac.uk/cogprints.org/521/1/ddcogsci.htm  

**Why it’s not the same claim:** DAYDREAMER is a cognitive architecture model of thought/daydreaming, not a modern autonomous agent with an operational “dream cycle pipeline” that persists artifacts/reports as a recurring system function in a deployed workflow.

---

### 2) Dyna (R. S. Sutton, 1990/1991)

Dyna integrates learning + planning + reactive execution; planning can involve simulated/hypothetical experience.
- ACM DOI: https://dl.acm.org/doi/abs/10.1145/122344.122377  
- Sci. Direct entry (1990): https://www.sciencedirect.com/science/article/abs/pii/B9781558601413500304  

**Why it’s not the same claim:** Dyna is a reinforcement-learning/planning architecture; it does not define or claim an *autonomous dreaming cycle* that produces persistent dream artifacts and reflective reports as an explicit, recurring system behavior.

---

### 3) Imagination-Augmented Agents (I2A) (Weber et al., 2017)

I2A uses a learned model to generate predicted rollouts (“imagination”) and learns how to interpret them to construct plans.
- arXiv: https://arxiv.org/abs/1707.06203  

**Why it’s not the same claim:** I2A is about using model predictions to support decision-making in RL tasks; it is not a system whose core product is a recurring autonomous dream cycle with persistent artifacts and reporting.

---

### 4) Dreamer / “Dream to Control” (Hafner et al., 2019 → DreamerV3, 2025)

Dreamer is a model-based RL approach that improves behavior by imagining trajectories in a learned world model.
- Dream to Control (2019): https://arxiv.org/abs/1912.01603  
- DreamerV3 (Nature, 2025): https://www.nature.com/articles/s41586-025-08744-2  
- Open implementation page: https://github.com/google-research/dreamer  

**Why it’s not the same claim:** Dreamer’s “dreaming” is latent imagination for control policies inside RL. It is not (by itself) a self-initiated, scheduled dream-cycle agent that persists dream artifacts and reflection reports as a first-class workflow output.

---

## SimNap Distinction (What This Repository Claims)

SimNap’s claim is *not* “first to ever simulate,” “first to use imagination,” or “first to use the word dream.”

SimNap’s claim is:

> **First publicly documented system framed as an autonomous Dream-Cycle AI** 
> where **dreaming is a recurring, self-initiated system behavior** that produces and persists **dream artifacts** and **reflection outputs** as primary outputs of the system (not just intermediate rollouts for RL control).

This is closer to “a scheduled internal cognition loop with persistent artifacts” than it is to “world-model planning.”

---

## Non-Claims (Explicit)

SimNap does **not** claim:

- consciousness, sentience, or human-like subjective experience
- invention of transformer architectures or foundational model training methods
- invention of simulation or model-based planning as a field

SimNap claims a **system behavior + architecture pattern**: autonomous, recurring dream cycles with persistent artifact/report outputs.

---

## Canonical Archive & Citation

- Zenodo DOI (canonical archive): https://doi.org/10.5281/zenodo.17946878  
- GitHub canonical repo: https://github.com/SweetKenneth/SimNap-Dreaming-AI-Whitepaper  

If you reference this work academically, cite the Zenodo DOI.
