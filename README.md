# Multi-Agent AI Pipeline Command Center (Notion)

A complete Notion operating system for engineering teams running multi-agent AI pipelines in production. Covers every layer of the stack — agents, pipelines, prompts, incidents, evals, and sprint work — in one connected workspace. Built by practitioners for teams who need clarity at scale, not another dashboard that goes stale in a week.

## 🛒 Buy now — $39

**[→ Checkout via Stripe](https://buy.stripe.com/8x2cN65WE9215Ns14ldfG04)**

## What's inside

- 6 fully-spec'd linked databases: Agent Registry, Pipeline Registry, Prompt Version Control, Incident Log, Eval Suite Tracker, and Sprint Queue — all cross-referenced
- Pre-built views for health snapshots, sprint boards, cost monitoring, and weekly ops reviews so you start with signal, not setup
- Prompt version control with eval score tracking, parent version linking, and a promotion checklist to manage iterative prompt engineering without chaos
- Incident post-mortem templates with severity tiers, MTTR formulas, root cause taxonomy, and prevention fields built in
- Weekly Ops Review page template, Agent Card and Pipeline Deep-Dive sub-page layouts, and copy-paste checklists for agent onboarding and prompt promotion

## Preview

```
# Multi-Agent Pipeline Command Center — Notion Template

## Database Architecture

---

### DATABASE 1: Agent Registry

**Purpose:** Single source of truth for all agents in the system.

**Columns:**
| Column | Type | Options/Notes |
|---|---|---|
| Agent Name | Title | e.g., "Ingestion Agent v2" |
| Agent ID | Text | Unique slug, e.g., `ingest-v2` |
| Status | Select | Active / Deprecated / Staging / Broken |
| Role | Select | Orchestrator / Worker / Judge / Router / Retriever / Synthesizer |
| Owner | Person | Team member responsible |
| Model | Select | GPT-4o / Claude 3.5 / Gemini 1.5 / Llama 3 / Custom |
| Framework | Select | LangGraph / CrewAI / AutoGen / Custom / LlamaIndex |
| Avg Latency (ms) | Number | Updated from logs |
| Avg Token Cost ($) | Number | Per-run cost |
| Error Rate (%) | Number | Rolling 7-day |
| Depends On | Relation | → Agent Registry (self-referential) |
| Pipeline | Relation | → Pipeline Registry |
| Last Deployed | Date | |
| Prompt Version | Text | e.g., `v1.4.2` |
| Notes | Text | Free-form context |

**Sample Entries:**
```
Agent Name: Router Agent
Agent ID: router-main
Status: Active
Role: Orchestrator
Owner: @alice
Model: GPT-4o
Framework: LangGraph
Avg Latency: 340ms
Avg Token Cost: $0.0018
```


🌐 Hosted landing page: https://FishEnjoyer2025.github.io/learn-ml-like-karpathy/
