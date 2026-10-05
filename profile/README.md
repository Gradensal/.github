# Gradensal

### Applied AI systems for work that requires judgment, control, and evidence.

Gradensal builds and investigates practical AI systems across reliable agents, intelligent workflows, enterprise automation, AI governance, and AI-native business applications.

Our public repositories combine engineering experiments, production-style prototypes, architecture research, and documented lessons from building with emerging AI systems.

---

## Reliable Agent Systems

A continuing Gradensal Lab research program exploring the infrastructure required when AI systems begin participating in consequential work.

```text
OBSERVE
   ↓
AUTHORIZE
   ↓
REVOKE
   ↓
DELEGATE
   ↓
VERIFY
```

| Lab | Focus | Research question |
| --- | --- | --- |
| **GL-001 — Agent Flight Recorder** | Observability | What did the agent actually do? |
| **GL-002 — Agent Intent Receipt** | Delegated authority | What was the agent authorized to do? |
| **GL-003 — Revocation Test** | Runtime authorization | What happens when authority changes mid-run? |
| **GL-004 — Agent Delegation Boundary** | Delegation policy | When should the agent ACT, ASK, or BLOCK? |
| **GL-005 — Agent Knowledge Trust Gate** | Evidence policy | Is the knowledge behind the action trustworthy enough? |

These experiments investigate different layers of a larger architectural question:

> **What control infrastructure is needed when AI moves from generating information to participating in consequential work?**

---

## Latest Research

### GL-005 — Agent Knowledge Trust Gate

A deterministic evidence-policy experiment testing whether retrieved enterprise knowledge is trustworthy enough to support an AI agent action.

The prototype separates:

**retrieval relevance**

from:

**decision authority**

and evaluates evidence through provenance, recency, expertise, corroboration, human validation, conflict detection, and action consequence.

The initial controlled experiment includes:

- 9 automated tests;
- 9 deterministic experiment evaluations;
- consequence-aware trust thresholds;
- hard evidence-policy gates;
- JSONL audit traces;
- reproducible results;
- GitHub Actions CI.

[Explore GL-005 →](https://github.com/Gradensal/gl-005-agent-knowledge-trust-gate)

---

## AI Business Systems

Gradensal also builds applied systems exploring how AI fits into real organizational workflows.

### Marketing AI Workflow Architect

Decision-support system for determining the appropriate level of AI autonomy in marketing workflows.

The system separates:

- deterministic rules;
- AI-assisted reasoning;
- governance constraints;
- human judgment.

[Explore the project →](https://github.com/Gradensal/marketing-ai-workflow-architect)

### Process Deployment Loop

An end-to-end process-orchestration prototype combining BPMN, Python workers, API integration, human review, incident recovery, and measured outcomes.

[Explore the project →](https://github.com/Gradensal/process-deployment-loop)

---

## Engineering Principles

### Deterministic controls where predictability matters

Probabilistic AI reasoning and deterministic authorization do not need to be the same layer.

### Human authority where consequences require judgment

Human review should be meaningful rather than merely frequent.

### Observability before trust

Systems participating in consequential work should leave inspectable evidence of what occurred.

### Evidence before claims

Experiments should preserve actual outputs, tests, limitations, and reproducible results.

### Useful systems before unnecessary complexity

Architecture should serve the research or business problem rather than demonstrate technology for its own sake.

---

## How We Build

### BUILD → LEARN → SHOW

Each meaningful Gradensal project aims to produce:

- a functioning system;
- reproducible tests;
- understandable architecture;
- documented technical decisions;
- security and failure considerations;
- measurable experiment results where appropriate;
- explicit limitations;
- professional documentation.

---

## Project Maturity

Many repositories in this organization are public **research prototypes**.

They investigate architecture, governance, workflow, and AI product questions.

A research prototype should not automatically be interpreted as production-ready software.

Each repository documents its own:

- scope;
- architecture;
- tests;
- security assumptions;
- limitations;
- maturity;
- future work.

---

## Areas of Exploration

**Reliable AI agents**  
**Agent governance**  
**AI observability**  
**Intelligent automation**  
**Enterprise AI systems**  
**AI workflows**  
**Human-AI collaboration**  
**Applied AI product architecture**

---

## Gradensal

**Applied AI · Reliable Agents · Intelligent Workflows · Enterprise Automation**

🌐 [gradensal.com](https://gradensal.com)
