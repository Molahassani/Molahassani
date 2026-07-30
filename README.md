[README(4).md](https://github.com/user-attachments/files/30556810/README.4.md)
<div align="center">

<img src="./assets/hero.svg" width="100%" alt="Mohammad Mahdi Molahassani — Medicine, Agentic AI, and Reliable Systems" />

<br/>

<a href="https://github.com/Molahassani"><img src="https://img.shields.io/github/followers/Molahassani?label=Follow&style=for-the-badge&logo=github&color=0B1220&labelColor=111827" alt="GitHub followers" /></a>
<a href="https://www.linkedin.com/in/mr-molahassani"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://orcid.org/0000-0001-9645-2607"><img src="https://img.shields.io/badge/ORCID-Research-A6CE39?style=for-the-badge&logo=orcid&logoColor=white" alt="ORCID" /></a>
<a href="http://www.mrmollahasani.ir/"><img src="https://img.shields.io/badge/Website-Visit-7C3AED?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website" /></a>

<br/><br/>

### Medical Student · AI Systems Builder · Researcher

Building AI systems that can **reason, retrieve evidence, use tools, verify outcomes, expose uncertainty, and explain decisions**.

<sub>Medicine × Agentic AI × Reliable Systems</sub>

</div>

---

## Currently Building

<table>
<tr>
<td width="68%" valign="top">

### 🛡️ IMMUNIS-X

**Portable Counterfactual Immunization for Heterogeneous LLM Agent Systems**

A reliability layer that learns from agent failures, validates structural repairs, and safely transfers them across different agent architectures.

```text
observe → replay → localize → repair → validate → transfer
```

> First milestone: a deterministic **time-travel debugger for tool-using agents**.

</td>
<td width="32%" valign="top">

**Status**  
`Active development`

**Focus**  
`Agent reliability`  
`Counterfactual replay`  
`Safe transfer`  
`Typed interventions`

**Core stack**  
`Python` `Pydantic`  
`LangGraph` `OpenTelemetry`  
`Docker` `OPA/Rego`

</td>
</tr>
</table>

---

## What I Work On

<table>
<tr>
<td width="33%" valign="top">

### 🤖 Agentic Systems

Agents that plan, use tools, recover from failures, and verify their own execution.

`Building`

</td>
<td width="33%" valign="top">

### 🩺 Healthcare RAG

Evidence-grounded clinical AI with provenance, uncertainty, and human review.

`Research track`

</td>
<td width="33%" valign="top">

### 🔍 Explainable Clinical AI

Testing whether natural-language explanations are faithful, useful, and safe.

`Research interest`

</td>
</tr>
</table>

---

## Technology Stack

<div align="center">

<img src="./assets/tech-stack.svg" width="100%" alt="Technology stack for reliable agentic AI systems" />

<br/>

`Python` · `FastAPI` · `LangGraph` · `Pydantic` · `PostgreSQL` · `Vector Search` · `Docker` · `Linux`

`OpenTelemetry` · `MCP` · `OPA/Rego` · `Evaluation` · `GraphRAG` · `Human-in-the-loop Systems`

</div>

---

## System Blueprint

```mermaid
flowchart LR
    H[Human / Clinician] --> A[AI Application]
    A --> P[Plan]
    A --> R[Retrieve Evidence]
    A --> T[Use Tools]
    P --> L[LLM Core]
    R --> L
    T --> L
    L --> V{Verify}
    V -->|pass| O[Evidence-grounded Output]
    V -->|uncertain| X[Abstain / Human Review]
    V --> E[Trace + Evaluation]
```

<div align="center">

`intent → plan → retrieve → act → validate → explain → learn`

</div>

---

## Research Direction

> **How can AI systems act in high-stakes environments while remaining inspectable, evidence-grounded, and uncertainty-aware?**

<div align="center">

`Agent reliability` · `RAG & GraphRAG` · `Clinical NLP` · `Faithfulness` · `Calibration` · `Human oversight`

</div>

<details>
<summary><strong>Featured research question</strong></summary>
<br/>
Can large language models explain health-related predictions without producing explanations that are merely plausible?
<br/><br/>
Evaluation: <code>faithfulness</code> · <code>evidence alignment</code> · <code>uncertainty</code> · <code>clinical usefulness</code>
</details>

---

## Engineering Principles

<table>
<tr>
<td width="33%" align="center">

### Evidence First

Prefer verifiable sources over confident-looking output.

</td>
<td width="33%" align="center">

### Uncertainty Visible

Calibrate, abstain, and escalate when confidence is not justified.

</td>
<td width="33%" align="center">

### Humans in Control

Design review points for consequential decisions and actions.

</td>
</tr>
</table>

---

<div align="center">

### Build systems, not demos.

**Reliable execution · Grounded evidence · Inspectable decisions**

<br/>

<a href="https://www.linkedin.com/in/mr-molahassani"><img src="https://img.shields.io/badge/Build_trustworthy_AI-Connect-7C3AED?style=for-the-badge&logo=linkedin&logoColor=white" alt="Connect on LinkedIn" /></a>
<a href="https://github.com/Molahassani?tab=repositories"><img src="https://img.shields.io/badge/Explore_my_work-Repositories-0EA5E9?style=for-the-badge&logo=github&logoColor=white" alt="Explore repositories" /></a>

<br/><br/>

<sub>Mohammad Mahdi Molahassani · Medicine × Agentic AI × Reliable Systems</sub>

</div>

<!--
Dynamic GitHub statistics are intentionally not displayed in the main profile.
The shared github-readme-stats Vercel endpoint can be rate-limited or return 503 errors,
and the original project now recommends maintained successors or a GitHub Actions workflow.
Keep the visible profile dependency-light; add generated local cards only when your profile
has enough original public repositories to produce meaningful language statistics.
-->
