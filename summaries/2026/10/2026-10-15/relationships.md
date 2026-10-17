# Paper relationship graph — 2026-10-15

> [← Daily summary](../2026-10-15.md)

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
| [2606.24472](2606.24472.md) | [2610.15112](2610.15112.md) | Shared method | Not directional | High |
| [2610.02089](2610.02089.md) | [2610.15425](2610.15425.md) | Shared problem | Not directional | High |
| [2610.18755](2610.18755.md) | [2610.19525](2610.19525.md) | Shared problem | Not directional | High |
| [2610.19551](2610.19551.md) | [2610.18284](2610.18284.md) | Enabling dependency | Source → target | Medium |
| [2610.18072](2610.18072.md) | [2610.20137](2610.20137.md) | Shared problem | Not directional | High |
| [2610.19726](2610.19726.md) | [2610.20571](2610.20571.md) | Shared problem | Not directional | High |
| [2610.15715](2610.15715.md) | [2610.17191](2610.17191.md) | Shared limitation | Not directional | High |
| [2610.17016](2610.17016.md) | [2610.17309](2610.17309.md) | Enabling dependency | Source → target | Medium |
| [2610.18638](2610.18638.md) | [2610.18598](2610.18598.md) | Follow-up opportunity | Not directional | Medium |
| [2610.17893](2610.17893.md) | [2610.20195](2610.20195.md) | Shared problem | Not directional | High |
| [2610.17301](2610.17301.md) | [2610.13623](2610.13623.md) | Method transfer | Source → target | Medium |
| [2610.20516](2610.20516.md) | [2610.20572](2610.20572.md) | Shared method | Not directional | High |

## Connections to previously seen papers

_The visual diagram is omitted because this graph is too large or dense for a readable snapshot; every edge remains in the table below._

| New paper | Previously seen paper | First seen by service | Relationship | Technical direction | Confidence |
| --- | --- | --- | --- | --- | --- |
| [2606.24472](2606.24472.md) | 2610.12099 ([Hugging Face](https://huggingface.co/papers/2610.12099) · [arXiv](https://arxiv.org/abs/2610.12099)) | 2026-10-13 | Shared method | Not directional | Medium |
| [2610.10787](2610.10787.md) | 2609.34276 ([Hugging Face](https://huggingface.co/papers/2609.34276) · [arXiv](https://arxiv.org/abs/2609.34276)) | 2026-10-01 | Shared method | Not directional | Medium |
| [2610.13521](2610.13521.md) | 2609.30837 ([Hugging Face](https://huggingface.co/papers/2609.30837) · [arXiv](https://arxiv.org/abs/2609.30837)) | 2026-09-28 | Shared problem | Not directional | Medium |
| [2610.14020](2610.14020.md) | 2610.12459 ([Hugging Face](https://huggingface.co/papers/2610.12459) · [arXiv](https://arxiv.org/abs/2610.12459)) | 2026-10-09 | Complementary | Not directional | Medium |
| [2610.14216](2610.14216.md) | 2609.06052 ([Hugging Face](https://huggingface.co/papers/2609.06052) · [arXiv](https://arxiv.org/abs/2609.06052)) | 2026-09-22 | Complementary | Not directional | Medium |
| [2610.16338](2610.16338.md) | 2610.00825 ([Hugging Face](https://huggingface.co/papers/2610.00825) · [arXiv](https://arxiv.org/abs/2610.00825)) | 2026-10-02 | Shared problem | Not directional | Medium |
| [2610.17893](2610.17893.md) | 2610.16117 ([Hugging Face](https://huggingface.co/papers/2610.16117) · [arXiv](https://arxiv.org/abs/2610.16117)) | 2026-10-14 | Follow-up opportunity | Not directional | Medium |
| [2610.19422](2610.19422.md) | 2609.32400 ([Hugging Face](https://huggingface.co/papers/2609.32400) · [arXiv](https://arxiv.org/abs/2609.32400)) | 2026-09-29 | Shared method | Not directional | Medium |
| [2610.19560](2610.19560.md) | 2610.09484 ([Hugging Face](https://huggingface.co/papers/2610.09484) · [arXiv](https://arxiv.org/abs/2610.09484)) | 2026-10-08 | Shared problem | Not directional | Medium |
| [2610.19975](2610.19975.md) | 2610.12582 ([Hugging Face](https://huggingface.co/papers/2610.12582) · [arXiv](https://arxiv.org/abs/2610.12582)) | 2026-10-12 | Shared method | Not directional | Medium |
| [2610.20344](2610.20344.md) | 2610.13361 ([Hugging Face](https://huggingface.co/papers/2610.13361) · [arXiv](https://arxiv.org/abs/2610.13361)) | 2026-10-13 | Shared evaluation | Not directional | Medium |
| [2610.20572](2610.20572.md) | 2609.36864 ([Hugging Face](https://huggingface.co/papers/2609.36864) · [arXiv](https://arxiv.org/abs/2609.36864)) | 2026-09-30 | Shared method | Not directional | Medium |

## Current paper key

| Paper | Analysis |
| --- | --- |
| 2610.20571 — Any Time, Any Space: A World-State-Centric Framework for Agentic Video Generation | [Read analysis](2610.20571.md) |
| 2610.20584 — Player-1: Learning to Play from Synthetic Experience | [Read analysis](2610.20584.md) |
| 2610.13521 — Beyond Domain-Routed Supervision: Cross-Teacher Guarding for Multi-Teacher On-Policy Distillation | [Read analysis](2610.13521.md) |
| 2610.20344 — Doc2Harness: Benchmarking LLMs on Long-Horizon Harness Engineering of Coding Agents | [Read analysis](2610.20344.md) |
| 2610.19789 — More Methods, Better Agents? A Reality Check on Self-Distillation in Agentic Reinforcement Learning | [Read analysis](2610.19789.md) |
| 2610.20572 — Recovering Reliable Supervision via Critique-Guided On-Policy Distillation | [Read analysis](2610.20572.md) |
| 2610.17771 — Many Right Answers, One Training Example: Removing Responder Noise from GRPO for LLM Recommenders | [Read analysis](2610.17771.md) |
| 2610.20431 — SwarmRSI: Recursive Self-Improvement through Evolving Scientific Agent Swarm | [Read analysis](2610.20431.md) |
| 2610.20399 — Cortex: Consolidating Context into Parametric Memory | [Read analysis](2610.20399.md) |
| 2610.19975 — LatentLoop: Scaling Looped MoE Models with Asymmetric Compute Allocation | [Read analysis](2610.19975.md) |
| 2610.19820 — ActionOPD: Distilling Decisions, Not Tokens | [Read analysis](2610.19820.md) |
| 2610.19366 — Seeing, Maintaining, and Learning: The Evolution of Multimodal Agent Memory | [Read analysis](2610.19366.md) |
| 2610.18072 — LensErase: A Foundation Model for Erase Anything | [Read analysis](2610.18072.md) |
| 2610.14448 — KV4-RL: Unlocking Faster Asynchronous Rollouts for RLVR with INT4 KV Cache Quantization | [Read analysis](2610.14448.md) |
| 2610.19128 — CLASHarness: Benchmarking Multi-Agent Conflict in Computer Use via a Controllable and Verifiable Generation Pipeline | [Read analysis](2610.19128.md) |
| 2610.20442 — Towards Agentic Robots: Model, Data, Environment, and Harness | [Read analysis](2610.20442.md) |
| 2610.19698 — RuleTrek: Benchmarking Agentic Rule Reasoning in Complex Scenarios | [Read analysis](2610.19698.md) |
| 2610.18861 — Hybrid Reasoning Agents | [Read analysis](2610.18861.md) |
| 2610.14270 — The Thinking Leakage in Reinforcement Learning for LLMs | [Read analysis](2610.14270.md) |
| 2610.02089 — HumanoidToolBench: Benchmarking Humanoid Tool Use from Selection to Mobile Execution | [Read analysis](2610.02089.md) |
| 2610.18097 — APT: Feedback-Driven Agentic Post-Training for Text-to-Image Generation | [Read analysis](2610.18097.md) |
| 2610.04781 — Super-Resolution in The Right Latent Space: A Frozen Vision-Foundation Substrate | [Read analysis](2610.04781.md) |
| 2610.19118 — DecisionRobust: Benchmarking Robustness for JEV Style Decision Models Across Text and Vision | [Read analysis](2610.19118.md) |
| 2610.19696 — Share the Symbol, Not the Vector: Training-Free Fact Communication Across Language Models | [Read analysis](2610.19696.md) |
| 2610.13623 — APEX-Harm: Evaluating Agent Safety in Shared Professional Workspaces | [Read analysis](2610.13623.md) |
| 2610.19729 — A Diagnostic Study of World-Space Human Recovery Under High Camera Dynamics | [Read analysis](2610.19729.md) |
| 2610.19560 — τ-Emotion-Bench: Exposing the Interaction Fragility of LLM Agents through Real-World User Emotions | [Read analysis](2610.19560.md) |
| 2610.14020 — LabInstruct: Benchmarking Situated Instructional Video Generation for Lab Procedures | [Read analysis](2610.14020.md) |
| 2610.15542 — Apertus 1.5: From Open Text Models to Open Multimodal Reasoners | [Read analysis](2610.15542.md) |
| 2610.15725 — SkillMarker: A KGW-Based Watermarking Method for Agent Skill Ownership Verification | [Read analysis](2610.15725.md) |
| 2610.16302 — RAR: Rate-Adaptive Rollout for Time-Consistent Interactive World Models | [Read analysis](2610.16302.md) |
| 2610.14774 — ProgAgent: Learning Tool Orchestration through Programmatic Training | [Read analysis](2610.14774.md) |
| 2610.20256 — Long-Horizon RL Needs Muon | [Read analysis](2610.20256.md) |
| 2610.19100 — GroundGUI: GUI Grounding by High-Quality Data and Distillation-to-Reinforcement Learning | [Read analysis](2610.19100.md) |
| 2610.19026 — Joint Subspace Sparse Attention for Efficient Long-Context Decoding | [Read analysis](2610.19026.md) |
| 2610.18284 — Efficient Scene-Text Refinement via Pixel-Space Grouped Image Generation | [Read analysis](2610.18284.md) |
| 2610.19525 — Diagnosing and Correcting Reward Hacking in Verifiable Instruction Following | [Read analysis](2610.19525.md) |
| 2610.18248 — Are We Testing Too Much? A Survey of Benchmark Compression for Efficient Evaluation of Large Language Models | [Read analysis](2610.18248.md) |
| 2610.20609 — SafeDriveVLA: Navigation-Conditioned World Model Dreaming for Conflict-Aware End-to-End Autonomous Driving | [Read analysis](2610.20609.md) |
| 2610.17191 — FreeSolo: Linear-time Sparse Attention with Zero-Shot Length Extrapolation | [Read analysis](2610.17191.md) |
| 2610.19628 — Self-Conditioning Enables Deep Sequential Reasoning in Flow Matching | [Read analysis](2610.19628.md) |
| 2610.17309 — StartLux-Decision: AutoThink Decision Models with Reinforcement Learning for Calibrated Deliberative Decisions | [Read analysis](2610.17309.md) |
| 2610.17246 — LLM-to-Flow Distillation: Teaching Natural Language Goals to Scientific Generators | [Read analysis](2610.17246.md) |
| 2610.18598 — Rethinking Projector Training in Multimodal LLMs | [Read analysis](2610.18598.md) |
| 2610.20195 — What Makes a Social Agent's Interactions Effective? Learning from Verifiable Outcomes in Paired Worlds | [Read analysis](2610.20195.md) |
| 2610.19420 — From Failures to Learnable Worlds: Policy-Conditioned Environment Generation for Navigation Agents | [Read analysis](2610.19420.md) |
| 2610.20220 — Glance Forcing: Making Bidirectional Diffusion Autoregressive at a Glance | [Read analysis](2610.20220.md) |
| 2610.17016 — ProbabilityBench: Model Evaluation and Calibration with Exact Ground-Truth Uncertainty | [Read analysis](2610.17016.md) |
| 2610.14261 — BigCell: Generating Gigapixel Whole-Slide Images | [Read analysis](2610.14261.md) |
| 2610.20604 — VITAL: From Visual Motion to Precise Action | [Read analysis](2610.20604.md) |
| 2610.19551 — TextVerifier: Seeing Beyond Recognition to Verify Chinese Text Rendering | [Read analysis](2610.19551.md) |
| 2610.17638 — Acting Through Registers | [Read analysis](2610.17638.md) |
| 2610.20456 — The COUNT: Counting N-grams Unlocks Scaling on Host Memory and Training-Free Adaptation | [Read analysis](2610.20456.md) |
| 2610.20586 — Continuum Attention | [Read analysis](2610.20586.md) |
| 2610.18755 — PreciseCoder: Faithful and Generalizable Debugging Beyond Unit-Test Rewards | [Read analysis](2610.18755.md) |
| 2610.20516 — VASPO: Self-Distillation with Privileged Value Estimation | [Read analysis](2610.20516.md) |
| 2610.19726 — Generative World Simulation with DAO and JING | [Read analysis](2610.19726.md) |
| 2610.20582 — Latent Compaction with Test-Time Training | [Read analysis](2610.20582.md) |
| 2610.14096 — SWEeper-Bench: Can Agents Discover Bugs in Interactive Software? | [Read analysis](2610.14096.md) |
| 2610.17831 — Diff Diffusion: Predicting Edit Paths with Diffusion Models for Efficient Code Editing | [Read analysis](2610.17831.md) |
| 2610.15425 — Exploring the Limits of Combinatorial Generalization in Embodied Manipulation | [Read analysis](2610.15425.md) |
| 2610.17893 — Training LLMs for Multi-Agent Collaboration with Verifiable Information Rewards | [Read analysis](2610.17893.md) |
| 2610.15715 — History Replays Itself: Unleashing Long-Context Capability in Linear Attention | [Read analysis](2610.15715.md) |
| 2610.17079 — Rethinking LLM-Guided Visual Question Answering: Does Deeper Knowledge Integration Really Help? | [Read analysis](2610.17079.md) |
| 2610.16338 — SyncReward: Human-Aligned Synchronization Reward for Audio-Visual Generation | [Read analysis](2610.16338.md) |
| 2610.18838 — Scaling Online Optimal Transport Minibatches for Flow Matching | [Read analysis](2610.18838.md) |
| 2610.19138 — MA-Bench: Measuring Operational Planning in Language Models | [Read analysis](2610.19138.md) |
| 2610.17242 — When Left Is Right? Camera-Motion Understanding beyond Screen | [Read analysis](2610.17242.md) |
| 2610.18354 — Choosing LLMs for Strategic Agent Interactions | [Read analysis](2610.18354.md) |
| 2610.18638 — To Align or Not To Align: Check Your COMPASS Before You Train | [Read analysis](2610.18638.md) |
| 2610.13239 — Jag: Direct Box Prediction for Efficient Visual Grounding | [Read analysis](2610.13239.md) |
| 2610.10787 — NavGPT-3: Harnessing Context in a Hierarchical Navigation Runtime | [Read analysis](2610.10787.md) |
| 2610.09055 — MimicX: Policy-in-the-Loop Supervision Refinement for Video-Driven Humanoid Motion Tracking | [Read analysis](2610.09055.md) |
| 2610.20524 — Physical Time as a Missing Dimension of Robot Policy Memory Dynamics | [Read analysis](2610.20524.md) |
| 2610.20588 — Your Transformer Is Secretly Elastic | [Read analysis](2610.20588.md) |
| 2610.20137 — StreamErase: Towards Ultra-Fast Streaming Video Erasing | [Read analysis](2610.20137.md) |
| 2610.19422 — AgentSafeEvo: Adversarial Co-Evolution for LLM Agent Safety | [Read analysis](2610.19422.md) |
| 2610.05230 — Vela: Scaling Vision-Language-Action Models with Adaptive Action Curve Parametrization | [Read analysis](2610.05230.md) |
| 2606.24472 — G^3VLA: Geometric Inductive Bias for Vision-Language-Action Models | [Read analysis](2606.24472.md) |
| 2610.19121 — Unlocking Structured Pruning for Reasoning Language Models via Attention-Preserving MLP Trimming | [Read analysis](2610.19121.md) |
| 2610.14162 — Next-Concept Modeling: Fast, Parallel Coarse-to-Fine Text Generation | [Read analysis](2610.14162.md) |
| 2610.20828 — CoTranslator: Reverse to Forward Chain-of-Thought Translator for Reasoning Distillation | [Read analysis](2610.20828.md) |
| 2610.20526 — Lluna: Collaborative Unimodal Models for Missing-Modality Inference | [Read analysis](2610.20526.md) |
| 2610.19361 — VLX-Go: Robust Embodied Tracking through Multi-Stage Learning and On-Policy Refinement | [Read analysis](2610.19361.md) |
| 2610.18762 — Looking Complete Is Not Being Grounded: Evaluating LLM Sitreps Against Human-Authored Situation Reports | [Read analysis](2610.18762.md) |
| 2610.14216 — Cortex: Measurement-Gated Evolution and Pruning of Coding-Agent Skills and Rules | [Read analysis](2610.14216.md) |
| 2610.17301 — The Agent Knew: Internal States Forecast Unauthorized Actions and Stop Them, and the Lies That Follow | [Read analysis](2610.17301.md) |
| 2610.15112 — Drive3R: Block-wise Streaming Geometric Foundation Models for Autonomous Driving | [Read analysis](2610.15112.md) |

## Current papers without a published edge

- [2610.20584](2610.20584.md)
- [2610.19789](2610.19789.md)
- [2610.17771](2610.17771.md)
- [2610.20431](2610.20431.md)
- [2610.20399](2610.20399.md)
- [2610.19820](2610.19820.md)
- [2610.19366](2610.19366.md)
- [2610.14448](2610.14448.md)
- [2610.19128](2610.19128.md)
- [2610.20442](2610.20442.md)
- [2610.19698](2610.19698.md)
- [2610.18861](2610.18861.md)
- [2610.14270](2610.14270.md)
- [2610.18097](2610.18097.md)
- [2610.04781](2610.04781.md)
- [2610.19118](2610.19118.md)
- [2610.19696](2610.19696.md)
- [2610.19729](2610.19729.md)
- [2610.15542](2610.15542.md)
- [2610.15725](2610.15725.md)
- [2610.16302](2610.16302.md)
- [2610.14774](2610.14774.md)
- [2610.20256](2610.20256.md)
- [2610.19100](2610.19100.md)
- [2610.19026](2610.19026.md)
- [2610.18248](2610.18248.md)
- [2610.20609](2610.20609.md)
- [2610.19628](2610.19628.md)
- [2610.17246](2610.17246.md)
- [2610.19420](2610.19420.md)
- [2610.20220](2610.20220.md)
- [2610.14261](2610.14261.md)
- [2610.20604](2610.20604.md)
- [2610.17638](2610.17638.md)
- [2610.20456](2610.20456.md)
- [2610.20586](2610.20586.md)
- [2610.20582](2610.20582.md)
- [2610.14096](2610.14096.md)
- [2610.17831](2610.17831.md)
- [2610.17079](2610.17079.md)
- [2610.18838](2610.18838.md)
- [2610.19138](2610.19138.md)
- [2610.17242](2610.17242.md)
- [2610.18354](2610.18354.md)
- [2610.13239](2610.13239.md)
- [2610.09055](2610.09055.md)
- [2610.20524](2610.20524.md)
- [2610.20588](2610.20588.md)
- [2610.05230](2610.05230.md)
- [2610.19121](2610.19121.md)
- [2610.14162](2610.14162.md)
- [2610.20828](2610.20828.md)
- [2610.20526](2610.20526.md)
- [2610.19361](2610.19361.md)
- [2610.18762](2610.18762.md)

---

[Support these research summaries on Buy Me a Coffee](https://buymeacoffee.com/vollero)
