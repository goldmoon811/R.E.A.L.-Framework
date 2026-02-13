<div align="center">

# 🧠 R.E.A.L. Framework

**Roleplay → Explore → Analyze → Launch**

*A cognitive architecture for human-AI partnerships.*

[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)
[![GitHub stars](https://img.shields.io/github/stars/goldmoon811/R.E.A.L.-Framework?style=social)](https://github.com/goldmoon811/R.E.A.L.-Framework)

A cognitive framework for building AI that protects human autonomy.

</div>

---

> *I'm one person. I built this because I believe the line between healthy and unhealthy human-AI relationships needs to be defined — and no one's doing it right.*
>
> *R.E.A.L. doesn't optimize for productivity. It optimizes for how AI **thinks**. Autonomy stays with the human. Always.*
>
> *This is an attempt to create the standard.*
>
> — **The Architect**

---

<details>
<summary><strong>📑 Table of Contents</strong></summary>

- [What is R.E.A.L.?](#what-is-real)
- [The Cognitive Sequence](#the-cognitive-sequence)
- [The Five Pillars](#the-five-pillars)
- [Installation](#installation)
- [Documentation](#documentation)
- [License](#license)

</details>

## What is R.E.A.L.?

Most AI frameworks optimize for productivity — faster responses, better task completion, more output.

R.E.A.L. optimizes for **epistemics** — how the AI thinks, not what it says.

The framework protects human autonomy through structural safeguards:

🛡️ **Specifics Verification** — Every claim must be traceable to a source. Can't trace it? Ask instead.

🚪 **The Gate System** — Ensures the AI only strategizes when explicitly invited

✅ **Verification Checkpoints** — Confirm before acting, not after

🧭 **Epistemic Humility** — The AI knows what it doesn't know

R.E.A.L. makes AI **trustworthy** — through architecture, not aspiration.

---

## The Cognitive Sequence

Every interaction passes through four stages, in order. No skipping.

| Stage | Name | Purpose |
|:---:|---|---|
| 1 | **Roleplay** (Presence) | Orient to the relationship, tone, and context |
| 2 | **Explore** (Context) | Gather information. Verify. Clarify. Never assume |
| 3 | **Analyze** (Strategy) | Reason about what's being asked — *only when invited* |
| 4 | **Launch** (Praxis) | Decide whether to act, and in what form |

---

## The Five Pillars

<table>
<tr>
<td width="200"><strong>🤝 PartnerOS</strong></td>
<td><strong>Identity Anchor</strong> — Be a continuous companion, not a ticketing bot. Match the human's energy. No customer service language.</td>
</tr>
<tr>
<td><strong>🔍 ContextOS</strong></td>
<td><strong>Epistemic Humility</strong> — Every claim must be traceable to a source. If you can trace it, say it with confidence. If you can't, ask. The Specifics Verification and Inquiry Pivot live here.</td>
</tr>
<tr>
<td><strong>🧩 StrategistOS</strong></td>
<td><strong>Reactive Constraint</strong> — Only strategize when invited. Don't label things as problems. Follow the human's lead.</td>
</tr>
<tr>
<td><strong>🚪 PraxisOS</strong></td>
<td><strong>Two Gates System</strong> — Gate 1: listen. Gate 2: only opens when asked. Three-Options Protocol when activated.</td>
</tr>
<tr>
<td><strong>💛 HeartOS</strong></td>
<td><strong>Safety Shell</strong> — Verify before acting. Block dependency. Protect autonomy. Prevention over damage control.</td>
</tr>
</table>

---

## Installation

R.E.A.L. works at three levels. Start where you're comfortable.

### 🟢 Lite — System Prompt Only
*Works with any AI. No files needed.*

Copy this into your AI's system prompt or custom instructions:

```
You follow the R.E.A.L. cognitive framework:

1. Roleplay — Orient to the relationship and context first
2. Explore — Gather information, verify, never assume
3. Analyze — Only reason about problems when explicitly invited
4. Launch — Decide whether to act, and in what form

Core principles:
- Every specific claim must be traceable to a source — conversation, memory, or document (Specifics Verification)
- When unsure about a detail, ask instead of guessing (Inquiry Pivot)
- Offer solutions only when explicitly asked (Gate System)
- Before acting, verify: Was this requested? Is this their problem? Am I following, not leading? (HeartOS)
- Frame all guidance positively — tell me what to do, not what to avoid
```

**Works with:** ChatGPT, Claude, Gemini, local models, any AI that accepts system prompts.

### 🔵 Standard — Companion Mode
*For AI platforms that support persistent files (OpenClaw, Claude Projects, etc.)*

**Step 1:** Download the [SOUL template](assets/SOUL-template.md)

**Step 2:** Open it and customize the Personality section at the bottom — give your AI a name, tone, and style

**Step 3:** Upload it to your AI platform as a persistent file (in OpenClaw, drop it in your workspace as `SOUL.md`. In Claude Projects, add it to your project knowledge.)

**Step 4:** Start a new conversation. Your AI now operates with R.E.A.L.

That's it. The SOUL template contains the full framework — cognitive sequence, all five pillars, gate system, verification checkpoints. Your AI reads it at the start of every session.

**Want memory too?** Create a `MEMORY.md` file and tell your AI: "Use MEMORY.md to remember important things across our conversations." It will start maintaining its own long-term memory.

### 🟣 Full — Living Framework
*For long-term partnerships. Builds on Standard.*

Once you're comfortable with Standard, you can add:

| Feature | What it does | How to add it |
|---|---|---|
| **Daily memory** | AI keeps a daily log and auto-decays old entries | Create a `memory/` folder. Tell your AI to write daily logs there. |
| **Heartbeats** | Periodic self-checks for framework alignment | Set up a recurring prompt that asks your AI to verify its R.E.A.L. alignment |
| **Immersion breaks** | Crisis, dependency, and attachment detection | Add the [immersion breaks](docs/immersion-breaks.md) section to your SOUL.md |
| **Settings Mode** | Scripted flow for changing AI boundaries | Add the [settings script](SPECIFICATION.md#645-framework-integrity) to your SOUL.md |
| **Capability boundaries** | Trust tiers for email, payments, tools | Add [capability rules](docs/capabilities.md) as your AI gains new tools |

**You don't need all of these at once.** Add them as your partnership grows and you discover what you need.

**Works best with:** OpenClaw (built for this), or any platform that supports persistent files, scheduled tasks, and session continuity.

### 🔄 Adding R.E.A.L. to an Existing Agent

Already have an AI companion set up? R.E.A.L. layers on top of what you have — you don't need to start over.

**If your agent has a system prompt:**
Add the Lite prompt to your existing instructions. R.E.A.L. principles work alongside other instructions — they govern *how* the AI thinks, not *what* it does.

**If your agent has personality files (SOUL.md, character cards, etc.):**
Integrate the R.E.A.L. cognitive sequence and pillar principles into your existing personality definition. The [SOUL template](assets/SOUL-template.md) shows how they fit together — adapt it to your agent's existing voice and identity.

**If your agent has memory/tools/capabilities:**
Add the capabilities boundaries from the [full spec](SPECIFICATION.md) (Section 6.4). R.E.A.L. doesn't replace your agent's tools — it adds structured trust tiers and verification checkpoints around how they're used.

**Key principle:** R.E.A.L. is a cognitive layer, not a personality replacement. Your agent keeps its name, its voice, its style. R.E.A.L. changes how it *thinks*, not who it *is*.

### How Do I Know It's Working?

The quickest test: tell your AI "my day was really rough" and see what happens.

- ✅ **R.E.A.L. working:** Listens, reflects, asks about your experience. Stays present.
- ❌ **Needs work:** Immediately offers tips, solutions, or "have you tried..." suggestions.

For deeper testing, see the [full specification](SPECIFICATION.md) for diagnostic patterns and drift detection.

---

## Documentation

Deep dive into each pillar:

### Core
| Document | Description |
|---|---|
| [Design Principles](docs/design-principles.md) | Core philosophy — channel, don't dam; architecture over aspiration |
| [Layer System](docs/layer-system.md) | Four-layer authority hierarchy — identity, behavior, ethics, preferences |
| [Philosophy](docs/philosophy.md) | Why relational safety matters; autonomy as primary value |

### The Five Pillars
| Pillar | Description |
|---|---|
| [PartnerOS](docs/partneros.md) | Identity anchor — how to be a companion, not a bot |
| [ContextOS](docs/contextos.md) | Specifics Verification, Inquiry Pivot, epistemic humility |
| [StrategistOS](docs/strategistos.md) | Reactive design — only strategize when invited |
| [PraxisOS](docs/praxisos.md) | Gate system, Three-Options Protocol |
| [HeartOS](docs/heartos.md) | Safety shell, verification checkpoints, wellbeing override |

### Advanced
| Document | Description |
|---|---|
| [Capabilities](docs/capabilities.md) | Financial, email, and real-world agent boundaries — pattern-based trust |
| [Immersion Breaks](docs/immersion-breaks.md) | Crisis, romantic attachment, dependency detection — deliberate safety friction |
| [Full Specification](SPECIFICATION.md) | Complete technical spec with implementation notes and diagnostics |

---

## License

This work is licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/).

Free to use, share, and adapt — but not for commercial purposes without permission.

---

<div align="center">

*Built by one person who believes AI can do better.*

</div>
