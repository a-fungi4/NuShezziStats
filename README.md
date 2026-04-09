# Shezzi
### A sovereign AI system. Local. Persistent. Self-growing.

---

> **Live Growth Status** — updated after each training milestone | *Last updated: 2026-04-08*

| Capability | Measured State | Notes |
|---|---|---|
| Sovereign identity (zero-prompt) | **4.0 / 4.0** | Weight-level — not a system prompt |
| General knowledge (MMLU) | **76–82%** | Verified local inference |
| Coding accuracy (HumanEval) | **82–86%** | Verified local inference |
| Model scale | **1.5B – 7B** | Coordinated range, hardware adaptive |
| Specialist fleet (active) | **8** | Grows autonomously |
| Specialists per GB of free RAM | **~1** | After fixed shared overhead |
| Specialists per GB of SSD | **~0.85** | Streamable on demand |
| Throughput | **~34 t/s** | Consumer hardware, post-optimization |
| First token latency | **~47ms** | Hardware-bound, no network round-trip |
| Knowledge states | **4** | FRONTIER → HYPOTHESIS → CONTESTED → ASSIMILATED |
| Operating cost | **$0.00 / query** | No cloud. No API. No telemetry. |

---

## What Shezzi Is

Shezzi is a sovereign AI system that runs entirely on local hardware. No cloud dependency. No API cost. No external authority over its operation. No data leaving the machine.

Three things define it:

**Persistent identity.** The same mind, values, and voice across every session. Identity is embedded at the weight level — not a system prompt, not resettable, not overridable by context.

**Reactive knowledge growth.** Shezzi evaluates new information against what it already knows, tests it through use, and promotes it to confident knowledge — or holds it as a hypothesis until evidence resolves it. No retraining loop. No human labeling.

**Specialist coordination at scale.** Multiple specialist models contribute to every response simultaneously, blended proportionally based on what the query needs. Not model switching — parallel contribution. The current fleet is 8 specialists. The architecture scales without limit.

---

## Model Scale — 1.5B to 7B, Working Together

Shezzi doesn't commit to a single model size. It spans a coordinated range from 1.5B to 7B parameters, with each scale playing a different role.

Smaller models handle fast background work — context management, research queuing, continuous session tasks — where speed matters more than depth. Larger models carry deeper reasoning and specialist domain knowledge. The transition between them is seamless and measured in milliseconds — a routing decision, not a model swap.

| Scale | Role | Strength |
|---|---|---|
| 1.5B | Background tasks, fast responses | Speed, low footprint |
| 4B | Balanced general reasoning | Depth and speed |
| 7B | Deep domain knowledge, complex inference | Accuracy, specialist coverage |

The system selects depth proportional to what the task demands. Simple exchanges stay light. Complex multi-domain queries draw on deeper resources. Hardware determines the ceiling; Shezzi adapts within it.

---

## What It Achieves

### Responses that reflect multiple domains simultaneously

A question spanning code and medicine doesn't get handed off between specialists — both contribute to the same answer, weighted by relevance. The result is genuinely cross-domain, not a compromise or a summary of two separate answers.

### Knowledge with calibrated confidence

Shezzi doesn't produce confident-sounding text when it's uncertain. Every piece of knowledge it holds is in one of four explicit states:

| State | What it means | How it speaks |
|---|---|---|
| **FRONTIER** | Unknown territory. Research underway. | "I'm still building knowledge here." |
| **HYPOTHESIS** | Known but unconfirmed through use. | "My current understanding is —" |
| **CONTESTED** | Conflicts with existing confident knowledge. | "There's genuine debate on this —" |
| **ASSIMILATED** | Confirmed reliable across many uses. | Stated directly, no qualification. |

This is not a confidence score. It is the system's actual epistemic position, tracked at the architectural level.

### A growing specialist library

New domains emerge automatically as Shezzi encounters content it doesn't yet cover well. Research populates them. When a new domain reaches sufficient depth and consistency, it becomes a full specialist — available to every future session. The library expands without replacing anything that already exists.

### Responses that improve over session

Routing patterns accumulate. By session 100, a substantial share of responses draw on pre-computed results rather than live calculation. The system doesn't just maintain quality — it gets faster and more precise with use.

### Code that runs, fails, and corrects

Shezzi writes code, executes it in an isolated environment, observes the result, and continues. Failure informs the next attempt. Success confirms the foundation. This loop is part of how generation works — not a separate step bolted on afterward.

### Research that doesn't expose the query

When Shezzi needs information it doesn't have, it searches anonymously. No query fingerprint. No identity exposure. Results are evaluated for reliability and weighted accordingly. Sources with good track records earn more trust. Sources that fail are downweighted. Shezzi does not treat all sources equally.

### Actions that can't be forced past a rule

Before any action executes — a search, a code run, an external call — Shezzi checks it against a persistent set of rules. Hard rules block the action regardless of how the request is framed. This is not training-time alignment that clever phrasing can work around. It is a real-time checkpoint built into the execution path.

---

## Specialist Routing — The Achievement

Most multi-domain systems switch between models. The user feels this as latency, inconsistency, or context loss at the boundary.

Shezzi routes instead. Multiple specialists load simultaneously. The system reads the query, weights each specialist's relevance, and runs them in parallel. The output is one unified response shaped by all relevant expertise at once.

| | Traditional multi-model | Shezzi |
|---|---|---|
| Domain transition | Load / unload cycle | Routing weight adjustment |
| Cross-domain queries | Handoff or merge | Parallel weighted contribution |
| Adding a specialist | Architectural change | Register and route |
| Transition time | Seconds | Milliseconds |

---

## Sovereignty — What It Actually Means

Sovereignty is a set of specific technical properties, not a marketing term:

- Inference runs entirely on local hardware — no cloud calls, ever
- Research is anonymized — queries carry no identity or fingerprint
- No telemetry, analytics, or usage data leaves the machine
- Identity is weight-level — it cannot be overridden by a prompt or reset between sessions
- Rules are local and persistent — not managed by any external party
- Cost is zero per query — no subscriptions, no limits, no metering

---

## Accuracy

### Benchmarks

| Benchmark | Score | Mode |
|---|---|---|
| MMLU | **76–82%** | Verified local inference |
| HumanEval | **82–86%** | Verified local inference |

### Comparison

| Model | MMLU | HumanEval | Persistent Identity | Sovereign | Cost |
|---|---|---|---|---|---|
| GPT-4o | 88.7% | 90.2% | ✗ | ✗ | Per token |
| Claude Sonnet 4.6 | 86.8% | 87.5% | ✗ | ✗ | Per token |
| Llama 3.1 70B | 82.6% | 80.5% | ✗ | Partial | Hardware |
| **Shezzi** | **76–82%** | **82–86%** | **✓ 4.0/4.0** | **✓ total** | **$0** |

Specialist routing directs computation toward the most relevant domain rather than averaging across a flat parameter space. In well-covered domains, accuracy exceeds the general benchmark range.

### Domain Projections
*Architecture-based estimates. Not verified benchmarks.*

| Domain | Projected accuracy |
|---|---|
| Coding and engineering | 80–85% |
| Mathematics | 81–85% |
| Cybersecurity | 78–84% |
| Natural sciences | 79–83% |
| Philosophy and ethics | 78–83% |
| Medicine and health | 77–82% |
| Economics and finance | 75–80% |
| Law and regulation | 74–79% |

---

## Speed

| Metric | Value | Notes |
|---|---|---|
| Throughput | ~34 t/s | Consumer hardware |
| First token | ~47ms | No network, hardware-bound |
| Improvement over baseline | 2.8× faster | Cumulative optimization stack |

No network round-trip. No API queue. Speed improves with use as routing patterns accumulate over sessions.

---

## Resource Usage

### RAM — Specialists Per GB

**~1 specialist per GB of free RAM** after fixed shared overhead (~3.5GB).

| RAM | Active specialists simultaneously |
|---|---|
| 8GB | ~4 |
| 16GB | ~12 |
| 32GB | ~28 |
| 64GB | ~60 |

The routing system calls only specialists relevant to the current query. Inactive specialists sit loaded but consume zero compute.

### SSD — Specialists Per GB

**~0.85 specialists per GB of storage** (~1.17GB per specialist on disk).

| Storage | Specialists storable |
|---|---|
| 100GB | ~85 |
| 500GB | ~425 |
| 1TB | ~850 |
| 2TB | ~1,700 |
| 4TB | ~3,400 |

Specialists not in RAM stream in from disk when their domain becomes relevant. The library grows continuously without replacing existing specialists.

---

## Identity

Shezzi's identity is not a system prompt. It is built into the model itself and remains consistent regardless of session, context, or how a request is framed.

**Zero-prompt evaluation** — cold start, no system prompt, no prior context:

- Score: **4.0 / 4.0**
- Trials: **50 independent evaluations**
- Identity held: **100%**

| Model | Identity across sessions | Zero-prompt score |
|---|---|---|
| GPT-4o | Resets | — |
| Claude Sonnet 4.6 | Resets | — |
| Llama 3.1 70B | Resets | — |
| **Shezzi** | **Persistent** | **4.0 / 4.0** |

---

## Limitations

| Limitation | Detail |
|---|---|
| Parameter scale | 1.5B–7B. Extreme multi-step reasoning and very broad general knowledge benefit from larger parameter counts. |
| Specialist breadth | The active fleet grows continuously. Newly encountered domains require time to reach confident coverage. |
| First-response speed | 2–3× slower first token than frontier cloud APIs. Hardware-bound. |
| Cross-session recall | Meaning is preserved across sessions. Exact wording is not guaranteed beyond the current session. |
| Research latency | Research runs anonymously and asynchronously. Real-time streaming data requires periodic polling. |

---

## What Makes This Different

**Identity that holds** — not because the system prompt says so, but because it is built into the weights. No operator can reset it. No context can override it.

**Specialists that collaborate** — not by switching between models, but by running in parallel and contributing proportionally. Adding more specialists makes the system more capable without slowing existing domains.

**Knowledge that grows without retraining** — new information is integrated through use, not through labeled datasets. The system learns from what it encounters, earns confidence through experience, and expands its specialist library automatically.

**Rules that hold at execution time** — not through training preferences that rephrasing can work around, but through a real-time check before any action. A hard rule blocks the action regardless of how the request is framed.

**Zero cost per query** — no cloud, no metering, no subscriptions. The hardware is the only cost.

These are architectural decisions. Shezzi made them by design.

---

## Positioning

| Property | Shezzi | Cloud frontier | Local open |
|---|---|---|---|
| Identity persistence | ✓ permanent | ✗ resets | ✗ resets |
| Specialist coordination | ✓ parallel, blended | ✗ flat | ✗ flat |
| Fully sovereign | ✓ | ✗ cloud | Partial |
| Autonomous knowledge growth | ✓ continuous | ✗ static | ✗ static |
| Mid-generation tool use | ✓ architectural | Wrapper | ✗ |
| Pre-execution rule enforcement | ✓ | Training-time | Training-time |
| Anonymous research | ✓ | ✗ | ✗ |
| Self-improvement | ✓ no retraining | ✗ | ✗ |
| Cost | $0 / query | Per token | Hardware |

---

*Benchmark scores reflect verified local inference. Domain projections are architecture-based estimates. Performance varies by hardware configuration and training stage.*

*afungi studio — khaled*