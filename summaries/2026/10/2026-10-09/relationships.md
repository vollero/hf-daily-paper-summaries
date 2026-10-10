# Paper relationship graph — 2026-10-09

> [← Daily summary](../2026-10-09.md)

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
| [2609.38527](2609.38527.md) | [2610.09280](2610.09280.md) | Shared problem | Not directional | High |
| [2610.06100](2610.06100.md) | [2610.11794](2610.11794.md) | Shared method | Not directional | High |
| [2610.11366](2610.11366.md) | [2610.12355](2610.12355.md) | Shared method | Not directional | High |
| [2610.09639](2610.09639.md) | [2610.11366](2610.11366.md) | Shared method | Not directional | High |
| [2610.11570](2610.11570.md) | [2610.07730](2610.07730.md) | Method transfer | Source → target | Medium |
| [2610.11322](2610.11322.md) | [2610.12452](2610.12452.md) | Shared method | Not directional | High |
| [2610.12229](2610.12229.md) | [2610.12230](2610.12230.md) | Shared method | Not directional | High |
| [2609.33987](2609.33987.md) | [2610.06406](2610.06406.md) | Complementary | Not directional | Medium |
| [2610.11287](2610.11287.md) | [2610.11566](2610.11566.md) | Shared problem | Not directional | High |
| [2610.11287](2610.11287.md) | [2610.08215](2610.08215.md) | Method transfer | Source → target | Medium |
| [2610.12355](2610.12355.md) | [2610.12402](2610.12402.md) | Follow-up opportunity | Not directional | Medium |
| [2610.12459](2610.12459.md) | [2610.12468](2610.12468.md) | Shared problem | Not directional | High |

## Connections to previously seen papers

_The visual diagram is omitted because this graph is too large or dense for a readable snapshot; every edge remains in the table below._

| New paper | Previously seen paper | First seen by service | Relationship | Technical direction | Confidence |
| --- | --- | --- | --- | --- | --- |
| [2610.06496](2610.06496.md) | 2609.32520 ([Hugging Face](https://huggingface.co/papers/2609.32520) · [arXiv](https://arxiv.org/abs/2609.32520)) | 2026-10-02 | Shared problem | Not directional | High |
| [2610.11287](2610.11287.md) | 2609.36435 ([Hugging Face](https://huggingface.co/papers/2609.36435) · [arXiv](https://arxiv.org/abs/2609.36435)) | 2026-10-02 | Shared method | Not directional | Medium |
| [2610.12369](2610.12369.md) | 2609.30233 ([Hugging Face](https://huggingface.co/papers/2609.30233) · [arXiv](https://arxiv.org/abs/2609.30233)) | 2026-09-25 | Shared method | Not directional | Medium |
| [2610.11366](2610.11366.md) | 2610.02191 ([Hugging Face](https://huggingface.co/papers/2610.02191) · [arXiv](https://arxiv.org/abs/2610.02191)) | 2026-10-06 | Shared method | Not directional | Medium |
| [2610.12468](2610.12468.md) | 2609.40153 ([Hugging Face](https://huggingface.co/papers/2609.40153) · [arXiv](https://arxiv.org/abs/2609.40153)) | 2026-10-05 | Shared method | Not directional | Medium |
| [2610.11570](2610.11570.md) | 2610.01153 ([Hugging Face](https://huggingface.co/papers/2610.01153) · [arXiv](https://arxiv.org/abs/2610.01153)) | 2026-10-05 | Shared method | Not directional | Medium |
| [2610.06406](2610.06406.md) | 2609.32754 ([Hugging Face](https://huggingface.co/papers/2609.32754) · [arXiv](https://arxiv.org/abs/2609.32754)) | 2026-09-29 | Shared method | Not directional | Medium |
| [2609.33987](2609.33987.md) | 2609.40111 ([Hugging Face](https://huggingface.co/papers/2609.40111) · [arXiv](https://arxiv.org/abs/2609.40111)) | 2026-10-01 | Complementary | Not directional | Medium |
| [2609.39068](2609.39068.md) | 2609.04971 ([Hugging Face](https://huggingface.co/papers/2609.04971) · [arXiv](https://arxiv.org/abs/2609.04971)) | 2026-09-09 | Enabling dependency | Previous → new | Medium |
| [2610.04875](2610.04875.md) | 2609.26796 ([Hugging Face](https://huggingface.co/papers/2609.26796) · [arXiv](https://arxiv.org/abs/2609.26796)) | 2026-09-23 | Complementary | Not directional | Medium |
| [2609.38173](2609.38173.md) | 2609.19138 ([Hugging Face](https://huggingface.co/papers/2609.19138) · [arXiv](https://arxiv.org/abs/2609.19138)) | 2026-09-17 | Shared problem | Not directional | Medium |
| [2610.11322](2610.11322.md) | 2610.07969 ([Hugging Face](https://huggingface.co/papers/2610.07969) · [arXiv](https://arxiv.org/abs/2610.07969)) | 2026-10-07 | Enabling dependency | New → previous | Medium |

## Current paper key

| Paper | Analysis |
| --- | --- |
| 2610.12374 — AgentGarten: Code Worlds for Evolving Agents | [Read analysis](2610.12374.md) |
| 2610.12242 — TokenRouter: Efficient Serving System for Token-Level LLM Routing | [Read analysis](2610.12242.md) |
| 2610.08215 — Learn2Play Bench: How Well Do LLM Agents Learn from Experience in Unfamiliar Environments? | [Read analysis](2610.08215.md) |
| 2610.06100 — From Traces to Agentic Worlds: Agentic Language World Models for Interactive Environment Simulation | [Read analysis](2610.06100.md) |
| 2610.12126 — SuperNav: An Agentic Navigation System for Any Task in Any Scene | [Read analysis](2610.12126.md) |
| 2610.11959 — MiMo-V2.6: Scaling Reinforcement Learning Towards Self-Improvement | [Read analysis](2610.11959.md) |
| 2610.12299 — Multi-Agent Egocentric World Model with Fine-Grained Embodied Interaction | [Read analysis](2610.12299.md) |
| 2609.38173 — In-context Robot Learning Made Simple: A Democratized Recipe for Manipulation Tasks | [Read analysis](2609.38173.md) |
| 2610.12468 — DreamTrue: Action-Faithful Robot World Model with Counterfactual Post-Training | [Read analysis](2610.12468.md) |
| 2610.12421 — Beyond Spatio-Temporal Priors: A Generalizable Approach for Dense Correspondence Matching | [Read analysis](2610.12421.md) |
| 2610.09087 — U-Space: Uncovering When and Why Uncertainty Arises in Language Models | [Read analysis](2610.09087.md) |
| 2610.12461 — OuroWorld: Bringing Any 3D World Alive as Diverse, Endlessly Looping 3D Cinemagraphs | [Read analysis](2610.12461.md) |
| 2610.12289 — TestPrism: Rethinking Test Evaluation Beyond a Single Reference | [Read analysis](2610.12289.md) |
| 2610.06801 — MC-Sparse: Deconstructing and Closing the Dense-Sparse Attention Gap in Diffusion Transformers | [Read analysis](2610.06801.md) |
| 2610.11794 — Memento 3: Model-Based Recursive Self-Improvement through Reflective Rulebooks | [Read analysis](2610.11794.md) |
| 2610.02967 — Post-Training Frontier Text-to-Image Models by Composing Preference and Rubric Rewards | [Read analysis](2610.02967.md) |
| 2610.12327 — SparseDecoding: Decoding-Aware Pruning for Accurate and Efficient LLM Inference | [Read analysis](2610.12327.md) |
| 2610.12442 — LEGO: A Lifting-Free Approach for Exocentric-to-Egocentric Video Generation | [Read analysis](2610.12442.md) |
| 2610.12419 — OneSearch-VL: Unified Multimodal Deep Research Agent for Image and Video | [Read analysis](2610.12419.md) |
| 2610.12343 — Reasoning-Informed Visual Editing | [Read analysis](2610.12343.md) |
| 2501.09223 — Foundations of Large Language Models | [Read analysis](2501.09223.md) |
| 2610.06406 — What Did the Agent Actually Do? Evidence-Grounded Oversight for Long-Horizon Agents | [Read analysis](2610.06406.md) |
| 2609.39068 — SparseEngine: Sparse-First Inference Engine | [Read analysis](2609.39068.md) |
| 2610.12229 — VibeEdit: Image Editing with Canvas Instructions | [Read analysis](2610.12229.md) |
| 2610.07730 — SanSi: A Looped Typed Decision Model for System 1.5 Thinking | [Read analysis](2610.07730.md) |
| 2610.11322 — USDCraft: Geometrically Grounded Programmatic Modeling of Articulated 3D Assets for Simulation | [Read analysis](2610.11322.md) |
| 2610.12458 — OmniCapBench: A Deep-Structured Evaluation Framework for Fine-Grained Audio-Visual Captioning | [Read analysis](2610.12458.md) |
| 2610.12369 — Embodied Turing Machines: Stateful Code for Robot Recursive Self-Improvement | [Read analysis](2610.12369.md) |
| 2610.12403 — ViSkill: Reinforcing VLM Agents with Evolving Visual-Native Skills | [Read analysis](2610.12403.md) |
| 2610.11251 — V-CoLA: Vision Token Compression with Linear Attention | [Read analysis](2610.11251.md) |
| 2609.35433 — ReSPO: Reshaped Sequence Policy Optimization for Gradient Starvation in Off-Policy Learning | [Read analysis](2609.35433.md) |
| 2610.04977 — Do LLMs Understand Sequential Structure? A Controlled Study of Inference and Generation | [Read analysis](2610.04977.md) |
| 2610.11366 — SpatialOPSD: Self-Distilling Spatial Intelligence from Verified Coding Agent Traces | [Read analysis](2610.11366.md) |
| 2610.12230 — From Prompting to Composing: A Spatial Canvas Interface for Poster Generation | [Read analysis](2610.12230.md) |
| 2610.03858 — Retrieval-Centric Deep Learning in Growing Nonparametric Neural Networks | [Read analysis](2610.03858.md) |
| 2609.33987 — Opera: A Verbal Critic Framework for Long-horizon Coding Agents | [Read analysis](2609.33987.md) |
| 2610.12402 — SpaceCast-Bench: Evaluating Predictive Spatial Reasoning in Vision-Language Models | [Read analysis](2610.12402.md) |
| 2610.11816 — Chaos in the Text: Revealing the Modality Preference in Mixed-Modality Retrievers | [Read analysis](2610.11816.md) |
| 2610.08927 — Can AI Agents Make Open-Ended Scientific Discovery? Evidence from Station | [Read analysis](2610.08927.md) |
| 2610.12183 — A Closer Look at Agentic BBO: Benchmarking LLM Agents for Black-Box Optimization | [Read analysis](2610.12183.md) |
| 2610.11287 — REMORY: Learning Residual Memory for Context Compaction | [Read analysis](2610.11287.md) |
| 2610.12459 — WorldGuide: Goal-Directed Video World Model for Procedural Task Execution | [Read analysis](2610.12459.md) |
| 2610.11570 — Scaling to Tens of Thousands of Test-Time Iterations with Loop-Native Attention Residuals | [Read analysis](2610.11570.md) |
| 2610.10549 — Synthesis Through Simulation: Generating Coherent Enterprise Data via Scalable Agent-System Interaction | [Read analysis](2610.10549.md) |
| 2610.11566 — Incremental Open-Ended Deep Research with Structured Harness | [Read analysis](2610.11566.md) |
| 2610.12448 — One Block, Multiple Depths: Recurrent Vision Transformers with Depth-Programmed Experts | [Read analysis](2610.12448.md) |
| 2610.12399 — SpaceFlow: Locally Controllable 3D Generation | [Read analysis](2610.12399.md) |
| 2610.12452 — BrickBench: Evaluating Agentic Brick Design | [Read analysis](2610.12452.md) |
| 2610.12360 — Accurate but Not Humble: Evaluating Epistemic Humility in LLM Agents under Knowledge Conflict | [Read analysis](2610.12360.md) |
| 2609.35855 — Mara Chain: Rethinking Failure as a Stepping Stone for AI System Auto-Evolution | [Read analysis](2609.35855.md) |
| 2610.09146 — Frozen Models, Evolving Expertise: Model-Agnostic Learning from Deployment Experience for Multimodal Medical AI | [Read analysis](2610.09146.md) |
| 2610.04875 — SpecFold: Folding Multi-Branch Redundancy for Faster Speculative Decoding in Diffusion Language Models | [Read analysis](2610.04875.md) |
| 2610.12423 — Pumpire: Unified Benchmark for Metric Distance Estimation | [Read analysis](2610.12423.md) |
| 2610.03136 — Investigating the Role of Reasoning-Language Alignment in Monolingual Retrieval-Augmented Generation | [Read analysis](2610.03136.md) |
| 2610.09059 — EDiS: Edge Disjoint Subgraph Sparsification Framework for Graph Neural Networks | [Read analysis](2610.09059.md) |
| 2610.08917 — CARE: Certifying Acceleration for Vision-Language-Action Inference | [Read analysis](2610.08917.md) |
| 2610.09639 — On-Policy Distillation Teaches New Skills but Not New Knowledge | [Read analysis](2610.09639.md) |
| 2610.11169 — Skill Constellations: Tracing the Supply Chain of Agent Skills on GitHub | [Read analysis](2610.11169.md) |
| 2610.11975 — Predicting Cable Dynamics with Physical Attention Bias | [Read analysis](2610.11975.md) |
| 2606.03335 — A GPU-Parallel Framework for Heterogeneous Multi-Task Reinforcement Learning | [Read analysis](2606.03335.md) |
| 2610.08585 — Incidental information contaminates patient notes and disrupts clinical reasoning in large language models | [Read analysis](2610.08585.md) |
| 2610.06496 — You Changed Your Mind, The Model Didn't: Demystifying Intent in Multi-Turn Dialogue | [Read analysis](2610.06496.md) |
| 2609.34344 — Learning to Steer, Steering to See: Unveiling the Geometry of RLVR in Large Language Models via Trainable Vectors | [Read analysis](2609.34344.md) |
| 2605.22949 — MARGIN: Runtime Confidence Calibration for Multi-Agent Foundation Model Coordination | [Read analysis](2605.22949.md) |
| 2610.12355 — Distilling Routed 3D Privilege for Spatial Reasoning in Vision-Language Models | [Read analysis](2610.12355.md) |
| 2610.11216 — The Lattice of Transition Laws | [Read analysis](2610.11216.md) |
| 2609.38527 — Behavioral Persistence and Incomplete Functional Transfer of Co-evolved Communication in Evolutionary Robotics | [Read analysis](2609.38527.md) |
| 2610.09280 — Evaluating the Transfer of Co-Evolved Communication from 2D to 3D Simulation | [Read analysis](2610.09280.md) |
| 2610.10355 — MIRA: A Musical Intent Refinement Agent for Aligning Text-to-Music Generation with User Intent | [Read analysis](2610.10355.md) |
| 2609.31507 — SatNav: A Scalable Benchmark for Long-Horizon UAV Vision-Language Navigation from Satellite Imagery | [Read analysis](2609.31507.md) |
| 2610.08941 — SPW-Nav: A Streaming Panoramic World Model for Language-Guided Navigation | [Read analysis](2610.08941.md) |
| 2610.02959 — TerraVis: Towards Evaluation of World-Grounded Visual Consistency in Text-to-Image Generation via MLLM Workflows | [Read analysis](2610.02959.md) |

## Current papers without a published edge

- [2610.12374](2610.12374.md)
- [2610.12242](2610.12242.md)
- [2610.12126](2610.12126.md)
- [2610.11959](2610.11959.md)
- [2610.12299](2610.12299.md)
- [2610.12421](2610.12421.md)
- [2610.09087](2610.09087.md)
- [2610.12461](2610.12461.md)
- [2610.12289](2610.12289.md)
- [2610.06801](2610.06801.md)
- [2610.02967](2610.02967.md)
- [2610.12327](2610.12327.md)
- [2610.12442](2610.12442.md)
- [2610.12419](2610.12419.md)
- [2610.12343](2610.12343.md)
- [2501.09223](2501.09223.md)
- [2610.12458](2610.12458.md)
- [2610.12403](2610.12403.md)
- [2610.11251](2610.11251.md)
- [2609.35433](2609.35433.md)
- [2610.04977](2610.04977.md)
- [2610.03858](2610.03858.md)
- [2610.11816](2610.11816.md)
- [2610.08927](2610.08927.md)
- [2610.12183](2610.12183.md)
- [2610.10549](2610.10549.md)
- [2610.12448](2610.12448.md)
- [2610.12399](2610.12399.md)
- [2610.12360](2610.12360.md)
- [2609.35855](2609.35855.md)
- [2610.09146](2610.09146.md)
- [2610.12423](2610.12423.md)
- [2610.03136](2610.03136.md)
- [2610.09059](2610.09059.md)
- [2610.08917](2610.08917.md)
- [2610.11169](2610.11169.md)
- [2610.11975](2610.11975.md)
- [2606.03335](2606.03335.md)
- [2610.08585](2610.08585.md)
- [2609.34344](2609.34344.md)
- [2605.22949](2605.22949.md)
- [2610.11216](2610.11216.md)
- [2610.10355](2610.10355.md)
- [2609.31507](2609.31507.md)
- [2610.08941](2610.08941.md)
- [2610.02959](2610.02959.md)

---

[Support these research summaries on Buy Me a Coffee](https://buymeacoffee.com/vollero)
