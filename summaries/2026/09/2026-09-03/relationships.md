# Paper relationship graph — 2026-09-03

> [← Daily summary](../2026-09-03.md)

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
| [2609.02749](2609.02749.md) | [2609.02272](2609.02272.md) | Complementary | Not directional | High |
| [2609.01437](2609.01437.md) | [2609.00196](2609.00196.md) | Shared problem | Not directional | High |
| [2609.01437](2609.01437.md) | [2609.02783](2609.02783.md) | Enabling dependency | Source → target | High |
| [2608.31111](2608.31111.md) | [2608.31100](2608.31100.md) | Shared problem | Not directional | High |
| [2609.02737](2609.02737.md) | [2609.01925](2609.01925.md) | Complementary | Not directional | High |
| [2609.01147](2609.01147.md) | [2609.01657](2609.01657.md) | Shared problem | Not directional | High |
| [2608.21450](2608.21450.md) | [2608.29607](2608.29607.md) | Shared problem | Not directional | High |
| [2608.30949](2608.30949.md) | [2608.29607](2608.29607.md) | Complementary | Not directional | High |
| [2609.02817](2609.02817.md) | [2608.29846](2608.29846.md) | Shared evaluation | Not directional | High |
| [2608.29692](2608.29692.md) | [2608.29669](2608.29669.md) | Shared method | Not directional | High |
| [2608.30751](2608.30751.md) | [2609.00377](2609.00377.md) | Shared method | Not directional | High |
| [2609.00834](2609.00834.md) | [2609.01865](2609.01865.md) | Method transfer | Source → target | Medium |

## Connections to previously seen papers

_The visual diagram is omitted because this graph is too large or dense for a readable snapshot; every edge remains in the table below._

| New paper | Previously seen paper | First seen by service | Relationship | Technical direction | Confidence |
| --- | --- | --- | --- | --- | --- |
| [2609.02749](2609.02749.md) | 2608.03874 ([Hugging Face](https://huggingface.co/papers/2608.03874) · [arXiv](https://arxiv.org/abs/2608.03874)) | 2026-08-05 | Shared problem | Not directional | High |
| [2609.02749](2609.02749.md) | 2608.10538 ([Hugging Face](https://huggingface.co/papers/2608.10538) · [arXiv](https://arxiv.org/abs/2608.10538)) | 2026-08-14 | Complementary | Not directional | High |
| [2609.01437](2609.01437.md) | 2608.06301 ([Hugging Face](https://huggingface.co/papers/2608.06301) · [arXiv](https://arxiv.org/abs/2608.06301)) | 2026-08-07 | Shared evaluation | Not directional | High |
| [2609.01437](2609.01437.md) | 2608.09096 ([Hugging Face](https://huggingface.co/papers/2608.09096) · [arXiv](https://arxiv.org/abs/2608.09096)) | 2026-08-11 | Shared problem | Not directional | High |
| [2609.00196](2609.00196.md) | 2608.06714 ([Hugging Face](https://huggingface.co/papers/2608.06714) · [arXiv](https://arxiv.org/abs/2608.06714)) | 2026-08-10 | Shared method | Not directional | Medium |
| [2609.02886](2609.02886.md) | 2608.14022 ([Hugging Face](https://huggingface.co/papers/2608.14022) · [arXiv](https://arxiv.org/abs/2608.14022)) | 2026-08-21 | Shared method | Not directional | High |
| [2609.02886](2609.02886.md) | 2608.15659 ([Hugging Face](https://huggingface.co/papers/2608.15659) · [arXiv](https://arxiv.org/abs/2608.15659)) | 2026-08-18 | Enabling dependency | Previous → new | Medium |
| [2609.01657](2609.01657.md) | 2608.15698 ([Hugging Face](https://huggingface.co/papers/2608.15698) · [arXiv](https://arxiv.org/abs/2608.15698)) | 2026-08-18 | Shared evaluation | Not directional | High |
| [2609.01740](2609.01740.md) | 2608.14783 ([Hugging Face](https://huggingface.co/papers/2608.14783) · [arXiv](https://arxiv.org/abs/2608.14783)) | 2026-08-18 | Shared method | Not directional | High |
| [2609.02817](2609.02817.md) | 2608.25580 ([Hugging Face](https://huggingface.co/papers/2608.25580) · [arXiv](https://arxiv.org/abs/2608.25580)) | 2026-08-27 | Shared method | Not directional | High |
| [2609.02783](2609.02783.md) | 2608.28281 ([Hugging Face](https://huggingface.co/papers/2608.28281) · [arXiv](https://arxiv.org/abs/2608.28281)) | 2026-08-31 | Shared problem | Not directional | High |
| [2609.02812](2609.02812.md) | 2608.26005 ([Hugging Face](https://huggingface.co/papers/2608.26005) · [arXiv](https://arxiv.org/abs/2608.26005)) | 2026-08-27 | Enabling dependency | New → previous | Medium |

## Current paper key

| Paper | Analysis |
| --- | --- |
| 2609.02749 — Repo-To-Skill: Distilling GitHub Repositories Into AI4AI Skills | [Read analysis](2609.02749.md) |
| 2609.01437 — HarnessDev: Can LLMs Create and Evolve Their Own Agent Harness? | [Read analysis](2609.01437.md) |
| 2608.31111 — Aspire: Can Models Self-Evolve from Vague Goals? | [Read analysis](2608.31111.md) |
| 2609.02886 — SolarWM: Open Data and Scalable Training for Long-Horizon Video World Models | [Read analysis](2609.02886.md) |
| 2609.02783 — EarlyEval: Cheaper Agent Evaluation via Early Outcome Prediction | [Read analysis](2609.02783.md) |
| 2609.00638 — It Takes Two to Match: Co-Evolving Generative Retriever with Reinforcement Learning | [Read analysis](2609.00638.md) |
| 2609.02737 — Language Models Can Control Their Own Attention | [Read analysis](2609.02737.md) |
| 2609.01147 — On the Design Fundamentals of Pixel Text Representation Learning | [Read analysis](2609.01147.md) |
| 2609.00196 — WHALE: A Simple Recipe for Joint Harness-Weight Optimization | [Read analysis](2609.00196.md) |
| 2608.31100 — S3Gym: Can LLMs Turn Self-Testing and Self-Judging into Self-Improvement? | [Read analysis](2608.31100.md) |
| 2608.21450 — Beyond Visual Similarity: Entity-Aligned Retrieval for Knowledge-Based Visual Question Answering | [Read analysis](2608.21450.md) |
| 2609.01657 — NeoMME: A Single-Tower Multimodal-Native Multilingual Foundation Encoder for Efficient Fine-Tuning and Inference | [Read analysis](2609.01657.md) |
| 2609.01740 — ZipTok3D: High-Fidelity 3D Tokenization with Compact Token Prefixes | [Read analysis](2609.01740.md) |
| 2609.00591 — A Glance Is All You Need: Single-Pass Fine-Grained Image Captioning with SimLoss | [Read analysis](2609.00591.md) |
| 2609.02817 — Cliff: Learning Process Rewards from the First Mistake | [Read analysis](2609.02817.md) |
| 2608.29846 — Influence-Directed Distillation: Solving the Diversity Bottleneck in Sampled-Token On-Policy Distillation | [Read analysis](2608.29846.md) |
| 2609.02812 — VibeVoice-ASR-Streaming Technical Report | [Read analysis](2609.02812.md) |
| 2609.02849 — Post-Training Language Models for Gold-Medal Performance in Coding Competitions | [Read analysis](2609.02849.md) |
| 2608.18972 — Institutional Newspapers Pipeline: Deriving billions of high quality tokens from historical newspapers | [Read analysis](2608.18972.md) |
| 2609.01925 — CRISP: Cliff-awaRe Input-adaptive Sparse Prefilling with Structural-Mass-Motivated Routing | [Read analysis](2609.01925.md) |
| 2608.30949 — MULTI3IR: A Benchmark for Multi-perspective Multi-domain Multi-modal Information Retrieval | [Read analysis](2608.30949.md) |
| 2609.02272 — PaperCompiler: Faithful Paper-to-Code Generation via Repository-Level Specification Compilation | [Read analysis](2609.02272.md) |
| 2609.01865 — ExecRetrieval: Measuring the Functional-Correctness Gap in Code-Embedding Retrieval | [Read analysis](2609.01865.md) |
| 2609.00474 — Exploring Collaboration between a language and a non-language agent | [Read analysis](2609.00474.md) |
| 2608.29607 — SnapBench: Benchmarking Snap-and-Ask Multimodal Retrieval for Mobile Interactions | [Read analysis](2608.29607.md) |
| 2608.30322 — Ignorance or Incompetence? Constructing Knowledge-Gated, Verifiable Tasks for LLM Agents | [Read analysis](2608.30322.md) |
| 2608.30751 — Autoregressive Mosaics: Probing 2D Spatial Reasoning in Text-Only Language Models | [Read analysis](2608.30751.md) |
| 2609.01823 — Kirin: Animal Motion Generation from In-the-Wild Video | [Read analysis](2609.01823.md) |
| 2609.00377 — FoldingAgent: Inferring Parametric Origami Procedures from Demonstration Videos | [Read analysis](2609.00377.md) |
| 2609.02496 — Debias-SparseGPT: Bias-Aware Pruning for Large Language Models | [Read analysis](2609.02496.md) |
| 2609.01936 — Sparse Readout Prism: Explaining Logit-Lens Scores in Features Instead of Tokens | [Read analysis](2609.01936.md) |
| 2609.00834 — Replacing Training with Memory: Listwise Selection for Text-to-SQL | [Read analysis](2609.00834.md) |
| 2608.30005 — Small Language Models as Judges for Rubric-Based Reinforcement Learning | [Read analysis](2608.30005.md) |
| 2608.29692 — Portfolio Risk Bounds without Cross-Asset Return Covariances: Distributional Fields from Language-Model Representations | [Read analysis](2608.29692.md) |
| 2504.15476 — An Empirical Study on Zero-Data Bootstrapping for Conversational Recommender Systems | [Read analysis](2504.15476.md) |
| 2608.29669 — Wasserstein-Barycentric Interaction Fields for Spatial Factor Models: Evidence from Language-Model Representations | [Read analysis](2608.29669.md) |

## Current papers without a published edge

- [2609.00638](2609.00638.md)
- [2609.00591](2609.00591.md)
- [2609.02849](2609.02849.md)
- [2608.18972](2608.18972.md)
- [2609.00474](2609.00474.md)
- [2608.30322](2608.30322.md)
- [2609.01823](2609.01823.md)
- [2609.02496](2609.02496.md)
- [2609.01936](2609.01936.md)
- [2608.30005](2608.30005.md)
- [2504.15476](2504.15476.md)

---

[Support these research summaries on Buy Me a Coffee](https://buymeacoffee.com/vollero)
