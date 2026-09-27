# <p align="center"> Shubham Rajendra Lagad</p>

<p align="center">
  <b>Technical Product Leader · AI Systems · Enterprise Platforms</b><br>
  <sub>Building privacy-preserving AI infrastructure and products for complex enterprise environments.</sub>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Now-Product%20%40%20Fiserv-0A66C2?style=flat-square" />
  <img src="https://img.shields.io/badge/Building-Clawwarden-6E40C9?style=flat-square" />
  <img src="https://img.shields.io/badge/Location-Pune,%20India-2EA44F?style=flat-square" />
  <img src="https://img.shields.io/badge/Open%20to-U.S.%20Opportunities-FF6B00?style=flat-square" />
</p>

---

I build products and systems at the boundary between **complex enterprise workflows and the infrastructure underneath them**.

In my product work, I operate across product discovery, APIs, architecture, cloud systems, and cross-functional delivery. At Fiserv, I work on a cloud-based branch and teller platform designed for 100+ target branches and supporting five banking cores through the Communicator Open API layer.

That work involves translating product requirements into capabilities that can operate consistently across different backend systems, shaping application-facing API and data schemas, and deciding where complexity should live across the application, integration layer, and underlying systems.

Outside my primary role, I build open-source AI systems focused on:

* Privacy-preserving AI infrastructure
* Local inference
* LLM evaluation
* Enterprise AI deployment
* Security and controlled data exposure

---

## Clawwarden — AI Privacy Gateway

<p>
  <a href="https://clawwarden.space"><img src="https://img.shields.io/badge/site-clawwarden.space-6E40C9?style=flat-square" /></a>
  <a href="https://github.com/clawwarden/clawwarden"><img src="https://img.shields.io/badge/source-github-181717?style=flat-square&logo=github&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/License-Apache_2.0-blue.svg?style=flat-square" />
</p>

**Creator & Lead Maintainer**

Clawwarden is an open-source, self-hosted gateway designed to sit between enterprise applications and external LLM providers, keeping sensitive information under enterprise control.

### Core architecture

* **Pre-flight PII tokenization:** Detects and tokenizes sensitive identifiers locally before requests leave the environment, then restores them on the response path.
* **Fail-safe processing:** Blocks requests when the privacy-processing path fails rather than allowing unprotected data through.
* **Tamper-evident audit logging:** Uses hash-chained, append-only records to support traceability of AI interactions.
* **Controlled detokenization:** Applies role-based access controls to determine when protected values can be restored.
* **LLM security controls:** Includes architectural mitigations for prompt injection, output handling, and sensitive-data exposure.

**Stack**

`FastAPI` `Microsoft Presidio` `spaCy` `Next.js` `PostgreSQL` `Redis` `Docker` `OpenTelemetry`

[Website](https://clawwarden.space) · [Source](https://github.com/clawwarden/clawwarden)

---

## Local LLM Arena

**Reproducible evaluation infrastructure for local models**

A local-first platform for comparing and evaluating multiple models without requiring evaluation data to leave the environment.

* Parallel evaluation of up to six local models
* Blind, randomized evaluation
* Pluggable LLM-as-a-judge workflows
* Latency and throughput measurement
* Structured evaluation artifacts
* Docker-based deployment and CI

**Stack**

`FastAPI` `React` `TypeScript` `Tailwind` `Ollama` `Docker`

[Repository](https://github.com/sammy995/Local-LLM-Arena)

---

## Local TTS Studio

**Local-first AI audio production**

A self-hosted TTS and podcast production system supporting:

* Multi-speaker timeline composition
* Voice-cloning workflows
* Music ducking
* Deterministic segment caching
* Fault-tolerant rendering
* Pluggable model backends

Designed to run locally for privacy and control.

[Repository](https://github.com/sammy995/Local-TTS-Studio)

---

## AI-Assisted Product Discovery

One of my ongoing areas of experimentation is using AI to change **how technical products are discovered and specified**, rather than simply using AI to generate text.

I developed a workflow that takes detailed product flows and use cases, generates interactive prototypes using an internal UI component library, and uses those prototypes to drive architecture and stakeholder feedback before formal requirements are finalized.

The approach reduced **concept-to-approved-specification time by 70%**.

The broader idea:

> **Make the product executable early enough that stakeholders can challenge behavior before engineering commits to implementation.**

---

## Open Source & Ecosystem Contributions

I contribute to open-source work around trustworthy and privacy-preserving AI infrastructure.

* **SantanderAI:** Contributor to the Mechanical Governance Framework.
* **Open-source AI tooling:** Building and maintaining infrastructure focused on privacy, evaluation, and controlled enterprise AI deployment.

---

## Enterprise Systems Background

My enterprise product experience comes primarily from complex financial systems, where correctness, integration boundaries, security, and operational constraints matter.

Areas I've worked across include:

* Core banking systems and enterprise APIs
* Branch and teller workflows
* Transaction processing
* RBAC and access control
* OFAC / CTR / BSA-related workflows
* Cloud modernization
* Legacy application decommissioning
* Enterprise system integration

This background shapes how I approach AI products: **not as isolated models, but as systems that have to operate reliably inside real organizations.**

---

## Writing

### AI Governance vs. AI Safety

Examining the distinction between governance mechanisms and technical safety systems.

### Building Privacy-Preserving Enterprise LLM Systems

Exploring architectures for using foundation models while retaining control over sensitive enterprise data.

### Designing Local-First LLM Evaluation Systems

Exploring reproducible model evaluation when data cannot be sent to external model providers.

---

## Background

**Current:** Product-focused role at Fiserv, working on enterprise branch and teller platform capabilities, APIs, and cross-system product design.

**Previous:** Senior Business Analyst – Fintech at Orion Innovation (Fiserv client) · Senior Technical Business Analyst at Globant (HSBC / First Direct client).

**Education:** MBA, Business Analytics — Hult International Business School · B.E., Computer Science — Savitribai Phule Pune University.

---

## Connect

<p>
  <a href="mailto:shubhamlagad@gmail.com">
    <img src="https://img.shields.io/badge/email-shubhamlagad@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/shubhamlagad/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://github.com/sammy995">
    <img src="https://img.shields.io/badge/GitHub-sammy995-181717?style=flat-square&logo=github&logoColor=white" />
  </a>
  <a href="https://clawwarden.space">
    <img src="https://img.shields.io/badge/Clawwarden-clawwarden.space-6E40C9?style=flat-square" />
  </a>
</p>
