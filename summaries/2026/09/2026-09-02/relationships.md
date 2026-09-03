# Paper relationship graph — 2026-09-02

> [← Daily summary](../2026-09-02.md)

> **Interpretation caveat:** Every edge is an evidence-screened editorial hypothesis, not proof of citation, influence, priority, historical use, dependency, or an author-claimed relationship.

## Legend

- Rectangular nodes are current-day papers; rounded nodes are previously seen candidates.
- A line has no technical direction. An arrow shows only a proposed technical flow for an enabling dependency or method transfer.
- Solid edges are high confidence; dotted edges are medium confidence. Confidence evaluates this editorial connection, not either paper.
- Relationship labels:
  - **Shared problem:** `shared_problem`
  - **Shared method:** `shared_method`
  - **Shared evaluation:** `shared_evaluation`
  - **Complementary:** `complementary`
  - **Enabling dependency:** `enabling_dependency`
  - **Method transfer:** `method_transfer`
  - **Assumption tension:** `assumption_tension`
  - **Result tension:** `result_tension`
  - **Shared limitation:** `shared_limitation`
  - **Follow-up opportunity:** `follow_up_opportunity`

## Same-day relationships

_The visual diagram is omitted because this graph is too large or dense for a readable snapshot; every edge remains in the table below._

| Source paper | Target paper | Relationship | Direction | Confidence |
| --- | --- | --- | --- | --- |
| [2609.01560](2609.01560.md) | [2609.00188](2609.00188.md) | Shared method | Not directional | High |
| [2609.00092](2609.00092.md) | [2609.01836](2609.01836.md) | Complementary | Not directional | High |
| [2608.26623](2608.26623.md) | [2609.00646](2609.00646.md) | Shared problem | Not directional | High |
| [2609.01404](2609.01404.md) | [2609.01453](2609.01453.md) | Shared problem | Not directional | Medium |
| [2608.30468](2608.30468.md) | [2609.00551](2609.00551.md) | Method transfer | Source → target | Medium |
| [2609.00551](2609.00551.md) | [2608.31082](2608.31082.md) | Complementary | Not directional | High |
| [2609.01343](2609.01343.md) | [2609.01532](2609.01532.md) | Shared problem | Not directional | High |
| [2609.01607](2609.01607.md) | [2609.00968](2609.00968.md) | Shared method | Not directional | High |
| [2608.27831](2608.27831.md) | [2609.01481](2609.01481.md) | Enabling dependency | Source → target | High |
| [2609.00621](2609.00621.md) | [2609.01404](2609.01404.md) | Method transfer | Source → target | High |
| [2609.00137](2609.00137.md) | [2608.27509](2608.27509.md) | Shared method | Not directional | Medium |
| [2609.01836](2609.01836.md) | [2608.30478](2608.30478.md) | Method transfer | Source → target | High |

## Connections to previously seen papers

_The visual diagram is omitted because this graph is too large or dense for a readable snapshot; every edge remains in the table below._

| New paper | Previously seen paper | First seen by service | Relationship | Technical direction | Confidence |
| --- | --- | --- | --- | --- | --- |
| [2609.00111](2609.00111.md) | 2608.01755 ([Hugging Face](https://huggingface.co/papers/2608.01755) · [arXiv](https://arxiv.org/abs/2608.01755)) | 2026-08-04 | Shared problem | Not directional | High |
| [2609.00111](2609.00111.md) | 2608.07468 ([Hugging Face](https://huggingface.co/papers/2608.07468) · [arXiv](https://arxiv.org/abs/2608.07468)) | 2026-08-10 | Shared evaluation | Not directional | High |
| [2609.01343](2609.01343.md) | 2608.03457 ([Hugging Face](https://huggingface.co/papers/2608.03457) · [arXiv](https://arxiv.org/abs/2608.03457)) | 2026-08-05 | Shared method | Not directional | High |
| [2609.01560](2609.01560.md) | 2608.26200 ([Hugging Face](https://huggingface.co/papers/2608.26200) · [arXiv](https://arxiv.org/abs/2608.26200)) | 2026-08-28 | Shared method | Not directional | High |
| [2609.00188](2609.00188.md) | 2607.26657 ([Hugging Face](https://huggingface.co/papers/2607.26657) · [arXiv](https://arxiv.org/abs/2607.26657)) | 2026-08-10 | Complementary | Not directional | High |
| [2609.00188](2609.00188.md) | 2608.27550 ([Hugging Face](https://huggingface.co/papers/2608.27550) · [arXiv](https://arxiv.org/abs/2608.27550)) | 2026-08-31 | Shared problem | Not directional | High |
| [2609.01481](2609.01481.md) | 2608.10450 ([Hugging Face](https://huggingface.co/papers/2608.10450) · [arXiv](https://arxiv.org/abs/2608.10450)) | 2026-08-13 | Shared problem | Not directional | High |
| [2609.01481](2609.01481.md) | 2608.28281 ([Hugging Face](https://huggingface.co/papers/2608.28281) · [arXiv](https://arxiv.org/abs/2608.28281)) | 2026-08-31 | Complementary | Not directional | High |
| [2608.30730](2608.30730.md) | 2607.28956 ([Hugging Face](https://huggingface.co/papers/2607.28956) · [arXiv](https://arxiv.org/abs/2607.28956)) | 2026-08-05 | Shared evaluation | Not directional | High |
| [2608.30457](2608.30457.md) | 2608.02585 ([Hugging Face](https://huggingface.co/papers/2608.02585) · [arXiv](https://arxiv.org/abs/2608.02585)) | 2026-08-04 | Shared problem | Not directional | High |
| [2609.01836](2609.01836.md) | 2608.00677 ([Hugging Face](https://huggingface.co/papers/2608.00677) · [arXiv](https://arxiv.org/abs/2608.00677)) | 2026-08-13 | Shared problem | Not directional | High |
| [2609.00551](2609.00551.md) | 2608.14718 ([Hugging Face](https://huggingface.co/papers/2608.14718) · [arXiv](https://arxiv.org/abs/2608.14718)) | 2026-08-18 | Complementary | Not directional | High |

## Current paper key

| Paper | Analysis |
| --- | --- |
| 2609.01591 — StudentSim: Training LLM-based Student Simulators | [Read analysis](2609.01591.md) |
| 2609.00111 — Qwen-Drive-1.0: An Initial Step towards a Vision-Language Foundation Model for Autonomous Driving | [Read analysis](2609.00111.md) |
| 2609.01343 — SMELT: Scaling Laws for Compute-Matched MoE Looped Transformers | [Read analysis](2609.01343.md) |
| 2609.00028 — UI-Venus-2 Technical Report | [Read analysis](2609.00028.md) |
| 2609.01560 — H3-World: Turning Language Understanding into World Control | [Read analysis](2609.01560.md) |
| 2609.00188 — ZimaBlue: Evolving Generalizable World Action Models through Scalable Video Pre-training | [Read analysis](2609.00188.md) |
| 2609.01572 — From Production Traffic to Post-Training: Building a Self-Hosted LLM That Covers the Corporate Request Mix | [Read analysis](2609.01572.md) |
| 2608.30468 — Hi-Q: Hierarchical Evidence-guided Query Refinement for Multi-Hop Question Answering | [Read analysis](2608.30468.md) |
| 2609.01404 — Evaluating Multimodal LLMs as Generalist Vision-Language-Action Agents for Drone Control: Commanding, Approaching, Tracking and Searching | [Read analysis](2609.01404.md) |
| 2609.01607 — Uncovering Understanding-Generation Synergy in Native Unified Multimodal Models: From Representation, Task to System | [Read analysis](2609.01607.md) |
| 2609.00092 — Safin-1: Safety from Within through Memory-Native State Evolution | [Read analysis](2609.00092.md) |
| 2608.26623 — AgentJudgeBench: A Multi-Difficulty Benchmark for Evaluating LLM Judges on Agentic Tool-Calling | [Read analysis](2608.26623.md) |
| 2609.00768 — DiagEvo: Diagnosis-Guided Self-Evolution via Hierarchical Error Memory | [Read analysis](2609.00768.md) |
| 2609.01481 — Harness-of-Harness: Multi-Day Autonomous Software Development with Continual Improvement | [Read analysis](2609.01481.md) |
| 2609.00551 — EM^2Mem: Event-Centric Multimodal Memory for Large Language Models | [Read analysis](2609.00551.md) |
| 2608.30478 — Agents in the Large: Perception-Centered Architecture for Persistent Agents | [Read analysis](2608.30478.md) |
| 2609.00621 — Control-Data Flow Separation: Stable Prompt Optimization in Multi-Agent LLMs | [Read analysis](2609.00621.md) |
| 2608.30730 — E-Commerce Bench: Evaluating LLM Agents on Long-Horizon Autonomous Business Operation | [Read analysis](2608.30730.md) |
| 2608.28612 — InternReviewer &amp; InternAdvocate: Objective Reward and Evaluation for Agentic Reinforcement Learning in Peer Review and Rebuttal | [Read analysis](2608.28612.md) |
| 2608.30457 — Learning Where Outcomes Change:Credit-Addressable Reasoning for Multimodal Geometry | [Read analysis](2608.30457.md) |
| 2609.01836 — Agent Memory Is a Surface for Endogenous Authorization Laundering | [Read analysis](2609.01836.md) |
| 2609.00968 — ReFlowSET: Representation-Aligned Latent Flow Matching for SAR-to-EO Image Translation | [Read analysis](2609.00968.md) |
| 2609.00374 — Adapting Without Gradients: Affine Statistics Transport and What Its Certificate Can Tell You | [Read analysis](2609.00374.md) |
| 2609.00137 — Recursive Criticality of AI Self-Improvement | [Read analysis](2609.00137.md) |
| 2609.00646 — DramaChain Bench: An End-to-End Benchmark for Short-Drama Generation | [Read analysis](2609.00646.md) |
| 2608.27509 — The Mechanics of Democratic Dominance: A System Dynamics Paradigm for Dynamic Consent Engineering | [Read analysis](2608.27509.md) |
| 2608.31082 — Token-Efficient Data Reasoning Agents via Adaptive Structuring of Unstructured Data | [Read analysis](2608.31082.md) |
| 2609.01532 — Knowledge Distillation During Mid-Training Favors Reasoning over Factual Recall | [Read analysis](2609.01532.md) |
| 2609.01453 — Does Imitation Learning Preserve Temporal Robustness in Dexterous Manipulation? An Expert-Learner Comparison Across Task Execution Speeds | [Read analysis](2609.01453.md) |
| 2608.27831 — RealSWE: A Compositional Evaluation of Coding Agents under Realistic User Requests | [Read analysis](2608.27831.md) |

## Current papers without a published edge

- [2609.01591](2609.01591.md)
- [2609.00028](2609.00028.md)
- [2609.01572](2609.01572.md)
- [2609.00768](2609.00768.md)
- [2608.28612](2608.28612.md)
- [2609.00374](2609.00374.md)

---

[Support these research summaries on Buy Me a Coffee](https://buymeacoffee.com/vollero)
