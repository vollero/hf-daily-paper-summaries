# Paper relationship graph — 2026-07-28

> [← Daily summary](../2026-07-28.md)

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

```mermaid
flowchart LR
  accTitle: Same-day paper relationships
  accDescr: Editorial hypotheses connecting papers from this daily collection.
  c2["2607.24744"]
  c3["2607.22798"]
  c4["2607.24280"]
  c5["2607.23588"]
  c7["2607.23855"]
  c8["2607.24731"]
  c9["2607.24743"]
  c10["2607.24516"]
  c11["2607.23806"]
  c12["2607.24651"]
  c14["2607.22148"]
  c16["2607.24241"]
  c3 ---|"Shared problem · High"| c5
  c3 ---|"Shared method · High"| c11
  c4 ---|"Shared method · High"| c8
  c7 ---|"Shared problem · High"| c14
  c9 ---|"Shared problem · High"| c12
  c10 -.->|"Method transfer · Medium"| c2
  c16 -.->|"Enabling dependency · Medium"| c7
```

| Source paper | Target paper | Relationship | Direction | Confidence |
| --- | --- | --- | --- | --- |
| [2607.22798](2607.22798.md) | [2607.23588](2607.23588.md) | Shared problem | Not directional | High |
| [2607.22798](2607.22798.md) | [2607.23806](2607.23806.md) | Shared method | Not directional | High |
| [2607.24280](2607.24280.md) | [2607.24731](2607.24731.md) | Shared method | Not directional | High |
| [2607.23855](2607.23855.md) | [2607.22148](2607.22148.md) | Shared problem | Not directional | High |
| [2607.24743](2607.24743.md) | [2607.24651](2607.24651.md) | Shared problem | Not directional | High |
| [2607.24516](2607.24516.md) | [2607.24744](2607.24744.md) | Method transfer | Source → target | Medium |
| [2607.24241](2607.24241.md) | [2607.23855](2607.23855.md) | Enabling dependency | Source → target | Medium |

## Connections to previously seen papers

_The visual diagram is omitted because this graph is too large or dense for a readable snapshot; every edge remains in the table below._

| New paper | Previously seen paper | First seen by service | Relationship | Technical direction | Confidence |
| --- | --- | --- | --- | --- | --- |
| [2607.24280](2607.24280.md) | 2607.14777 ([Hugging Face](https://huggingface.co/papers/2607.14777) · [arXiv](https://arxiv.org/abs/2607.14777)) | 2026-07-17 | Shared method | Not directional | High |
| [2607.24731](2607.24731.md) | 2607.13399 ([Hugging Face](https://huggingface.co/papers/2607.13399) · [arXiv](https://arxiv.org/abs/2607.13399)) | 2026-07-17 | Shared problem | Not directional | High |
| [2607.22798](2607.22798.md) | 2607.20709 ([Hugging Face](https://huggingface.co/papers/2607.20709) · [arXiv](https://arxiv.org/abs/2607.20709)) | 2026-07-24 | Shared method | Not directional | High |
| [2607.22798](2607.22798.md) | 2607.16617 ([Hugging Face](https://huggingface.co/papers/2607.16617) · [arXiv](https://arxiv.org/abs/2607.16617)) | 2026-07-22 | Complementary | Not directional | High |
| [2607.23588](2607.23588.md) | 2607.16617 ([Hugging Face](https://huggingface.co/papers/2607.16617) · [arXiv](https://arxiv.org/abs/2607.16617)) | 2026-07-22 | Shared method | Not directional | High |
| [2607.22148](2607.22148.md) | 2607.14088 ([Hugging Face](https://huggingface.co/papers/2607.14088) · [arXiv](https://arxiv.org/abs/2607.14088)) | 2026-07-20 | Shared method | Not directional | High |
| [2607.23855](2607.23855.md) | 2607.14088 ([Hugging Face](https://huggingface.co/papers/2607.14088) · [arXiv](https://arxiv.org/abs/2607.14088)) | 2026-07-20 | Complementary | Not directional | High |
| [2607.21694](2607.21694.md) | 2607.09362 ([Hugging Face](https://huggingface.co/papers/2607.09362) · [arXiv](https://arxiv.org/abs/2607.09362)) | 2026-07-14 | Complementary | Not directional | High |
| [2607.23806](2607.23806.md) | 2607.14431 ([Hugging Face](https://huggingface.co/papers/2607.14431) · [arXiv](https://arxiv.org/abs/2607.14431)) | 2026-07-17 | Shared method | Not directional | High |
| [2607.24651](2607.24651.md) | 2607.10400 ([Hugging Face](https://huggingface.co/papers/2607.10400) · [arXiv](https://arxiv.org/abs/2607.10400)) | 2026-07-15 | Follow-up opportunity | Not directional | High |
| [2607.21936](2607.21936.md) | 2607.11562 ([Hugging Face](https://huggingface.co/papers/2607.11562) · [arXiv](https://arxiv.org/abs/2607.11562)) | 2026-07-15 | Complementary | Not directional | High |
| [2607.24744](2607.24744.md) | 2607.21017 ([Hugging Face](https://huggingface.co/papers/2607.21017) · [arXiv](https://arxiv.org/abs/2607.21017)) | 2026-07-24 | Shared problem | Not directional | High |

## Current paper key

| Paper | Analysis |
| --- | --- |
| 2607.21655 — Progress Reward Modeling for Robotic Learning: A Comprehensive Survey | [Read analysis](2607.21655.md) |
| 2607.24744 — Data Pyramid for Embodied Manipulation | [Read analysis](2607.24744.md) |
| 2607.22798 — StateAct: Program State, before Pixels, for Long-Horizon Computer-Use Agents | [Read analysis](2607.22798.md) |
| 2607.24280 — From Proprietary to Open-Source: Bridging the Distribution Gap via Multi-Agent Protocol Distillation in Agentic Search | [Read analysis](2607.24280.md) |
| 2607.23588 — JarvisHub: An Open Harness for Canvas-Native Multimodal Creative Agents | [Read analysis](2607.23588.md) |
| 2607.24653 — Kimi K3: Open Frontier Intelligence | [Read analysis](2607.24653.md) |
| 2607.23855 — OmniVAE: An Audio-Video VAE with Cross-Modal Alignment for Joint Generation | [Read analysis](2607.23855.md) |
| 2607.24731 — Rethinking Classifier-Free Guidance in On-Policy Diffusion Distillation | [Read analysis](2607.24731.md) |
| 2607.24743 — ClinFusion: A Vision-Centric Multimodal LLM System for Holistic Medical Understanding | [Read analysis](2607.24743.md) |
| 2607.24516 — DecoupleMix: Decoupled Ratio Search and Convex Allocation for Scalable VLM Data Recipes | [Read analysis](2607.24516.md) |
| 2607.23806 — A Frozen 12B Beats Frontier Models on Verified Work: 100% Accuracy, 0 Tokens, Bit-Exact, Forever | [Read analysis](2607.23806.md) |
| 2607.24651 — Evidence Attribution in Visual Document Understanding without Coordinates or Region Labels | [Read analysis](2607.24651.md) |
| 2607.23687 — GNM Head: A Generative aNthropometric Model of the human head | [Read analysis](2607.23687.md) |
| 2607.22148 — dRAE: Representation Autoencoder with Hyper-Spherical Codes | [Read analysis](2607.22148.md) |
| 2607.21694 — Oxygen-TryOn: Fashion-Native Foundation Model for Any-item Virtual Try-On | [Read analysis](2607.21694.md) |
| 2607.24241 — FilmBench: A Film-Grade Benchmark for Cinematic Video Generation | [Read analysis](2607.24241.md) |
| 2607.23822 — DriveDNA: A Large-Scale Multimodal Naturalistic Driving Dataset and Benchmark for Driving Style Identification | [Read analysis](2607.23822.md) |
| 2607.23242 — IndicTalk: A Large-Scale Persona-Based Multilingual Conversational Corpus for Indic Languages | [Read analysis](2607.23242.md) |
| 2607.21936 — Leveraging External Knowledge for Historical Document Restoration via Retrieval-Augmented Large Language Models | [Read analysis](2607.21936.md) |

## Current papers without a published edge

- [2607.21655](2607.21655.md)
- [2607.24653](2607.24653.md)
- [2607.23687](2607.23687.md)
- [2607.23822](2607.23822.md)
- [2607.23242](2607.23242.md)

---

[Support these research summaries on Buy Me a Coffee](https://buymeacoffee.com/vollero)
