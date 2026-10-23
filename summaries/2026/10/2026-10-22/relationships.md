# Paper relationship graph — 2026-10-22

> [← Daily summary](../2026-10-22.md)

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
| [2610.28679](2610.28679.md) | [2610.26828](2610.26828.md) | Method transfer | Source → target | High |
| [2610.26828](2610.26828.md) | [2610.29458](2610.29458.md) | Complementary | Not directional | High |
| [2610.17860](2610.17860.md) | [2610.27227](2610.27227.md) | Shared method | Not directional | High |
| [2610.29357](2610.29357.md) | [2610.29317](2610.29317.md) | Method transfer | Source → target | High |
| [2610.19376](2610.19376.md) | [2610.28577](2610.28577.md) | Follow-up opportunity | Not directional | Medium |
| [2610.26397](2610.26397.md) | [2610.29680](2610.29680.md) | Shared problem | Not directional | High |
| [2610.23344](2610.23344.md) | [2610.28887](2610.28887.md) | Shared problem | Not directional | High |
| [2610.28763](2610.28763.md) | [2610.29932](2610.29932.md) | Shared problem | Not directional | High |
| [2610.27040](2610.27040.md) | [2610.26659](2610.26659.md) | Method transfer | Source → target | Medium |
| [2610.28402](2610.28402.md) | [2610.28827](2610.28827.md) | Follow-up opportunity | Not directional | Medium |
| [2610.30066](2610.30066.md) | [2610.30128](2610.30128.md) | Shared method | Not directional | High |
| [2610.13177](2610.13177.md) | [2610.30023](2610.30023.md) | Shared problem | Not directional | High |

## Connections to previously seen papers

_The visual diagram is omitted because this graph is too large or dense for a readable snapshot; every edge remains in the table below._

| New paper | Previously seen paper | First seen by service | Relationship | Technical direction | Confidence |
| --- | --- | --- | --- | --- | --- |
| [2610.11942](2610.11942.md) | 2610.14228 ([Hugging Face](https://huggingface.co/papers/2610.14228) · [arXiv](https://arxiv.org/abs/2610.14228)) | 2026-10-14 | Shared method | Not directional | Medium |
| [2610.26828](2610.26828.md) | 2609.33665 ([Hugging Face](https://huggingface.co/papers/2609.33665) · [arXiv](https://arxiv.org/abs/2609.33665)) | 2026-09-29 | Shared method | Not directional | Medium |
| [2610.28679](2610.28679.md) | 2609.35025 ([Hugging Face](https://huggingface.co/papers/2609.35025) · [arXiv](https://arxiv.org/abs/2609.35025)) | 2026-09-30 | Complementary | Not directional | Medium |
| [2610.27040](2610.27040.md) | 2609.39601 ([Hugging Face](https://huggingface.co/papers/2609.39601) · [arXiv](https://arxiv.org/abs/2609.39601)) | 2026-10-13 | Shared method | Not directional | Medium |
| [2610.27861](2610.27861.md) | 2609.36352 ([Hugging Face](https://huggingface.co/papers/2609.36352) · [arXiv](https://arxiv.org/abs/2609.36352)) | 2026-09-30 | Complementary | Not directional | Medium |
| [2610.26397](2610.26397.md) | 2609.36642 ([Hugging Face](https://huggingface.co/papers/2609.36642) · [arXiv](https://arxiv.org/abs/2609.36642)) | 2026-10-13 | Shared method | Not directional | Medium |
| [2610.29545](2610.29545.md) | 2609.38169 ([Hugging Face](https://huggingface.co/papers/2609.38169) · [arXiv](https://arxiv.org/abs/2609.38169)) | 2026-10-08 | Shared problem | Not directional | Medium |
| [2610.29934](2610.29934.md) | 2610.12453 ([Hugging Face](https://huggingface.co/papers/2610.12453) · [arXiv](https://arxiv.org/abs/2610.12453)) | 2026-10-12 | Shared method | Not directional | Medium |
| [2610.30066](2610.30066.md) | 2610.12582 ([Hugging Face](https://huggingface.co/papers/2610.12582) · [arXiv](https://arxiv.org/abs/2610.12582)) | 2026-10-12 | Shared method | Not directional | Medium |
| [2610.29560](2610.29560.md) | 2610.14224 ([Hugging Face](https://huggingface.co/papers/2610.14224) · [arXiv](https://arxiv.org/abs/2610.14224)) | 2026-10-14 | Shared method | Not directional | Medium |
| [2610.29441](2610.29441.md) | 2610.06801 ([Hugging Face](https://huggingface.co/papers/2610.06801) · [arXiv](https://arxiv.org/abs/2610.06801)) | 2026-10-09 | Complementary | Not directional | Medium |
| [2610.29357](2610.29357.md) | 2610.13021 ([Hugging Face](https://huggingface.co/papers/2610.13021) · [arXiv](https://arxiv.org/abs/2610.13021)) | 2026-10-12 | Shared problem | Not directional | Medium |

## Current paper key

| Paper | Analysis |
| --- | --- |
| 2610.28402 — StreamEval: Evaluating Interactive Streaming Video Generation Models | [Read analysis](2610.28402.md) |
| 2610.29989 — Looking Ahead: Modeling Future Evolution in Autoregressive Video Generation | [Read analysis](2610.29989.md) |
| 2610.29997 — DONIC: Generalist Dexterous Bimanual Tracking Control from Human Demonstrations | [Read analysis](2610.29997.md) |
| 2610.26659 — SpatialScout: Can VLM Agents Actively Explore and Map 3D Scenes? | [Read analysis](2610.26659.md) |
| 2610.21114 — Spectral-Spatial Interpretation | [Read analysis](2610.21114.md) |
| 2610.28577 — Cache Engineering for Agents | [Read analysis](2610.28577.md) |
| 2610.11942 — Right Screen, Wrong Transition: World Models as Verifiers for GUI Agents | [Read analysis](2610.11942.md) |
| 2610.26828 — Agent World Model in the Wild: Computer-Use Agent Environment Synthesis | [Read analysis](2610.26828.md) |
| 2610.28698 — Scaling in Games: Continued Pre-Training For Embodied Agents In Diverse Virtual Worlds | [Read analysis](2610.28698.md) |
| 2610.20538 — PrismaCoder: Pushing the Boundaries of Open Multimodal Code Intelligence through Decomposed Rubric Synthesis | [Read analysis](2610.20538.md) |
| 2610.17860 — Socratic Skill Learning: Interleaving Teaching and Practice for Transferable Agent Skills | [Read analysis](2610.17860.md) |
| 2610.29722 — Retrieval Augmented Generation Compositionality | [Read analysis](2610.29722.md) |
| 2610.29680 — TraceForge: Distilling with Your Own Thinking | [Read analysis](2610.29680.md) |
| 2610.28589 — AgenticRoboRL: Bringing Coding-Agent Post-Training to Agentic Robotics | [Read analysis](2610.28589.md) |
| 2610.29968 — CulturalRiddles: A Multicultural Benchmark of Riddles | [Read analysis](2610.29968.md) |
| 2610.30120 — ALPS: Visual State Encoders for World Models | [Read analysis](2610.30120.md) |
| 2610.29357 — Memory-Centric Continual Learning for AI Agents | [Read analysis](2610.29357.md) |
| 2610.29545 — PACE: Periodic and Channel-Aligned Encoding of Four-Bit Recurrent States | [Read analysis](2610.29545.md) |
| 2610.30108 — Multimodal Embodied Agents: A Unified Capability-centric Perspective from Computer-Use to Robot-Use | [Read analysis](2610.30108.md) |
| 2610.19376 — DeLoop: Repeated Actions as Self-Supervision for Long-Horizon Agents | [Read analysis](2610.19376.md) |
| 2610.27592 — Real In, Real Out: What If We Only Use Real Data for Scene Text Editing? | [Read analysis](2610.27592.md) |
| 2610.29458 — Harness Scaling for Generalizable Agentic Reinforcement Learning | [Read analysis](2610.29458.md) |
| 2610.28887 — Building AI Research Teams for Autonomous Discovery of Linear Attention Architectures | [Read analysis](2610.28887.md) |
| 2610.30023 — RealMe: Immersive Volumetric Video from Minimal Captures | [Read analysis](2610.30023.md) |
| 2610.29441 — Sparsity Should Be ALLOTted by Output: Training-Free Allocation of Block-Sparse Attention for Video Diffusion Transformers | [Read analysis](2610.29441.md) |
| 2610.28763 — Automating ML for Science: Can Frontier Agents Climb Scientific Hills in the Wild? | [Read analysis](2610.28763.md) |
| 2610.30136 — Agentic World Action Models | [Read analysis](2610.30136.md) |
| 2610.13177 — CompactSplat: Spatially Adaptive Gaussian Distribution for Feedforward Scene Reconstruction | [Read analysis](2610.13177.md) |
| 2610.28711 — Qwen-Audio-3.1-ASR Technical Report | [Read analysis](2610.28711.md) |
| 2610.21204 — Entertain, then Cancel: How Thinking Makes Reasoning Models Read Some and Or Literally | [Read analysis](2610.21204.md) |
| 2610.29317 — SpatialBrain: Spatial Intelligence Growing from Experience | [Read analysis](2610.29317.md) |
| 2610.29784 — Evolving with Open Worlds: Towards Recursive Self-Improvement for Future Forecasting | [Read analysis](2610.29784.md) |
| 2610.30128 — Think Harder Where It Matters: Item-Level Adaptive Recursion for Sequential Recommendation | [Read analysis](2610.30128.md) |
| 2610.29434 — RubatoCodec: Budgeted Adaptive Speech Tokenization with Streaming Decoding | [Read analysis](2610.29434.md) |
| 2610.28027 — From RL Papers to Framework Code: Inclusion and Review in Seven Open-Source Training Frameworks | [Read analysis](2610.28027.md) |
| 2610.29560 — From VLM Planners to Robotic Agents: Self-Evolving Harnesses for History-Dependent Manipulation | [Read analysis](2610.29560.md) |
| 2610.27227 — Which Agent's Skill Should Change? Group-Relative Credit Assignment for Evolving Multi-Agent Teams | [Read analysis](2610.27227.md) |
| 2610.28940 — StyleStream 2.0: Fast and Controllable Streaming Voice Style Conversion | [Read analysis](2610.28940.md) |
| 2610.28827 — WorldStream: Streaming Interactive 3D Worlds with Hierarchical Planning and Persistent State | [Read analysis](2610.28827.md) |
| 2610.28474 — Answering in the User's Variety: Calibrated Accommodation Pairs for Post-Training | [Read analysis](2610.28474.md) |
| 2610.27040 — ACE-Brain-0.6: Scaling Spatial Grounding for Physical Foundation Models | [Read analysis](2610.27040.md) |
| 2610.30090 — VX-One: Typed, Calibrated Decision Heads for Real-Time Perimeter Triage - An empirical study of unknown-attack honesty, cascade gray zones, and calibration under drift | [Read analysis](2610.30090.md) |
| 2610.28679 — VerifierBench: Benchmarking the Generation of Executable Verifiers for LLM Agents | [Read analysis](2610.28679.md) |
| 2610.09861 — Toward Part-Aware Choral Transcription with singing voice assignment | [Read analysis](2610.09861.md) |
| 2610.28905 — Hidden Messages Between Diffusion Language Model Agents: Causal Evidence for Latent Communication | [Read analysis](2610.28905.md) |
| 2610.29934 — ToM2Vec: Continuous Theory-of-Mind Tokens for Multi-Agent Coordination | [Read analysis](2610.29934.md) |
| 2610.28909 — DiffResearch: Accelerating Deep Research with Diffusion Language Models | [Read analysis](2610.28909.md) |
| 2610.23344 — Language Models Learn to Improve Language Models | [Read analysis](2610.23344.md) |
| 2610.30066 — Looped Uniform Diffusion Language Models | [Read analysis](2610.30066.md) |
| 2610.30113 — Quant-Arena: Benchmarking LLM Agents for Quantitative Trading Research | [Read analysis](2610.30113.md) |
| 2610.24771 — Design Anything, Design at Scale | [Read analysis](2610.24771.md) |
| 2610.22659 — Exploring The Empirical Privacy Landscape of Synthetic Data | [Read analysis](2610.22659.md) |
| 2610.28441 — Stratified Sparse Attention: Reducing the Sparse-to-Dense Gap at Extreme Sparsity | [Read analysis](2610.28441.md) |
| 2610.27861 — RoboCasa-Shift: Stage-Aware Robustness Evaluation of Vision-Language-Action Policies in Long-Horizon Household Manipulation | [Read analysis](2610.27861.md) |
| 2610.26397 — Bridged Self-Distillation for On-Policy Learning | [Read analysis](2610.26397.md) |
| 2610.29932 — FrontierCS 2: A Benchmark for Computer Science R&amp;D | [Read analysis](2610.29932.md) |
| 2610.27233 — MMedAgent-Plus: Scaling Multimodal Medical Agents across Modalities, Tasks and Workflows | [Read analysis](2610.27233.md) |
| 2610.26836 — Same Simulation, Different Evidence: Where Retrieved Tool Output Costs LLM Agents Accuracy | [Read analysis](2610.26836.md) |

## Current papers without a published edge

- [2610.29989](2610.29989.md)
- [2610.29997](2610.29997.md)
- [2610.21114](2610.21114.md)
- [2610.28698](2610.28698.md)
- [2610.20538](2610.20538.md)
- [2610.29722](2610.29722.md)
- [2610.28589](2610.28589.md)
- [2610.29968](2610.29968.md)
- [2610.30120](2610.30120.md)
- [2610.30108](2610.30108.md)
- [2610.27592](2610.27592.md)
- [2610.30136](2610.30136.md)
- [2610.28711](2610.28711.md)
- [2610.21204](2610.21204.md)
- [2610.29784](2610.29784.md)
- [2610.29434](2610.29434.md)
- [2610.28027](2610.28027.md)
- [2610.28940](2610.28940.md)
- [2610.28474](2610.28474.md)
- [2610.30090](2610.30090.md)
- [2610.09861](2610.09861.md)
- [2610.28905](2610.28905.md)
- [2610.28909](2610.28909.md)
- [2610.30113](2610.30113.md)
- [2610.24771](2610.24771.md)
- [2610.22659](2610.22659.md)
- [2610.28441](2610.28441.md)
- [2610.27233](2610.27233.md)
- [2610.26836](2610.26836.md)

---

[Support these research summaries on Buy Me a Coffee](https://buymeacoffee.com/vollero)
