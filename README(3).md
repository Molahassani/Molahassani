<div align="center">

<img src="./assets/hero.svg" width="100%" alt="Mohammad Mahdi Molahassani — Medicine, Agentic AI, and Reliable Systems" />

<br/>

<a href="https://github.com/Molahassani"><img src="https://img.shields.io/github/followers/Molahassani?label=Follow&style=for-the-badge&logo=github&color=0B1220&labelColor=111827" alt="GitHub followers" /></a>
<a href="https://www.linkedin.com/in/mr-molahassani"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://orcid.org/0000-0001-9645-2607"><img src="https://img.shields.io/badge/ORCID-Research-A6CE39?style=for-the-badge&logo=orcid&logoColor=white" alt="ORCID" /></a>
<a href="http://www.mrmollahasani.ir/"><img src="https://img.shields.io/badge/Website-Visit-7C3AED?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website" /></a>

<br/><br/>

**Medical Student · AI Systems Builder · Researcher**  
Building reliable AI that can **reason, retrieve evidence, use tools, verify, and explain**.

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

</td>
<td width="32%" valign="top">

**Status**  
`Active development`

**Focus**  
`Agent reliability`  
`Counterfactual replay`  
`Safe transfer`  
`Typed interventions`

**Stack**  
`Python` `Pydantic`  
`LangGraph` `OpenTelemetry`  
`Docker` `OPA/Rego`

</td>
</tr>
</table>

> First milestone: a deterministic **time-travel debugger for tool-using agents**.

---

## Featured Projects & Directions

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

Evaluating whether natural-language explanations are faithful, useful, and safe.

`Research interest`

</td>
</tr>
</table>

---

## Research

> **How can AI systems act in high-stakes environments while remaining inspectable, evidence-grounded, and uncertainty-aware?**

`Agent reliability` · `RAG & GraphRAG` · `Clinical NLP` · `Faithfulness` · `Calibration` · `Human oversight`

<details>
<summary><strong>Featured research question</strong></summary>
<br/>
Can large language models explain health-related predictions without producing explanations that are merely plausible?
<br/><br/>
Evaluation: <code>faithfulness</code> · <code>evidence alignment</code> · <code>uncertainty</code> · <code>clinical usefulness</code>
</details>

---

## Agentic AI

```mermaid
flowchart LR
    H[Human / Clinician] --> A[AI Application]
    A --> P[Plan]
    A --> R[Retrieve]
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

## Technology Stack

<div align="center">

<img src="./assets/tech-stack.svg" width="100%" alt="Technology stack architecture" />

<br/>

<img src="https://skillicons.dev/icons?i=python,fastapi,postgres,docker,linux,git,github,vscode" alt="Core engineering stack" />

<br/><br/>

`LangGraph` · `Pydantic` · `OpenTelemetry` · `MCP` · `OPA/Rego` · `Vector Search`

</div>

---

## GitHub Activity

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Molahassani&show_icons=true&theme=github_dark&hide_border=true&rank_icon=github" alt="GitHub statistics" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Molahassani&layout=compact&theme=github_dark&hide_border=true&langs_count=8" alt="Most used languages" />

<br/>

<img width="88%" src="https://github-readme-activity-graph.vercel.app/graph?username=Molahassani&theme=github-compact&hide_border=true&area=true" alt="Contribution activity graph" />

</div>

---

<div align="center">

### Build systems, not demos.

**Prefer evidence over confidence · Make uncertainty visible · Keep humans in control**

<br/>

<a href="https://www.linkedin.com/in/mr-molahassani"><img src="https://img.shields.io/badge/Let's_build_trustworthy_AI-Connect-7C3AED?style=for-the-badge&logo=linkedin&logoColor=white" alt="Connect on LinkedIn" /></a>

<br/><br/>

<sub>Medicine × Agentic AI × Reliable Systems</sub>

</div>
