# Al Mahdi Marhou

### Building AI that augments human capability — safely, efficiently, and with human agency at the center.

I am interested in a simple but increasingly important question:

> **How do we build AI systems that amplify human capability without giving up human judgment, responsibility, and control?**

My work explores the engineering and decision layers needed to make that possible: **AI policy, reliable agents, efficient AI systems, evaluation, decision support, and human–AI co-evolution.**

I see AI not simply as automation, but as a new participant in human systems.  
The challenge is therefore not only making models more capable — it is designing the **rules, feedback loops, boundaries, measurements, and interfaces** that allow humans and AI to work together productively.

---

## 🔷 Merchval — Policy Infrastructure for AI

**My primary project.**

Merchval explores how explicit policies can become an executable control layer between **AI systems, business rules, and consequential decisions**.

Many important decisions should not depend entirely on a prompt or on the probabilistic judgment of a language model.

Merchval investigates a different architecture:

**intent → policy → AI reasoning → controlled action**

The goal is to make AI systems:

- safer without making them unusable,
- governed without hard-coding every decision,
- explainable at the policy level,
- auditable when decisions matter,
- and capable of operating within explicit organizational boundaries.

Initial applications include areas such as **refund decisions, company policies, agent actions, approvals, exceptions, and other bounded business decisions**.

→ [Merchval](https://github.com/mahdimor/merchval)

---

## 🧪 AIK — Agent Improvement Kit

AI systems also need a way to **learn from failure without silently introducing new failures**.

AIK is a local-first framework for turning an agent failure into:

**failure → test case → candidate improvement → evaluation → acceptance decision → permanent regression test**

It explores a disciplined improvement loop for AI agents where changes are measured rather than assumed to be better.

→ [AIK](https://github.com/mahdimor/AIK)

---

## 🔄 Nelarvo — Human × AI Co-evolution

AI transformation is not simply about replacing tasks.

When AI enters a workflow, work **moves**:

- some tasks disappear,
- some become cheaper,
- human review appears,
- exceptions increase,
- responsibilities shift,
- and entirely new work is created.

Nelarvo is an open-source tool for modeling these transitions and understanding how **human roles and AI capabilities can evolve together**.

The objective is not to predict which humans disappear.

It is to understand:

> **What should machines do, what should humans continue doing, and what new capabilities emerge between them?**

→ [Nelarvo](https://github.com/mahdimor/nelarvo)

---

## ⚡ Efficient AI

More capable AI should not automatically mean more expensive AI.

I experiment with ways to improve the **quality / cost / reliability frontier** of AI systems through evaluation-driven optimization.

My GEPA × n8n experiments explore:

- prompt optimization,
- model selection,
- pipeline architecture,
- multi-provider resilience,
- quality evaluation,
- and cost compression.

One experiment reduced generation cost by **73% while preserving most of the target quality**, illustrating why AI architecture should optimize systems rather than simply defaulting to larger models.

→ [GEPA × n8n experiments](https://github.com/mahdimor/gepa-n8n-ai-optimizer-experiments)

---

## What ties these projects together

These projects explore different layers of the same problem:

```text
                    HUMAN INTENT
                         │
                         ▼
              ┌────────────────────┐
              │      POLICY        │
              │     Merchval       │
              └─────────┬──────────┘
                        │
                        ▼
              ┌────────────────────┐
              │     AI SYSTEM      │
              │ Agents · Models    │
              └─────────┬──────────┘
                        │
              ┌─────────┴──────────┐
              ▼                    ▼
       RELIABILITY             EFFICIENCY
           AIK             GEPA / Optimization
              │                    │
              └─────────┬──────────┘
                        ▼
              ┌────────────────────┐
              │   HUMAN × AI       │
              │   CO-EVOLUTION     │
              │      Nelarvo       │
              └────────────────────┘
```

**Policy** defines what AI may do.  
**Evaluation** tells us whether it works.  
**Optimization** makes it economically sustainable.  
**Human–AI co-evolution** determines how it fits into the systems around us.

---

## Areas I am exploring

**Safe AI · AI Policy · Agent Reliability · AI Evaluation · Decision Systems · Efficient AI · Human-in-the-loop Systems · AI Architecture · Human–AI Co-evolution**

---

### A principle behind my work

> **The most valuable AI systems will not be the ones that remove humans from the loop everywhere. They will be the ones that make humans and machines better together — while preserving human agency where it matters.**
