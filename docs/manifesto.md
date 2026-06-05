# The OpenEval Manifesto
## An Open Standard for AI Reliability Engineering
### Version 0.1
### Dated: 5th June, 2026

---

# Introduction

Artificial Intelligence is rapidly becoming part of the world's critical infrastructure.

AI systems now help people write code, diagnose diseases, approve loans, answer legal questions, resolve customer support issues, manage enterprise operations, and make business decisions.
The capabilities of AI systems have improved at an extraordinary pace.
Every few months, models become more capable.
Every year, AI systems become more autonomous.
Every day, organizations place more trust in AI.

Yet there is a fundamental problem.
While AI capabilities have advanced dramatically, AI reliability has not.
Organizations are deploying increasingly sophisticated AI systems without a common way to measure, evaluate, benchmark, compare, monitor, or improve their reliability.
The result is an industry-wide reliability gap.
A gap between what AI systems can do and what organizations can confidently trust them to do.
The OpenEval Project exists to close that gap.

---

# The Reliability Gap

Modern software engineering evolved through discipline.
The software industry did not become reliable because developers became smarter.
It became reliable because the industry created standards, practices, tools, and disciplines for measuring quality.

We created:
- Unit Testing
- Integration Testing
- Continuous Integration
- Continuous Delivery
- Monitoring
- Observability
- Site Reliability Engineering

These disciplines transformed software from unpredictable code into trusted infrastructure.

Today, every serious software organization understands reliability.
No engineering leader would deploy critical software without testing.
No platform team would operate production systems without monitoring.
No organization would accept software quality based solely on intuition.

Yet this is exactly how much of the AI industry operates today.
Organizations deploy AI systems without agreed reliability standards.
Teams frequently evaluate outputs manually.
Benchmarks are fragmented.
Evaluation methods vary widely.
Reliability metrics are inconsistent.
Trust is often based on anecdotal evidence rather than systematic measurement.

We are building increasingly powerful systems while lacking the reliability foundations that software engineering established decades ago.
This is the reliability gap.

---

# The Cost of Unreliable AI

Unreliable AI creates costs that are often invisible until they become catastrophic.

- A customer support system may provide incorrect policy information.
- A coding assistant may generate insecure code.
- A retrieval system may confidently answer using outdated information.
- A workflow agent may complete a task while introducing subtle errors.
- A compliance assistant may violate regulatory requirements.
- A multi-agent system may successfully execute hundreds of actions before making a critical mistake.

These failures are difficult because they often appear successful.

The infrastructure may function perfectly.
The API requests may succeed.
The latency may be acceptable.
The costs may remain within budget.
The system may still be wrong.

Traditional infrastructure metrics cannot answer the most important question:
Can this AI system be trusted?

Organizations need more than uptime.
They need confidence, evidence & reliability.

---

# AI Systems Are Different

Traditional software is deterministic.
Given the same inputs, traditional software generally produces the same outputs.

AI systems are probabilistic.
The same input may produce different outputs.
The same task may succeed in one situation and fail in another.

Modern AI systems are no longer simple model calls.
They consist of multiple interacting components:
- Models
- Prompts
- Retrieval Systems
- Knowledge Bases
- Tools
- Workflows
- Memory Systems
- Agents
- Human Feedback Loops

Reliability emerges from the interaction of these components.
Failure can occur anywhere.

A model may be correct while retrieval fails.
Retrieval may be correct while planning fails.
Planning may be correct while tool execution fails.

Every layer introduces uncertainty.
Every layer requires evaluation.
Every layer requires reliability engineering.

---

# Why Current Approaches Are Insufficient

The AI ecosystem has produced extraordinary innovation.

Models have improved.
Frameworks have matured.
Infrastructure has evolved.
However, evaluation remains fragmented.

Many solutions focus on specific providers.
Others focus on specific frameworks.
Some focus exclusively on prompts.
Others focus exclusively on observability.

Most organizations build custom evaluation pipelines.
Benchmarks are difficult to share.
Results are difficult to reproduce.
Reliability measurements are difficult to compare.

Every team invents its own language.
Every platform creates its own definitions.
Every vendor promotes its own methodology.

The industry lacks a shared foundation.
The software industry solved this problem through standards.
The AI industry must do the same.

---

# Introducing AI Reliability Engineering

We believe a new engineering discipline is emerging.
We call it AI Reliability Engineering.

**AI Reliability Engineering** is the discipline of measuring, testing, validating, benchmarking, monitoring, and continuously improving the trustworthiness of AI systems.

It exists at the intersection of:
- AI Engineering
- Software Engineering
- Quality Engineering
- Observability
- Evaluation Science
- Reliability Engineering

Its purpose is simple: To ensure that AI systems behave consistently, predictably, and safely in real-world environments.

AI Reliability Engineering is not a tool.
It is not a framework.
It is not a vendor product.

It is a discipline. A discipline that the industry increasingly requires.

---

# The Need For An Open Standard

No engineering discipline matures without shared standards.
Software engineering has standards.
Networking has standards.
Security has standards.
Observability has standards.

AI Reliability Engineering requires standards as well.
Organizations need common definitions.
They need common benchmarks.
They need common evaluation models.
They need common reliability metrics.

Without standards:
- Results cannot be compared.
- Benchmarks cannot be shared.
- Progress cannot be measured.
- Reliability cannot be trusted.

The future of AI reliability must be open.
Not controlled by a single vendor.
Not tied to a single model provider.
Not restricted to a single framework.

The future must belong to the ecosystem.

---

# The OpenEval Vision

**OpenEval exists to become the open standard for AI Reliability Engineering.**

Our vision is a future where every AI system can answer a simple question: How reliable is it?

Not through opinion.
Not through marketing.
Not through isolated demonstrations.

Through measurable evidence.
Through repeatable evaluation.
Through transparent benchmarks.
Through shared standards.

In that future, organizations can evaluate AI systems as rigorously as they evaluate software systems today.
Reliability becomes measurable.
Trust becomes quantifiable.
Progress becomes visible.

---

# OpenEval Principles

## Open:
The standard belongs to the community. No vendor owns AI reliability.

---

## Model Agnostic:
Reliability should be measurable regardless of model provider.

---

## Framework Agnostic:
Reliability should be measurable regardless of orchestration framework.

---

## Reproducible:
Evaluations should be repeatable and verifiable.

---

## Transparent:
Reliability measurements should be explainable.

---

## Benchmarkable:
Systems should be comparable using shared benchmarks.

---

## Observable:
Reliability requires visibility into behavior.

---

## Continuous:
Evaluation is not a one-time activity. Reliability must be continuously measured.

---

## Practical: 
Standards must help teams improve real-world systems.

---

## Community Governed:
The ecosystem should guide the evolution of the standard.

---

# The Future

We believe every production AI system will eventually include:
- Reliability Tests
- Benchmark Suites
- Regression Detection
- Evaluation Pipelines
- Reliability Metrics
- Continuous Monitoring
- Trust Reports

Just as modern software systems include:
- Unit Tests
- CI/CD Pipelines
- Monitoring
- Observability

The organizations that embrace AI Reliability Engineering will build systems that are more trusted, more resilient, and more effective.
The organizations that ignore reliability will eventually encounter the limits of capability without trust.

Reliability is not a feature.
Reliability is infrastructure.
Reliability is engineering.
Reliability is the foundation upon which trustworthy AI will be built.

---

# Our Mission

**The mission of The OpenEval Project is to establish the open standard for AI Reliability Engineering.**

To create a shared language.
To create shared benchmarks.
To create shared evaluation models.
To create shared reliability practices.

To help the industry move from demonstrations to dependable systems.
To ensure that the future of AI is not only powerful, but trustworthy.
The future of AI depends on reliability. 

The future of reliability should be open.