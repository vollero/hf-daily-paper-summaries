# Paper relationship graph — 2026-07-17

> [← Daily summary](../2026-07-17.md)

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
  c1["2607.14777"]
  c2["2607.15257"]
  c3["2607.15207"]
  c4["2607.14202"]
  c5["2607.14189"]
  c6["2607.14935"]
  c7["2607.13188"]
  c9["2607.12800"]
  c10["2607.13399"]
  c11["2607.14749"]
  c12["2607.15275"]
  c13["2607.15273"]
  c15["2607.14431"]
  c1 ---|"Shared method · High"| c10
  c1 -.-|"Complementary · Medium"| c2
  c2 -.-|"Shared method · Medium"| c15
  c3 ---|"Shared problem · High"| c12
  c4 ---|"Shared problem · High / Shared evaluation · High"| c5
  c6 -.-|"Shared problem · Medium"| c9
  c7 -.-|"Shared problem · Medium"| c9
  c9 -.->|"Method transfer · Medium"| c12
  c13 -.->|"Method transfer · Medium"| c11
```

| Source paper | Target paper | Relationship | Direction | Confidence |
| --- | --- | --- | --- | --- |
| [2607.14777](2607.14777.md) | [2607.13399](2607.13399.md) | Shared method | Not directional | High |
| [2607.14777](2607.14777.md) | [2607.15257](2607.15257.md) | Complementary | Not directional | Medium |
| [2607.15257](2607.15257.md) | [2607.14431](2607.14431.md) | Shared method | Not directional | Medium |
| [2607.15207](2607.15207.md) | [2607.15275](2607.15275.md) | Shared problem | Not directional | High |
| [2607.14202](2607.14202.md) | [2607.14189](2607.14189.md) | Shared problem | Not directional | High |
| [2607.14202](2607.14202.md) | [2607.14189](2607.14189.md) | Shared evaluation | Not directional | High |
| [2607.14935](2607.14935.md) | [2607.12800](2607.12800.md) | Shared problem | Not directional | Medium |
| [2607.13188](2607.13188.md) | [2607.12800](2607.12800.md) | Shared problem | Not directional | Medium |
| [2607.12800](2607.12800.md) | [2607.15275](2607.15275.md) | Method transfer | Source → target | Medium |
| [2607.15273](2607.15273.md) | [2607.14749](2607.14749.md) | Method transfer | Source → target | Medium |

## Connections to previously seen papers

```mermaid
flowchart LR
  accTitle: Relationships with previously seen papers
  accDescr: Editorial hypotheses connecting current papers with bounded previous-paper candidates.
  subgraph current["Current papers"]
    c1["2607.14777"]
    c2["2607.15257"]
    c3["2607.15207"]
    c4["2607.14202"]
    c5["2607.14189"]
    c6["2607.14935"]
    c9["2607.12800"]
    c10["2607.13399"]
    c13["2607.15273"]
  end
  subgraph previous["Previously seen papers"]
    p1(["2607.13124"])
    p4(["2607.11886"])
    p5(["2607.12477"])
    p8(["2607.13960"])
    p10(["2607.07702"])
    p19(["2607.12752"])
    p22(["2607.11523"])
    p24(["2607.13705"])
    p25(["2607.09786"])
  end
  c1 ---|"Shared method · High"| p1
  c1 ---|"Shared problem · High"| p10
  c2 ---|"Shared method · High"| p22
  c2 ---|"Complementary · High"| p24
  c3 ---|"Complementary · High"| p8
  c4 ---|"Shared evaluation · High"| p19
  c5 ---|"Shared problem · High"| p19
  c6 ---|"Shared evaluation · High"| p22
  c9 ---|"Shared evaluation · High"| p5
  c10 ---|"Shared method · High"| p1
  c10 ---|"Shared limitation · High"| p25
  p4 -.->|"Method transfer · Medium"| c13
```

| New paper | Previously seen paper | First seen by service | Relationship | Technical direction | Confidence |
| --- | --- | --- | --- | --- | --- |
| [2607.14777](2607.14777.md) | 2607.13124 ([Hugging Face](https://huggingface.co/papers/2607.13124) · [arXiv](https://arxiv.org/abs/2607.13124)) | 2026-07-16 | Shared method | Not directional | High |
| [2607.14777](2607.14777.md) | 2607.07702 ([Hugging Face](https://huggingface.co/papers/2607.07702) · [arXiv](https://arxiv.org/abs/2607.07702)) | 2026-07-16 | Shared problem | Not directional | High |
| [2607.15257](2607.15257.md) | 2607.11523 ([Hugging Face](https://huggingface.co/papers/2607.11523) · [arXiv](https://arxiv.org/abs/2607.11523)) | 2026-07-16 | Shared method | Not directional | High |
| [2607.15257](2607.15257.md) | 2607.13705 ([Hugging Face](https://huggingface.co/papers/2607.13705) · [arXiv](https://arxiv.org/abs/2607.13705)) | 2026-07-16 | Complementary | Not directional | High |
| [2607.15207](2607.15207.md) | 2607.13960 ([Hugging Face](https://huggingface.co/papers/2607.13960) · [arXiv](https://arxiv.org/abs/2607.13960)) | 2026-07-16 | Complementary | Not directional | High |
| [2607.14202](2607.14202.md) | 2607.12752 ([Hugging Face](https://huggingface.co/papers/2607.12752) · [arXiv](https://arxiv.org/abs/2607.12752)) | 2026-07-16 | Shared evaluation | Not directional | High |
| [2607.14189](2607.14189.md) | 2607.12752 ([Hugging Face](https://huggingface.co/papers/2607.12752) · [arXiv](https://arxiv.org/abs/2607.12752)) | 2026-07-16 | Shared problem | Not directional | High |
| [2607.14935](2607.14935.md) | 2607.11523 ([Hugging Face](https://huggingface.co/papers/2607.11523) · [arXiv](https://arxiv.org/abs/2607.11523)) | 2026-07-16 | Shared evaluation | Not directional | High |
| [2607.12800](2607.12800.md) | 2607.12477 ([Hugging Face](https://huggingface.co/papers/2607.12477) · [arXiv](https://arxiv.org/abs/2607.12477)) | 2026-07-16 | Shared evaluation | Not directional | High |
| [2607.13399](2607.13399.md) | 2607.13124 ([Hugging Face](https://huggingface.co/papers/2607.13124) · [arXiv](https://arxiv.org/abs/2607.13124)) | 2026-07-16 | Shared method | Not directional | High |
| [2607.13399](2607.13399.md) | 2607.09786 ([Hugging Face](https://huggingface.co/papers/2607.09786) · [arXiv](https://arxiv.org/abs/2607.09786)) | 2026-07-16 | Shared limitation | Not directional | High |
| [2607.15273](2607.15273.md) | 2607.11886 ([Hugging Face](https://huggingface.co/papers/2607.11886) · [arXiv](https://arxiv.org/abs/2607.11886)) | 2026-07-15 | Method transfer | Previous → new | Medium |

## Current paper key

| Paper | Analysis |
| --- | --- |
| 2607.14777 — SEED: Self-Evolving On-Policy Distillation for Agentic Reinforcement Learning | [Read analysis](2607.14777.md) |
| 2607.15257 — SearchOS-V1: Towards Robust Open-Domain Information-Seeking Agent Collaboration | [Read analysis](2607.15257.md) |
| 2607.15207 — BadWAM: When World-Action Models Dream Right but Act Wrong | [Read analysis](2607.15207.md) |
| 2607.14202 — KeyFrame-Compass: Towards Comprehensive Evaluation of Keyframe-Conditioned Video Generation | [Read analysis](2607.14202.md) |
| 2607.14189 — MultiRef-Compass: Towards Comprehensive Evaluation of Multi-Reference-to-Audio-Video Generation | [Read analysis](2607.14189.md) |
| 2607.14935 — VideoChat3: Fully Open Video MLLM for Efficient and Generalist Video Understanding | [Read analysis](2607.14935.md) |
| 2607.13188 — Concurrent Image Understanding and Generation: Self-Correcting Coupled Markov Jump Processes | [Read analysis](2607.13188.md) |
| 2607.15038 — Video = World + Event Stream | [Read analysis](2607.15038.md) |
| 2607.12800 — UniVR: Thinking in Visual Space for Unified Visual Reasoning | [Read analysis](2607.12800.md) |
| 2607.13399 — Demystifying On-Policy Distillation: Roles, Pathologies, and Regulations | [Read analysis](2607.13399.md) |
| 2607.14749 — WanSong v1.0 Technical Report | [Read analysis](2607.14749.md) |
| 2607.15275 — RoboTTT: Context Scaling for Robot Policies | [Read analysis](2607.15275.md) |
| 2607.15273 — MeanFlowNFT: Bringing Forward-Process RL to Average-Velocity Generators | [Read analysis](2607.15273.md) |
| 2607.13491 — DeepLoop: Depth Scaling for Looped Transformers | [Read analysis](2607.13491.md) |
| 2607.14431 — Smarter and Cheaper at Once: Byte-Exact KV-Cache Grafting Turns a Frozen Small Model into a Verified-Knowledge Flywheel | [Read analysis](2607.14431.md) |

## Current papers without a published edge

- [2607.15038](2607.15038.md)
- [2607.13491](2607.13491.md)
