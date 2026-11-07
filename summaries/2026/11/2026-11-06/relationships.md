# Paper relationship graph — 2026-11-06

> [← Daily summary](../2026-11-06.md)

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
| [2611.02660](2611.02660.md) | [2611.03743](2611.03743.md) | Shared method | Not directional | High |
| [2611.04527](2611.04527.md) | [2611.08373](2611.08373.md) | Shared method | Not directional | High |
| [2611.06817](2611.06817.md) | [2611.08373](2611.08373.md) | Shared evaluation | Not directional | High |
| [2611.02075](2611.02075.md) | [2611.07854](2611.07854.md) | Shared problem | Not directional | High |
| [2611.06500](2611.06500.md) | [2611.06976](2611.06976.md) | Shared method | Not directional | High |
| [2610.37739](2610.37739.md) | [2611.08237](2611.08237.md) | Shared method | Not directional | High |
| [2611.04386](2611.04386.md) | [2611.07392](2611.07392.md) | Shared method | Not directional | High |
| [2610.40119](2610.40119.md) | [2610.41789](2610.41789.md) | Complementary | Not directional | Medium |
| [2611.06982](2611.06982.md) | [2611.08449](2611.08449.md) | Shared method | Not directional | High |
| [2611.04277](2611.04277.md) | [2611.08483](2611.08483.md) | Shared method | Not directional | High |
| [2611.00883](2611.00883.md) | [2610.34074](2610.34074.md) | Method transfer | Source → target | Medium |
| [2611.02660](2611.02660.md) | [2611.08373](2611.08373.md) | Follow-up opportunity | Not directional | Medium |

## Connections to previously seen papers

_The visual diagram is omitted because this graph is too large or dense for a readable snapshot; every edge remains in the table below._

| New paper | Previously seen paper | First seen by service | Relationship | Technical direction | Confidence |
| --- | --- | --- | --- | --- | --- |
| [2611.00883](2611.00883.md) | 2610.18248 ([Hugging Face](https://huggingface.co/papers/2610.18248) · [arXiv](https://arxiv.org/abs/2610.18248)) | 2026-10-15 | Shared problem | Not directional | Medium |
| [2611.02660](2611.02660.md) | 2610.29560 ([Hugging Face](https://huggingface.co/papers/2610.29560) · [arXiv](https://arxiv.org/abs/2610.29560)) | 2026-10-22 | Shared method | Not directional | Medium |
| [2611.03743](2611.03743.md) | 2609.34565 ([Hugging Face](https://huggingface.co/papers/2609.34565) · [arXiv](https://arxiv.org/abs/2609.34565)) | 2026-10-21 | Shared method | Not directional | Medium |
| [2611.04277](2611.04277.md) | 2610.29458 ([Hugging Face](https://huggingface.co/papers/2610.29458) · [arXiv](https://arxiv.org/abs/2610.29458)) | 2026-10-22 | Shared method | Not directional | Medium |
| [2611.04386](2611.04386.md) | 2610.10460 ([Hugging Face](https://huggingface.co/papers/2610.10460) · [arXiv](https://arxiv.org/abs/2610.10460)) | 2026-10-08 | Shared method | Not directional | Medium |
| [2611.04527](2611.04527.md) | 2610.30320 ([Hugging Face](https://huggingface.co/papers/2610.30320) · [arXiv](https://arxiv.org/abs/2610.30320)) | 2026-10-23 | Shared method | Not directional | Medium |
| [2611.06498](2611.06498.md) | 2610.33732 ([Hugging Face](https://huggingface.co/papers/2610.33732) · [arXiv](https://arxiv.org/abs/2610.33732)) | 2026-10-27 | Complementary | Not directional | Medium |
| [2611.06741](2611.06741.md) | 2610.25404 ([Hugging Face](https://huggingface.co/papers/2610.25404) · [arXiv](https://arxiv.org/abs/2610.25404)) | 2026-10-20 | Shared method | Not directional | Medium |
| [2611.06817](2611.06817.md) | 2610.26855 ([Hugging Face](https://huggingface.co/papers/2610.26855) · [arXiv](https://arxiv.org/abs/2610.26855)) | 2026-10-21 | Shared method | Not directional | Medium |
| [2611.07854](2611.07854.md) | 2610.36915 ([Hugging Face](https://huggingface.co/papers/2610.36915) · [arXiv](https://arxiv.org/abs/2610.36915)) | 2026-11-04 | Shared problem | Not directional | Medium |
| [2611.08089](2611.08089.md) | 2610.20680 ([Hugging Face](https://huggingface.co/papers/2610.20680) · [arXiv](https://arxiv.org/abs/2610.20680)) | 2026-10-16 | Method transfer | Previous → new | Medium |
| [2611.08449](2611.08449.md) | 2610.13239 ([Hugging Face](https://huggingface.co/papers/2610.13239) · [arXiv](https://arxiv.org/abs/2610.13239)) | 2026-10-15 | Shared problem | Not directional | Medium |

## Current paper key

| Paper | Analysis |
| --- | --- |
| 2611.08449 — VFlash: Fast, Accurate Visual Planning via Flash Primitive Decoding | [Read analysis](2611.08449.md) |
| 2611.08373 — SLA: Scaling Spatial-Language-Action Model via Continual Pre-training | [Read analysis](2611.08373.md) |
| 2611.04277 — Harness-S: Learning from Sibling Harnesses for Generalizable Agent Training | [Read analysis](2611.04277.md) |
| 2611.05376 — From Autonomous Agents to Cognitive Symbionts: Toward AI-Augmented Human Intelligence | [Read analysis](2611.05376.md) |
| 2611.00883 — Random Is Almost Enough? Stable and Low-Cost Benchmark Compression via BestRand | [Read analysis](2611.00883.md) |
| 2611.07392 — WeLM-Image: A Unified Image Generation Model towards Visual Intelligence | [Read analysis](2611.07392.md) |
| 2611.06741 — TailSteer: Trajectory-Tail Steering for Drift-Resistant Multi-turn Image Editing | [Read analysis](2611.06741.md) |
| 2611.03743 — EvoMemState: Evolving Memory State for Personal Agents | [Read analysis](2611.03743.md) |
| 2611.07854 — Towards Foundation Decision Models: Drex | [Read analysis](2611.07854.md) |
| 2611.04894 — VisSearch-Bench: Evaluating Long Horizon Visual Search in Multimodal Agents | [Read analysis](2611.04894.md) |
| 2611.06817 — Open-HumanScale: An Open Recipe for Scaling Human and Robot Experience for Embodied Foundation Models | [Read analysis](2611.06817.md) |
| 2611.06976 — On the Opportunities and Challenges of Prefill-to-Autoregressive Cross-Model Transfer | [Read analysis](2611.06976.md) |
| 2611.07909 — EDGAR: Efficient Diffusion-Driven Gaussian Avatar Refinement via Synthetic Failure | [Read analysis](2611.07909.md) |
| 2611.08237 — Terminal-style Mathematical Modeling Bench: The First Agentic and Verifiable Benchmark for Mathematical Modeling | [Read analysis](2611.08237.md) |
| 2611.04527 — Future Representation Distillation for Imagination-free World Action Models | [Read analysis](2611.04527.md) |
| 2611.08483 — SwarmEvolve: Latent Agent Swarms for Evolutionary Discovery and Optimization | [Read analysis](2611.08483.md) |
| 2611.02660 — HeLM: Hierarchical Explicit Language Memory for Non-Markovian Manipulation | [Read analysis](2611.02660.md) |
| 2611.08376 — Muir: Linear Attention with Sensitivity-Allocated Gating and Matched-Filter Readout | [Read analysis](2611.08376.md) |
| 2611.07298 — Reducing Representational Interference in Retrieval Embeddings with Trainable Prefix Tokens | [Read analysis](2611.07298.md) |
| 2611.08089 — SAE Interprets MoE: Sparse AutoEncoders Reveal That MoE Experts Exhibit Human-Interpretable Fine-Grained Specialization | [Read analysis](2611.08089.md) |
| 2611.07613 — Towards Real-Time Full-Waveform LiDAR Transformers via Intensity-Guided Token Reduction and Physics-Aware Augmentation | [Read analysis](2611.07613.md) |
| 2611.06982 — Decode Before You Hear: Speculative Listening for Chunk-Interleaved Full-Duplex Speech Language Models | [Read analysis](2611.06982.md) |
| 2611.04386 — StepX-OPD: Rethinking Multi-Teacher On-Policy Distillation in Diffusion Models | [Read analysis](2611.04386.md) |
| 2610.37739 — OpenFrontiers: A Collection of Open Research Problems and a Benchmark for Scientific Rediscovery | [Read analysis](2610.37739.md) |
| 2609.37820 — Information Games: Strategic Crowding and Firm Repositioning in Language-Model Space | [Read analysis](2609.37820.md) |
| 2611.02075 — Decoupled Predictive Decision Making: A Shared Conditional Predictor for Agents | [Read analysis](2611.02075.md) |
| 2611.06500 — Tools Need Not Speak in Text: Latent Context Compression for Agents | [Read analysis](2611.06500.md) |
| 2611.06498 — Signed but Steerable: Measuring and Closing the Text-Vector Integrity Gap in Offline Retrieval-Augmented Generation | [Read analysis](2611.06498.md) |
| 2610.41789 — Hard Sample-Conditioned Decorrelated Attention for Robust Face Recognition | [Read analysis](2610.41789.md) |
| 2610.34074 — Identically Trained Language Models Break on Different Jailbreaks | [Read analysis](2610.34074.md) |
| 2611.08369 — NPCBench: A Clinical Apprenticeship Benchmark for Multimodal Care-Pathway Reasoning in Nasopharyngeal Carcinoma | [Read analysis](2611.08369.md) |
| 2610.40119 — SynthFaces: Balanced Large Scale Human Dataset | [Read analysis](2610.40119.md) |

## Current papers without a published edge

- [2611.05376](2611.05376.md)
- [2611.04894](2611.04894.md)
- [2611.07909](2611.07909.md)
- [2611.08376](2611.08376.md)
- [2611.07298](2611.07298.md)
- [2611.07613](2611.07613.md)
- [2609.37820](2609.37820.md)
- [2611.08369](2611.08369.md)

---

[Support these research summaries on Buy Me a Coffee](https://buymeacoffee.com/vollero)
