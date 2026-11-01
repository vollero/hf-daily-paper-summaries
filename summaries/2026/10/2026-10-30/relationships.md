# Paper relationship graph — 2026-10-30

> [← Daily summary](../2026-10-30.md)

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
| [2610.33106](2610.33106.md) | [2610.35138](2610.35138.md) | Shared problem | Not directional | High |
| [2610.37161](2610.37161.md) | [2610.37786](2610.37786.md) | Shared method | Not directional | High |
| [2610.38293](2610.38293.md) | [2610.38342](2610.38342.md) | Shared problem | Not directional | High |
| [2610.32411](2610.32411.md) | [2610.40454](2610.40454.md) | Shared method | Not directional | High |
| [2610.34298](2610.34298.md) | [2610.39264](2610.39264.md) | Shared method | Not directional | High |
| [2610.38352](2610.38352.md) | [2610.39664](2610.39664.md) | Shared method | Not directional | High |
| [2610.25276](2610.25276.md) | [2610.40614](2610.40614.md) | Shared method | Not directional | High |
| [2610.40453](2610.40453.md) | [2610.39664](2610.39664.md) | Method transfer | Source → target | Medium |
| [2610.39663](2610.39663.md) | [2610.40647](2610.40647.md) | Shared method | Not directional | High |
| [2610.38568](2610.38568.md) | [2610.40564](2610.40564.md) | Shared problem | Not directional | High |
| [2610.38681](2610.38681.md) | [2610.39301](2610.39301.md) | Shared method | Not directional | High |

## Connections to previously seen papers

_The visual diagram is omitted because this graph is too large or dense for a readable snapshot; every edge remains in the table below._

| New paper | Previously seen paper | First seen by service | Relationship | Technical direction | Confidence |
| --- | --- | --- | --- | --- | --- |
| [2610.40647](2610.40647.md) | 2610.12307 ([Hugging Face](https://huggingface.co/papers/2610.12307) · [arXiv](https://arxiv.org/abs/2610.12307)) | 2026-10-12 | Shared problem | Not directional | Medium |
| [2610.40614](2610.40614.md) | 2610.17625 ([Hugging Face](https://huggingface.co/papers/2610.17625) · [arXiv](https://arxiv.org/abs/2610.17625)) | 2026-10-14 | Shared method | Not directional | Medium |
| [2610.25276](2610.25276.md) | 2610.17625 ([Hugging Face](https://huggingface.co/papers/2610.17625) · [arXiv](https://arxiv.org/abs/2610.17625)) | 2026-10-14 | Shared method | Not directional | Medium |
| [2610.39663](2610.39663.md) | 2610.29441 ([Hugging Face](https://huggingface.co/papers/2610.29441) · [arXiv](https://arxiv.org/abs/2610.29441)) | 2026-10-22 | Complementary | Not directional | Medium |
| [2610.37161](2610.37161.md) | 2610.04906 ([Hugging Face](https://huggingface.co/papers/2610.04906) · [arXiv](https://arxiv.org/abs/2610.04906)) | 2026-10-14 | Shared problem | Not directional | Medium |
| [2610.37786](2610.37786.md) | 2610.26828 ([Hugging Face](https://huggingface.co/papers/2610.26828) · [arXiv](https://arxiv.org/abs/2610.26828)) | 2026-10-22 | Enabling dependency | New → previous | Medium |
| [2610.38678](2610.38678.md) | 2610.34735 ([Hugging Face](https://huggingface.co/papers/2610.34735) · [arXiv](https://arxiv.org/abs/2610.34735)) | 2026-10-27 | Follow-up opportunity | Not directional | Medium |
| [2610.38681](2610.38681.md) | 2609.37915 ([Hugging Face](https://huggingface.co/papers/2609.37915) · [arXiv](https://arxiv.org/abs/2609.37915)) | 2026-10-01 | Shared problem | Not directional | Medium |
| [2610.39633](2610.39633.md) | 2610.02188 ([Hugging Face](https://huggingface.co/papers/2610.02188) · [arXiv](https://arxiv.org/abs/2610.02188)) | 2026-10-07 | Shared problem | Not directional | Medium |
| [2610.29927](2610.29927.md) | 2610.29932 ([Hugging Face](https://huggingface.co/papers/2610.29932) · [arXiv](https://arxiv.org/abs/2610.29932)) | 2026-10-22 | Shared method | Not directional | Medium |
| [2610.39264](2610.39264.md) | 2610.20939 ([Hugging Face](https://huggingface.co/papers/2610.20939) · [arXiv](https://arxiv.org/abs/2610.20939)) | 2026-10-16 | Shared method | Not directional | Medium |
| [2610.39664](2610.39664.md) | 2609.39982 ([Hugging Face](https://huggingface.co/papers/2609.39982) · [arXiv](https://arxiv.org/abs/2609.39982)) | 2026-10-01 | Shared method | Not directional | Medium |

## Current paper key

| Paper | Analysis |
| --- | --- |
| 2610.39633 — Intrinsic Distribution Matching | [Read analysis](2610.39633.md) |
| 2610.38568 — A-RSI: Adaptive Task Refresh for Zero-Data Multimodal Self-Improvement | [Read analysis](2610.38568.md) |
| 2610.39301 — Youtu-Parsing-Omni: One Encoder, One Schema, All Modalities | [Read analysis](2610.39301.md) |
| 2610.29927 — Your Benchmark Is an Empirical Measure Over Difficulty | [Read analysis](2610.29927.md) |
| 2610.36671 — Look Only When Needed: Certificate-Guided Visual Routing for Efficient Diffusion VLMs | [Read analysis](2610.36671.md) |
| 2610.39302 — Proving and Improving the Platonic Representation Hypothesis with JEPAs | [Read analysis](2610.39302.md) |
| 2610.40614 — L3G-World: Real-Time Infinite World Generation with Latent 3D Gaussian Memory | [Read analysis](2610.40614.md) |
| 2610.40647 — Read, Allocate, Route: Role-Coupled Tokenization for Pixel-Space Generative Transformers | [Read analysis](2610.40647.md) |
| 2610.37161 — WorkFactory: Turning Professional Intents into Executable Work for Scalable Agent Training | [Read analysis](2610.37161.md) |
| 2610.32411 — A Broader Look into MLLM's Retrieval Heads | [Read analysis](2610.32411.md) |
| 2610.33106 — VibeGame: Prompt-to-Game Development with AI-Native Engine and Self-Evolving Adversarial Agent Team | [Read analysis](2610.33106.md) |
| 2610.40599 — HairDeck: Animation-Ready Stylized Hair Cards from a Single Image | [Read analysis](2610.40599.md) |
| 2610.35138 — Co-Design Bench: Multimodal Collaborative Coding Evaluation for Agentic Models | [Read analysis](2610.35138.md) |
| 2610.38352 — WeVisCut: The Whole Editing Room in One Agent From Narration to Long-Form Video | [Read analysis](2610.38352.md) |
| 2610.38425 — IntReal: A Real-World Dataset and Benchmark for Multimodal Interleaved Generation | [Read analysis](2610.38425.md) |
| 2610.38331 — Multi-Token Prediction Done Right | [Read analysis](2610.38331.md) |
| 2610.21143 — CoSTA: Compressed Speech Token Adaptation for Efficient Spoken Dialogue Models | [Read analysis](2610.21143.md) |
| 2610.37786 — WebAnything: From the Wild Web to Scalable Agent Environments | [Read analysis](2610.37786.md) |
| 2610.38342 — Investor's Last Exam: Can AI Agents Do Equity Investment Without Seeing the Future? | [Read analysis](2610.38342.md) |
| 2610.40454 — Glance: The Generator Is Its Own Reranker | [Read analysis](2610.40454.md) |
| 2610.38678 — AskStream: When and What to Ask Proactively under Uncertainty in Streaming Video Understanding | [Read analysis](2610.38678.md) |
| 2610.39664 — EditAgent: Rethinking Agentic Image Editing | [Read analysis](2610.39664.md) |
| 2610.40453 — PhysInsert: Physically Plausible Object Insertion with Geometric Priors and Bidirectional Object-Scene Interactions | [Read analysis](2610.40453.md) |
| 2610.39264 — Online Dense Reinforcement Learning with Planning-Grounding Agent for UI Navigation on Live IOS Apps | [Read analysis](2610.39264.md) |
| 2610.40564 — Training Foundation Models with a Single Algorithm | [Read analysis](2610.40564.md) |
| 2610.39287 — OpenFlyV2: An onboard vision-language-action model for aerial perception and navigation | [Read analysis](2610.39287.md) |
| 2610.39663 — AB-Attention: Accurate Block Attention for Accelerating Video Diffusion Transformers | [Read analysis](2610.39663.md) |
| 2610.40362 — Your LR Schedule May Not Be Principled: Effective Learning Rate Scheduling in Weight-Normalized Training | [Read analysis](2610.40362.md) |
| 2610.36420 — SO-101 Bench: Accessible Spatial Manipulation | [Read analysis](2610.36420.md) |
| 2610.23656 — ABF-Bench: A Verifiable Benchmark for Agentic Blockchain Forensics | [Read analysis](2610.23656.md) |
| 2610.38293 — EPSBench: Benchmarking LLM Agents for Earnings Forecasting | [Read analysis](2610.38293.md) |
| 2610.38681 — Weaken to Strengthen: Weakening-Induced On-Policy Self-Distillation for Large Reasoning Models | [Read analysis](2610.38681.md) |
| 2610.39293 — Unlocking Any-Order Generation in Pretrained Autoregressive Image Models | [Read analysis](2610.39293.md) |
| 2610.34298 — Matched Capabilities, Different Behaviors: A Controlled Study of MCP and CLI Interfaces for Language Agents | [Read analysis](2610.34298.md) |
| 2609.05881 — Broken on Arrival: Non-Functional Quantized LLM Artifacts in Public Model Registries and How to Catch Them | [Read analysis](2609.05881.md) |
| 2610.38174 — Scaling Lean Theorem Proving for Real-World Code Verification | [Read analysis](2610.38174.md) |
| 2610.25276 — Holo4D: Holistic 4D Reconstruction as Geometric Control for Video Diffusion | [Read analysis](2610.25276.md) |
| 2610.37695 — After One-Click Video: The Inflow of Service-Type Content, the Failure of the Recommendation Pool Mechanism, and the BoLe System | [Read analysis](2610.37695.md) |
| 2610.39423 — FDSML: Formula-Driven Supervised Metric Learning with Parameter-Aware Triplet Loss | [Read analysis](2610.39423.md) |

## Current papers without a published edge

- [2610.36671](2610.36671.md)
- [2610.39302](2610.39302.md)
- [2610.40599](2610.40599.md)
- [2610.38425](2610.38425.md)
- [2610.38331](2610.38331.md)
- [2610.21143](2610.21143.md)
- [2610.39287](2610.39287.md)
- [2610.40362](2610.40362.md)
- [2610.36420](2610.36420.md)
- [2610.23656](2610.23656.md)
- [2610.39293](2610.39293.md)
- [2609.05881](2609.05881.md)
- [2610.38174](2610.38174.md)
- [2610.37695](2610.37695.md)
- [2610.39423](2610.39423.md)

---

[Support these research summaries on Buy Me a Coffee](https://buymeacoffee.com/vollero)
