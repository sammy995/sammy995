<h1 align="center">Shubham Rajendra Lagad</h1>
<p align="center">
  <b>Product lead making LLMs safe to deploy where mistakes are expensive.</b><br>
  <sub>AI Safety · AI Governance · Privacy-Preserving LLM Systems</sub>
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Now-Senior%20AI%20PM%20%40%20Fiserv-0A66C2?style=flat-square" />
  <img src="https://img.shields.io/badge/Building-Clawwarden-6E40C9?style=flat-square" />
  <img src="https://img.shields.io/badge/Location-Pune,%20India-2EA44F?style=flat-square" />
  <img src="https://img.shields.io/badge/Open%20to-US%20roles%20%2F%20sponsorship-FF6B00?style=flat-square" />
</p>

---

Your team is already pasting customer data into ChatGPT. Banning it doesn't work. I build the layer that lets regulated enterprises actually **say yes to AI** — with the controls, audit trail, and proof that risk and compliance will sign off on.

~8 years shipping product inside banking, where a wrong output isn't a bug — it's a regulatory violation. Now I'm building for the exact moment **AI meets real money and real rules**.

---

## 🛡️ Clawwarden — the AI gateway regulated teams can actually deploy

<p>
  <a href="https://clawwarden.space"><img src="https://img.shields.io/badge/site-clawwarden.space-6E40C9?style=flat-square" /></a>
  <a href="https://github.com/clawwarden/clawwarden"><img src="https://img.shields.io/badge/source-github-181717?style=flat-square&logo=github&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/License-Apache_2.0-blue.svg?style=flat-square" />
  <img src="https://img.shields.io/badge/telemetry-zero-2EA44F?style=flat-square" />
</p>

A self-hosted proxy between your people and any LLM. It tokenizes every personal identifier *before the prompt leaves your network* (`Jane Smith → {{PERSON_1}}`), restores it per-role on the way back, and logs every request to a tamper-evident trail a regulator will accept.

> **The product bet:** the blocker to enterprise AI isn't capability — it's *"can legal sign off?"* Clawwarden is the yes.

- **Fail-safe by design** — if PII detection errors, the request is *blocked*, never sent in the clear. Safety is the default, not a config.
- **Tamper-evident audit** — hash-chained, append-only (WORM on Postgres). Any edit, reorder, or deletion breaks the chain and is provable.
- **Measured, not claimed** — 100% recall / 0% residual leak on the labeled eval corpus.
- **OWASP LLM Top 10 mapped** — prompt-injection guard (LLM01), output sanitization (LLM02), PII tokenization + secret scrubbing (LLM06).
- **No vendor lock** — bring your own key or run fully local (Ollama / OpenAI / Anthropic). You hold the keys and the data.

<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Presidio-0078D4?style=flat-square&logo=microsoft&logoColor=white" />
  <img src="https://img.shields.io/badge/spaCy-09A3D5?style=flat-square&logo=spacy&logoColor=white" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenTelemetry-425CC7?style=flat-square&logo=opentelemetry&logoColor=white" />
</p>

---

## 🚀 Also building

| Project | What it is |
|---|---|
| [**Local-LLM-Arena**](https://github.com/sammy995/Local-LLM-Arena) ⭐ | Privacy-first model comparison — blind A/B eval of 2–6 local models via Ollama, per-model hyperparameters, zero cloud. The eval problem for teams that can't ship prompts to a vendor. |
| [**Local-TTS-Studio**](https://github.com/sammy995/Local-TTS-Studio) ⭐ | Fully offline text-to-speech with voice design and cloning (Qwen3-TTS, GPU inference). |
| [**PDFQuery-VectorDB**](https://github.com/sammy995/PDFQuery-VectorDB) | RAG-based PDF Q&A over a vector DB. |
| [**ML-algorithms**](https://github.com/sammy995/ML-algorithms) | Core ML algorithms implemented from scratch in Python. |

---

## 🏦 Why a banking product background is an AI-safety edge

The hard part of safe AI isn't the model — it's deploying into systems that punish failure. I learned that environment the expensive way:

- Owned compliance-critical workflows — **CTR · BSA · KYC · OFAC** — where wrong output = legal exposure.
- Shipped **25+ banking API contracts** — the exact surface where models touch financial data.
- Built **IAM/RBAC from zero at Fiserv** — 30+ launch-critical roles; the access model safety rides on.
- Drove **50+ requirements with FCA/PRA regulatory traceability** at **HSBC UK**.
- 8 years (since 2017) on the gap between what AI demos promise and what survives an audit.

---

## ✍️ Writing

- **AI Governance vs AI Safety** — why conflating them is dangerous.
- **Building Privacy-Preserving Enterprise LLM Systems**
- **Designing Local-First LLM Evaluation Systems**

---

## 🧭 Now / background

- **Now:** Senior AI Product Manager, **Fiserv** (via Orion Innovation) — identity, governance & platform safety for North American banking.
- **Before:** Senior PM @ **HSBC UK** (Globant) · Product Owner @ **Fiserv** (Vivid) · data/app roles @ Air Dynamics, Accenture (since 2017).
- **Education:** MBA, Business Analytics — Hult International Business School (Dean's List) · B.E. CS — University of Pune.

---

## 🤝 Connect

<p>
  <a href="mailto:shubhamlagad@gmail.com"><img src="https://img.shields.io/badge/email-shubhamlagad@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/shubhamlagad/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/sammy995"><img src="https://img.shields.io/badge/GitHub-sammy995-181717?style=flat-square&logo=github&logoColor=white" /></a>
  <a href="https://clawwarden.space"><img src="https://img.shields.io/badge/Clawwarden-clawwarden.space-6E40C9?style=flat-square" /></a>
</p>

---

<p align="center"><i>Making AI safe to deploy where it's most expensive to get wrong.</i></p>
