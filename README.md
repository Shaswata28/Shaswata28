<!-- Shaswata28/Shaswata28 — Cyber-Industrial Engineering Dashboard -->

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=venom&color=0:080A12,35:17102B,70:3A124D,100:00F0FF&height=240&section=header&text=SHASWATA%20DAS&fontSize=64&fontColor=FFFFFF&fontAlignY=40&desc=SOFTWARE%20ENGINEERING%20%2F%2F%20FEDERATED%20AI%20%2F%2F%20SYSTEMS%20DESIGN&descSize=14&descAlignY=62&descColor=00F0FF&animation=twinkling&stroke=00F0FF&strokeWidth=1" alt="Shaswata Das — Engineering Dashboard" />

<br/>

<a href="https://github.com/Shaswata28">
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=17&duration=2600&pause=650&color=00F0FF&center=true&vCenter=true&width=850&height=55&lines=%24+initializing+engineering+environment...;Building+systems%2C+not+just+interfaces.;Federated+Medical+AI+%C3%97+Residual+SVD;Full-Stack+Products+%C3%97+Local+AI+%C3%97+Automation;Curiosity+in.+Working+systems+out." alt="Terminal introduction" />
</a>

<br/>

<a href="https://github.com/Shaswata28">
<img src="https://img.shields.io/badge/OPERATOR-SHASWATA_DAS-00F0FF?style=for-the-badge&labelColor=080A12" alt="Operator" />
</a>
<a href="https://github.com/Shaswata28?tab=repositories">
<img src="https://img.shields.io/badge/REPOSITORIES-EXPLORE-FF0055?style=for-the-badge&labelColor=080A12" alt="Explore repositories" />
</a>
<a href="https://github.com/Shaswata28?tab=followers">
<img src="https://img.shields.io/github/followers/Shaswata28?style=for-the-badge&label=NETWORK&color=7000FF&labelColor=080A12" alt="GitHub followers" />
</a>
<img src="https://komarev.com/ghpvc/?username=Shaswata28&style=for-the-badge&color=00F0FF&label=SIGNAL+DETECTED&labelColor=080A12" alt="Profile visits" />

<br/><br/>

<code>SOFTWARE ENGINEERING</code> &nbsp; <code>AI RESEARCH</code> &nbsp; <code>SYSTEMS THINKING</code>

<br/><br/>

<a href="#research-lab">RESEARCH</a> &nbsp; // &nbsp;
<a href="#project-archives">PROJECTS</a> &nbsp; // &nbsp;
<a href="#technical-stack">TECH STACK</a> &nbsp; // &nbsp;
<a href="#github-telemetry">GITHUB TELEMETRY</a>

</div>

---

## `00` / OPERATOR PROFILE

```text
┌──────────────────────────────────────────────────────────┐
│  USER       : Shaswata Das                               │
│  ROLE       : Software Engineer / AI-ML Researcher       │
│  INSTITUTION: East Delta University                      │
│  DEGREE     : B.Sc. in Computer Science                  │
│  INTERESTS  : Distributed AI, Product Engineering        │
│               Local LLMs, Automation, Systems Design     │
├──────────────────────────────────────────────────────────┤
│  DIRECTIVE                                               │
│  Turn ambitious ideas into useful, working systems.     │
└──────────────────────────────────────────────────────────┘
```

I build across the boundary between software engineering and applied AI — from full-stack applications and mobile products to privacy-preserving machine learning and locally orchestrated AI workflows.

I enjoy understanding how systems work, finding the bottlenecks, and engineering practical solutions rather than stopping at the prototype.

---

<a id="research-lab"></a>

## `01` / RESEARCH LAB

<details open>
<summary><strong>01.A — Federated Medical AI</strong></summary>

### Privacy-Preserving Glioma Segmentation

<code>FEDERATED LEARNING</code> <code>MEDICAL VLMs</code> <code>NON-IID DATA</code> <code>RESIDUAL SVD</code>

Investigating communication-efficient federated learning for multimodal brain MRI segmentation across heterogeneous clinical clients, exploring LLaVA-Med, MedGemma, parameter-efficient adaptation, and Residual SVD-based aggregation.

| Research component | Approach |
|---|---|
| Clinical data | BraTS multimodal brain MRI |
| Distributed training | Federated learning across non-IID clients |
| Model adaptation | LoRA / parameter-efficient fine-tuning |
| Aggregation | Residual SVD and low-rank updates |
| Primary objective | Communication efficiency and privacy-aware collaboration |

```mermaid
flowchart TB
    subgraph CLIENTS["01 / DISTRIBUTED CLINICAL CLIENTS"]
        direction LR
        A["Client Alpha<br/>Local MRI Training"]
        B["Client Beta<br/>Local MRI Training"]
        C["Client Gamma<br/>Local MRI Training"]
    end

    subgraph SERVER["02 / AGGREGATION PIPELINE"]
        D["Local Model Updates"]
        E["Residual SVD"]
        F["Global Adapter<br/>Reconstruction"]
    end

    G["03 / GLOBAL MODEL"]

    A --> D
    B --> D
    C --> D
    D --> E --> F --> G
    G -. "Next training round" .-> CLIENTS

    style A fill:#101522,stroke:#00F0FF,color:#FFFFFF
    style B fill:#101522,stroke:#00F0FF,color:#FFFFFF
    style C fill:#101522,stroke:#00F0FF,color:#FFFFFF
    style D fill:#17102B,stroke:#7000FF,color:#FFFFFF
    style E fill:#3A124D,stroke:#FF0055,color:#FFFFFF
    style F fill:#17102B,stroke:#7000FF,color:#FFFFFF
    style G fill:#101522,stroke:#00F0FF,color:#FFFFFF
```

*Architecture illustration — conceptual workflow, not a claim of a deployed clinical system. Federated learning alone does not guarantee privacy; that depends on the implementation and additional safeguards.*

</details>

---

<a id="project-archives"></a>

## `02` / PROJECT ARCHIVES

<text>Selected engineering projects spanning campus fintech, event management, mobile productivity, and applied AI.</text>

<table>
<tr>
<td width="50%" valign="top">

### `01` / EDU-COIN

**Campus Digital Token Ledger**

<code>REACT</code> <code>NODE.JS</code> <code>SUPABASE</code>

A university payment ecosystem for student wallets, campus purchases, vendor transactions, and administrative analytics.

[↗ Explore repository](https://github.com/Shaswata28/EDU-COIN)

</td>
<td width="50%" valign="top">

### `02` / EVENTFLOW CRM

**Event Operations Engine**

<code>FULL-STACK</code> <code>DATABASES</code> <code>CRM</code>

An event-management platform designed to organize stakeholder pipelines, scheduling, team coordination, and event operations.

[↗ Explore repositories](https://github.com/Shaswata28?tab=repositories)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### `03` / STUDYMATE

**AI-Powered Learning Workspace**

<code>RAG</code> <code>LLMs</code> <code>LOCAL AI</code>

A learning assistant concept combining document retrieval, course organization, and AI-powered study workflows with local and hosted models.

[↗ Explore repositories](https://github.com/Shaswata28?tab=repositories)

</td>
<td width="50%" valign="top">

### `04` / FED-MEDVLM

**Federated Medical AI Research**

<code>PYTORCH</code> <code>LoRA</code> <code>SVD</code>

Research into communication-efficient federated training and multimodal brain tumor segmentation under heterogeneous client distributions.

[↗ Explore repositories](https://github.com/Shaswata28?tab=repositories)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### `05` / MOMENTUM

**Student Life OS**

<code>FLUTTER</code> <code>DART</code> <code>MOBILE</code>

A mobile productivity concept focused on routines, habit tracking, personal organization, and financial activity.

[↗ Explore repositories](https://github.com/Shaswata28?tab=repositories)

</td>
<td width="50%" valign="top">

### `06` / LENS-E UTHSOB 2.0

**National Photography Exhibition Portal**

<code>WEB ENGINEERING</code> <code>EVENT TECH</code>

A digital portal supporting photography contest submissions and event operations for a national photography exhibition.

[↗ Explore repositories](https://github.com/Shaswata28?tab=repositories)

</td>
</tr>
</table>

---

## `03` / ENGINEERING PRINCIPLES

<details>
<summary><strong>How I approach building systems</strong></summary>

- **Understand the system first.** Identify constraints, dependencies, and failure points before adding complexity.
- **Build for actual workflows.** Design around what users need to accomplish, not just what looks impressive in a demo.
- **Keep data and infrastructure deliberate.** Choose architectures based on maintainability, reliability, and deployment requirements.
- **Experiment with local AI.** Explore practical ways to run, orchestrate, and integrate language models.
- **Measure before claiming.** Distinguish working implementations, experiments, and future objectives.

</details>

---

<a id="technical-stack"></a>

## `04` / TECHNICAL STACK

<table>
<tr>
<td width="28%" valign="top"><strong>LANGUAGES</strong></td>
<td valign="top">

![Python](https://img.shields.io/badge/Python-080A12?style=flat-square&logo=python&logoColor=00F0FF)
![JavaScript](https://img.shields.io/badge/JavaScript-080A12?style=flat-square&logo=javascript&logoColor=F7DF1E)
![TypeScript](https://img.shields.io/badge/TypeScript-080A12?style=flat-square&logo=typescript&logoColor=3178C6)
![Dart](https://img.shields.io/badge/Dart-080A12?style=flat-square&logo=dart&logoColor=00F0FF)
![SQL](https://img.shields.io/badge/SQL-080A12?style=flat-square&logo=postgresql&logoColor=00F0FF)

</td>
</tr>
<tr>
<td valign="top"><strong>WEB & MOBILE</strong></td>
<td valign="top">

![React](https://img.shields.io/badge/React-080A12?style=flat-square&logo=react&logoColor=00F0FF)
![Next.js](https://img.shields.io/badge/Next.js-080A12?style=flat-square&logo=nextdotjs&logoColor=FFFFFF)
![Flutter](https://img.shields.io/badge/Flutter-080A12?style=flat-square&logo=flutter&logoColor=00F0FF)
![React Native](https://img.shields.io/badge/React_Native-080A12?style=flat-square&logo=react&logoColor=00F0FF)
![Node.js](https://img.shields.io/badge/Node.js-080A12?style=flat-square&logo=nodedotjs&logoColor=3FB950)

</td>
</tr>
<tr>
<td valign="top"><strong>DATA & BACKEND</strong></td>
<td valign="top">

![Supabase](https://img.shields.io/badge/Supabase-080A12?style=flat-square&logo=supabase&logoColor=3ECF8E)
![MongoDB](https://img.shields.io/badge/MongoDB-080A12?style=flat-square&logo=mongodb&logoColor=47A248)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-080A12?style=flat-square&logo=postgresql&logoColor=4169E1)

</td>
</tr>
<tr>
<td valign="top"><strong>AI & RESEARCH</strong></td>
<td valign="top">

![PyTorch](https://img.shields.io/badge/PyTorch-080A12?style=flat-square&logo=pytorch&logoColor=EE4C2C)
![Ollama](https://img.shields.io/badge/Ollama-080A12?style=flat-square&logo=ollama&logoColor=FFFFFF)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-080A12?style=flat-square&logo=huggingface&logoColor=FFD21E)
![Federated Learning](https://img.shields.io/badge/Federated_Learning-080A12?style=flat-square&logoColor=00F0FF)

</td>
</tr>
<tr>
<td valign="top"><strong>INFRASTRUCTURE</strong></td>
<td valign="top">

![Docker](https://img.shields.io/badge/Docker-080A12?style=flat-square&logo=docker&logoColor=2496ED)
![Linux](https://img.shields.io/badge/Linux-080A12?style=flat-square&logo=linux&logoColor=FCC624)
![Git](https://img.shields.io/badge/Git-080A12?style=flat-square&logo=git&logoColor=F05032)
![n8n](https://img.shields.io/badge/n8n-080A12?style=flat-square&logo=n8n&logoColor=FF6D5A)

</td>
</tr>
</table>

---

<a id="github-telemetry"></a>

## `05` / GITHUB TELEMETRY

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=Shaswata28&show_icons=true&hide_border=true&bg_color=080A12&title_color=00F0FF&text_color=C9D1D9&icon_color=FF0055&ring_color=7000FF" alt="GitHub profile statistics" />
<img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Shaswata28&layout=compact&hide_border=true&bg_color=080A12&title_color=00F0FF&text_color=C9D1D9&langs_count=8" alt="Most used programming languages" />

<br/><br/>

<img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=Shaswata28&bg_color=080A12&color=00F0FF&line=7000FF&point=FF0055&area=true&hide_border=true&custom_title=COMMIT%20SIGNAL%20%2F%2F%20ACTIVITY%20TRACE" alt="GitHub contribution activity graph" />

<br/><br/>

<img src="https://streak-stats.demolab.com?user=Shaswata28&theme=transparent&hide_border=true&ring=00F0FF&fire=FF0055&currStreakLabel=00F0FF&sideLabels=C9D1D9&currStreakNum=FFFFFF&sideNums=FFFFFF&dates=8B949E" alt="GitHub contribution streak" />

</div>

---

## `06` / CURRENT OPERATING DIRECTIVES

```text
[01] RESEARCH
     Explore federated medical AI and efficient model adaptation.

[02] ENGINEERING
     Build maintainable web and mobile applications.

[03] LOCAL AI
     Experiment with LLM inference, retrieval, and automation.

[04] SYSTEMS
     Understand deployment, infrastructure, and performance.
```

---

<div align="center">

### `BUILD INTENTIONALLY. UNDERSTAND DEEPLY. SHIP USEFUL THINGS.`

<code>END OF TRANSMISSION // SHASWATA28</code>

<br/><br/>

<a href="https://github.com/Shaswata28">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:00F0FF,50:7000FF,100:FF0055&height=5&section=footer" width="100%" alt="" />
</a>

</div>
