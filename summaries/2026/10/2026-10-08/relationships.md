# Paper relationship graph — 2026-10-08

> [← Daily summary](../2026-10-08.md)

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
| [2610.03799](2610.03799.md) | [2610.09127](2610.09127.md) | Shared method | Not directional | High |
| [2610.09832](2610.09832.md) | [2610.10164](2610.10164.md) | Shared problem | Not directional | High |
| [2609.38562](2609.38562.md) | [2610.10429](2610.10429.md) | Shared evaluation | Not directional | Medium |
| [2609.36995](2609.36995.md) | [2609.38562](2609.38562.md) | Shared method | Not directional | High |
| [2610.10429](2610.10429.md) | [2610.10528](2610.10528.md) | Method transfer | Source → target | Medium |
| [2610.10497](2610.10497.md) | [2610.10524](2610.10524.md) | Shared problem | Not directional | High |
| [2609.39306](2609.39306.md) | [2610.08077](2610.08077.md) | Shared method | Not directional | High |
| [2610.07862](2610.07862.md) | [2610.08995](2610.08995.md) | Shared method | Not directional | High |
| [2610.08902](2610.08902.md) | [2610.08995](2610.08995.md) | Method transfer | Source → target | Medium |
| [2610.10388](2610.10388.md) | [2610.10409](2610.10409.md) | Shared problem | Not directional | High |
| [2610.04012](2610.04012.md) | [2610.10444](2610.10444.md) | Shared problem | Not directional | High |
| [2610.09823](2610.09823.md) | [2610.10047](2610.10047.md) | Shared problem | Not directional | Medium |

## Connections to previously seen papers

_The visual diagram is omitted because this graph is too large or dense for a readable snapshot; every edge remains in the table below._

| New paper | Previously seen paper | First seen by service | Relationship | Technical direction | Confidence |
| --- | --- | --- | --- | --- | --- |
| [2610.05336](2610.05336.md) | 2609.33757 ([Hugging Face](https://huggingface.co/papers/2609.33757) · [arXiv](https://arxiv.org/abs/2609.33757)) | 2026-09-29 | Enabling dependency | New → previous | High |
| [2610.07250](2610.07250.md) | 2609.38721 ([Hugging Face](https://huggingface.co/papers/2609.38721) · [arXiv](https://arxiv.org/abs/2609.38721)) | 2026-10-01 | Shared method | Not directional | High |
| [2610.08995](2610.08995.md) | 2609.22966 ([Hugging Face](https://huggingface.co/papers/2609.22966) · [arXiv](https://arxiv.org/abs/2609.22966)) | 2026-09-22 | Shared method | Not directional | High |
| [2610.10444](2610.10444.md) | 2609.33326 ([Hugging Face](https://huggingface.co/papers/2609.33326) · [arXiv](https://arxiv.org/abs/2609.33326)) | 2026-09-30 | Shared method | Not directional | High |
| [2609.40360](2609.40360.md) | 2609.33781 ([Hugging Face](https://huggingface.co/papers/2609.33781) · [arXiv](https://arxiv.org/abs/2609.33781)) | 2026-09-29 | Shared problem | Not directional | High |
| [2610.03185](2610.03185.md) | 2609.35210 ([Hugging Face](https://huggingface.co/papers/2609.35210) · [arXiv](https://arxiv.org/abs/2609.35210)) | 2026-09-30 | Complementary | Not directional | High |
| [2610.10460](2610.10460.md) | 2609.33791 ([Hugging Face](https://huggingface.co/papers/2609.33791) · [arXiv](https://arxiv.org/abs/2609.33791)) | 2026-09-29 | Shared problem | Not directional | High |
| [2609.38562](2609.38562.md) | 2609.37925 ([Hugging Face](https://huggingface.co/papers/2609.37925) · [arXiv](https://arxiv.org/abs/2609.37925)) | 2026-10-05 | Shared problem | Not directional | High |
| [2609.38169](2609.38169.md) | 2609.26425 ([Hugging Face](https://huggingface.co/papers/2609.26425) · [arXiv](https://arxiv.org/abs/2609.26425)) | 2026-10-05 | Shared method | Not directional | High |
| [2610.10539](2610.10539.md) | 2609.05594 ([Hugging Face](https://huggingface.co/papers/2609.05594) · [arXiv](https://arxiv.org/abs/2609.05594)) | 2026-09-09 | Complementary | Not directional | Medium |
| [2610.04722](2610.04722.md) | 2609.33253 ([Hugging Face](https://huggingface.co/papers/2609.33253) · [arXiv](https://arxiv.org/abs/2609.33253)) | 2026-09-29 | Shared problem | Not directional | High |
| [2609.39306](2609.39306.md) | 2609.36864 ([Hugging Face](https://huggingface.co/papers/2609.36864) · [arXiv](https://arxiv.org/abs/2609.36864)) | 2026-09-30 | Shared method | Not directional | High |

## Current paper key

| Paper | Analysis |
| --- | --- |
| 2609.38169 — STEPQuant: When and Where Errors Matter in Delta-Rule Recurrent State Quantization | [Read analysis](2609.38169.md) |
| 2610.10528 — Long-WAM: Scaling the Context of World-Action Models | [Read analysis](2610.10528.md) |
| 2610.08699 — nanoMuse: An Open-Source Personal Agent for Every Device You Own | [Read analysis](2610.08699.md) |
| 2610.08621 — Recursive Game Creator: An Agentic Product-Level Experience-Oriented Game Harness | [Read analysis](2610.08621.md) |
| 2610.09823 — UltraText Bench: A Comprehensive Bilingual Benchmark for Evaluating Visual Text Rendering in Image Generation | [Read analysis](2610.09823.md) |
| 2610.07967 — DecepEval: A Benchmark for Evaluating Deception in LLM Agents | [Read analysis](2610.07967.md) |
| 2610.10524 — GRACE: Generation-aware latent compression for efficient video generation | [Read analysis](2610.10524.md) |
| 2610.04299 — Questioning the Questions: Sustaining Self-Evolution in Reasoning Models | [Read analysis](2610.04299.md) |
| 2610.06293 — VepAgent: Bridging Causal-Transition via Tool-Augmented Reinforcement Learning for Video Event Prediction | [Read analysis](2610.06293.md) |
| 2610.10429 — SGF+: Decoupling Gradient Flows for Autoregressive Video Generation | [Read analysis](2610.10429.md) |
| 2610.02054 — UniWAM: Unified World-Action Model | [Read analysis](2610.02054.md) |
| 2610.08077 — Self-Retrospection Distillation: Turning Post-hoc Experiences into Prior Foresight | [Read analysis](2610.08077.md) |
| 2609.40360 — Semifactual Credit-Augmented Policy Optimization | [Read analysis](2609.40360.md) |
| 2610.10539 — Tetris3D: 3D Scene Generation With Objects That Fit Together | [Read analysis](2610.10539.md) |
| 2610.10444 — RunningTab: Direct Workspace Interaction with Environment-Side Tabs | [Read analysis](2610.10444.md) |
| 2610.08760 — WorldSonus: Bringing Sound to Worlds | [Read analysis](2610.08760.md) |
| 2609.39306 — ReSAIL: Mitigating Collapse in Iterative Agent Self-Distillation | [Read analysis](2609.39306.md) |
| 2610.10114 — Mechanics of Long-Context Hybrid Models Part 1.1: From Hybrid Attention to Hybrid Position | [Read analysis](2610.10114.md) |
| 2610.10409 — RobotWorld: Benchmarking Multimodal Agents for Robot Use Across Diverse Tasks and Embodiments | [Read analysis](2610.10409.md) |
| 2610.03185 — Gains and Collapse in On-Policy Distillation:A Reinforcement Learning Perspective | [Read analysis](2610.03185.md) |
| 2610.08995 — PhysEvo: Astra Can Act, Let It | [Read analysis](2610.08995.md) |
| 2610.07591 — Recurrent Looped Transformer | [Read analysis](2610.07591.md) |
| 2609.33678 — SWE-Game: Can Coding Agents Build the Games We Want? | [Read analysis](2609.33678.md) |
| 2610.00994 — VIEScore2: Unified Image Evaluation with Spatially Grounded Explanations | [Read analysis](2610.00994.md) |
| 2610.04722 — NAMVIS: Next-Scale Autoregressive Multi-View Image Synthesis | [Read analysis](2610.04722.md) |
| 2610.05034 — Agentic RAG Evaluation: Budget Allocation Across Questions, Trajectories, and Reads | [Read analysis](2610.05034.md) |
| 2610.08963 — On KL-Regularized Policy Optimization | [Read analysis](2610.08963.md) |
| 2610.09920 — Inverting Multi-Vector Visual Document Indices | [Read analysis](2610.09920.md) |
| 2610.10437 — Q-Learning with Scalar Adjoint Matching | [Read analysis](2610.10437.md) |
| 2610.07226 — Minimal Witness Reinforcement Learning | [Read analysis](2610.07226.md) |
| 2610.03036 — WebFovea: When the Model Is Right but the Click Is Wrong -- Reliable Round Trips for Vision-Based Web Agents on Live Websites | [Read analysis](2610.03036.md) |
| 2610.09484 — MIMESIS: Learning User Simulators as Training Environments for Interactive Agents | [Read analysis](2610.09484.md) |
| 2610.09684 — From Pareto to Preference: Personalized Test-Time Scaling via Amortized Agentic Policy Discovery | [Read analysis](2610.09684.md) |
| 2610.07874 — On-Policy Distillation with Negative-Policy Rollouts | [Read analysis](2610.07874.md) |
| 2610.10047 — AdSpark: A Large-Scale Dataset and Benchmark for Product-Centric Advertisement Video Generation | [Read analysis](2610.10047.md) |
| 2610.05289 — Mobile-4DGS: Unified Static-Dynamic Real-time Mobile Gaussian Splatting | [Read analysis](2610.05289.md) |
| 2610.10497 — QuadTok: Quadtree Visual Tokenizer for Autoregressive Image Generation | [Read analysis](2610.10497.md) |
| 2610.07659 — DLoop: Looped Speculative Decoding | [Read analysis](2610.07659.md) |
| 2610.09127 — CADFather: Autonomous CAD Reconstruction through Coordinated Tool Use | [Read analysis](2610.09127.md) |
| 2610.07250 — Internalizing Agent Experience into Diffusion Model Weights via On-Policy Context Distillation | [Read analysis](2610.07250.md) |
| 2610.07862 — A self-learning scientific agent for X-ray diffraction | [Read analysis](2610.07862.md) |
| 2610.06505 — Improving Proactive AI Assistance with Hierarchical Procedural Understanding | [Read analysis](2610.06505.md) |
| 2610.10460 — Composing What Each Teacher Learned: Multi-Teacher On-Policy Distillation through Teacher-Relative Shifts | [Read analysis](2610.10460.md) |
| 2609.33659 — Learning Multimodal Embeddings with Evidence-Aligned Readout | [Read analysis](2609.33659.md) |
| 2610.09450 — Iris-3B: Going Beyond the Latent with Pixel-Space Diffusion Training, Conversion and Fine-Tuning | [Read analysis](2610.09450.md) |
| 2610.05336 — SheetSage2: Coherent Lead-Sheet Transcription with Synthetic Supervision | [Read analysis](2610.05336.md) |
| 2610.09832 — SkillForge: Co-Evolving Skills and Agents via Dynamic Skill Lifecycles | [Read analysis](2610.09832.md) |
| 2610.10164 — UniSkill: Learning Actor-Aligned Skill Proposals for an Evolving Policy | [Read analysis](2610.10164.md) |
| 2610.02396 — Inherit-MAS: Test-Time Evolution of Multi-Agent Systems through Workflow and Execution Inheritance | [Read analysis](2610.02396.md) |
| 2610.03799 — StepCAD: Mesh-to-CAD Code Generation via LLM Policy and Geometry-Guided Search | [Read analysis](2610.03799.md) |
| 2610.10533 — EngramEdit: Decoupled Knowledge Updates in LLMs through Conditional Memory | [Read analysis](2610.10533.md) |
| 2610.09457 — DSReg: Provably Recovering Individual World Latents without Reconstruction | [Read analysis](2610.09457.md) |
| 2610.05324 — CoDance: Learning Reactive and Compliant Human-Humanoid Interaction from Video | [Read analysis](2610.05324.md) |
| 2609.36995 — Salt++: Context-Aligned Post-Training for Few-Step Streaming Multimodal Generation | [Read analysis](2609.36995.md) |
| 2610.10388 — RoboQuest: Generalist Physical Agents that Search, Inspect and Test | [Read analysis](2610.10388.md) |
| 2610.10845 — Real Long-Term Memory for AI: A 50-Million-Token Window That Is Faster and Cheaper Than Recompute | [Read analysis](2610.10845.md) |
| 2610.08902 — Agent Plasticity: Measuring Self-Improvement Through Experience | [Read analysis](2610.08902.md) |
| 2610.10515 — RoboJEPA: Scaling Robotic Latent World Models | [Read analysis](2610.10515.md) |
| 2610.04012 — Beyond the Parameter Monolith: Reconstructive Memories, Executable Skills, and Residual Assembly for Language Models | [Read analysis](2610.04012.md) |
| 2610.05003 — How corner is a corner case? Percentile control for highway scenario generation | [Read analysis](2610.05003.md) |
| 2610.07258 — Lineage-Aware Memory Governance: A Derivation-Gated Framework for Privacy-Preserving Column-Level Access Control in Enterprise AI Agents | [Read analysis](2610.07258.md) |
| 2609.38466 — PAMI: Part Anchored Motion for Text to Human-Object Interaction Generation | [Read analysis](2609.38466.md) |
| 2610.09683 — System Switch: When Should a Fast Decision Model Stop and Think? | [Read analysis](2610.09683.md) |
| 2605.09742 — TIDES: Implicit Time-Awareness in Selective State Space Models | [Read analysis](2605.09742.md) |
| 2610.02832 — FastOPD: On-Policy Distillation for Lightweight VLA Deployment | [Read analysis](2610.02832.md) |
| 2610.08884 — Task-Sufficient Contraction: Source Selection for Machine Information Interfaces | [Read analysis](2610.08884.md) |
| 2610.02368 — Rethinking World-Action Model for Compositional and In-Context Robotic Manipulation | [Read analysis](2610.02368.md) |
| 2609.38562 — LongTake: Learning to Sustain Dynamics in Long-Horizon Video Generation | [Read analysis](2609.38562.md) |
| 2609.30541 — AutoResearch at Production Scale: Failure Modes and a Multi-Agent Framework | [Read analysis](2609.30541.md) |
| 2609.38680 — ReGain: Restoring Subject Fidelity in Personalization on Synthetic Images | [Read analysis](2609.38680.md) |
| 2610.09228 — Co-Evolving Robot Orchestrators and Policies through Deployment | [Read analysis](2610.09228.md) |

## Current papers without a published edge

- [2610.08699](2610.08699.md)
- [2610.08621](2610.08621.md)
- [2610.07967](2610.07967.md)
- [2610.04299](2610.04299.md)
- [2610.06293](2610.06293.md)
- [2610.02054](2610.02054.md)
- [2610.08760](2610.08760.md)
- [2610.10114](2610.10114.md)
- [2610.07591](2610.07591.md)
- [2609.33678](2609.33678.md)
- [2610.00994](2610.00994.md)
- [2610.05034](2610.05034.md)
- [2610.08963](2610.08963.md)
- [2610.09920](2610.09920.md)
- [2610.10437](2610.10437.md)
- [2610.07226](2610.07226.md)
- [2610.03036](2610.03036.md)
- [2610.09484](2610.09484.md)
- [2610.09684](2610.09684.md)
- [2610.07874](2610.07874.md)
- [2610.05289](2610.05289.md)
- [2610.07659](2610.07659.md)
- [2610.06505](2610.06505.md)
- [2609.33659](2609.33659.md)
- [2610.09450](2610.09450.md)
- [2610.02396](2610.02396.md)
- [2610.10533](2610.10533.md)
- [2610.09457](2610.09457.md)
- [2610.05324](2610.05324.md)
- [2610.10845](2610.10845.md)
- [2610.10515](2610.10515.md)
- [2610.05003](2610.05003.md)
- [2610.07258](2610.07258.md)
- [2609.38466](2609.38466.md)
- [2610.09683](2610.09683.md)
- [2605.09742](2605.09742.md)
- [2610.02832](2610.02832.md)
- [2610.08884](2610.08884.md)
- [2610.02368](2610.02368.md)
- [2609.30541](2609.30541.md)
- [2609.38680](2609.38680.md)
- [2610.09228](2610.09228.md)

---

[Support these research summaries on Buy Me a Coffee](https://buymeacoffee.com/vollero)
