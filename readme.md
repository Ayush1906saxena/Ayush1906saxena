<div align="center">

# Ayush Saxena

**Software Engineer II @ JPMorgan Chase · Building [Warrantee](https://ayush1906saxena.github.io/warrantee/) · Bengaluru, India**

I build systems that ship software on their own and prove it works: AI agents that write the code, and the infrastructure that won't let them ship anything unproven.

[![Warrantee](https://img.shields.io/badge/Warrantee-Visit_the_site-9A1F1A?style=for-the-badge)](https://ayush1906saxena.github.io/warrantee/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ayush-saxena-a766b418b/)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ayushsaxena.official01@gmail.com)
[![LeetCode](https://img.shields.io/badge/LeetCode_650+-FFA116?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/)
[![AWS](https://img.shields.io/badge/AWS_Certified-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)](#)

</div>

---

## 🔏 &nbsp;Now building: [Warrantee](https://ayush1906saxena.github.io/warrantee/)

> **AI engineers that answer for your app.** You describe the fix or the feature; a team of AI agents plans it, writes it, tests it and reviews it, and nothing reaches your repository until it clears an evidence gate: the project's own tests, hidden checks written before the code, and an independent review. Built, proven, shipped.

```mermaid
flowchart LR
    A[Request] --> B[Acceptance tests<br/>written first]
    B --> C[Plan]
    C --> D[Agents write code<br/>in a sandbox]
    D --> E[Own tests +<br/>independent review]
    E --> F{Proof gate<br/>hidden tests + judge}
    F -- not proven --> D
    F -- proven --> G[Delivered to<br/>your GitHub]
```

**Under the hood** (private source, one month of building):

| | |
|---|---|
| 🧠 **Model gateway** | Every model call goes through one door: a learned router picks the model per task from real outcomes, slow calls are raced against a fast backup, and every token is costed. Model-agnostic: Claude, GPT and open models on any host. |
| 🛡️ **Policy gateway** | Every tool call (git, CI, Kubernetes, databases) passes an OPA policy check through MCP servers; agents never touch credentials. |
| ✅ **Proof gate** | A change ships only on evidence: hidden acceptance checks written before the code, the project's own suite, an independent reviewer from another model family, and a calibrated judge. |
| 🧪 **Sandboxed CI** | Every test run happens in an isolated Kubernetes job, across Python, Java, Node and Go. |
| 📏 **Graded on real code** | Benchmarked on real tasks from pydantic, gson, jsoup, SQLAlchemy, Hugo, ESLint and more, scored by each project's own upstream tests ([fixtures](https://github.com/Ayush1906saxena?tab=repositories&q=meridian-fixture)). |

```
721   commits since 20 Sep 2026
138k  lines of code: Java 21 / Spring Boot services, Python, TypeScript
 17   services and MCP tool servers on Kubernetes
317   test classes · 41 architecture decision records · 30 versioned prompts
 32   research passes: every engine change starts from the literature
```

![Java](https://img.shields.io/badge/Java_21-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![OPA](https://img.shields.io/badge/OPA-7D9199?style=flat-square&logo=openpolicyagent&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white)

---

### 🔨 &nbsp;Other things I've built

<table>
<tr>
<td width="50%" valign="top">

#### [ChaosGuard AI](https://github.com/Ayush1906saxena/ChaosGuard)
Autonomous security and chaos-engineering platform with a **3-tier LLM agent architecture**: static analysis, then 4 LangGraph-orchestrated agents, then 8 specialised agents for attack-chain construction and cascading-failure simulation. Fully local inference, zero API cost.

![Java](https://img.shields.io/badge/Java_21-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot_3-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)

</td>
<td width="50%" valign="top">

#### [ArchitectIQ](https://github.com/Ayush1906saxena/ArchitectIQ)
AI-powered system design academy: **174 lessons**, an adaptive AI interviewer, interactive failure labs and D3.js architecture diagrams, with an Ollama-backed quizzing engine.

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![D3.js](https://img.shields.io/badge/D3.js-F9A03C?style=flat-square&logo=d3dotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)

</td>
</tr>
</table>

---

### 💼 &nbsp;At work

> At JPMorgan Chase, I led the migration of the **LOANIQ financial platform** to Kubernetes with near-zero downtime, built **Workmate**, a developer productivity tool that provisions production environments in **under 2 hours** through automated Terraform and CI/CD pipelines, and unified **300+ interfaces** into a single deployment pipeline, **cutting release time by 90%**.

```
650+  LeetCode problems solved (DSA, DP, system design)
 90%  deployment time cut: 300+ interfaces unified into 1 CI/CD pipeline
 90%  query latency cut: Oracle OLTP/OLAP schema split for financial databases
< 2h  environment provisioning with Workmate (previously days of manual setup)
```

---

### 🛠️ &nbsp;Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=java,spring,python,ts,js,react,nextjs,threejs,d3&perline=9" alt="Languages and frameworks" />
  <br/>
  <img src="https://skillicons.dev/icons?i=kubernetes,docker,aws,terraform,postgres,redis,mongodb,jenkins,linux&perline=9" alt="Infrastructure" />
</p>

---

### 📈 &nbsp;GitHub

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Ayush1906saxena&show_icons=true&theme=github_dark_dimmed&hide_border=true&count_private=true&bg_color=00000000" alt="GitHub Stats" height="170"/>
&nbsp;&nbsp;
<img src="https://github-readme-streak-stats.herokuapp.com/?user=Ayush1906saxena&theme=github_dark_dimmed&hide_border=true&background=00000000" alt="GitHub Streak" height="170"/>

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Ayush1906saxena&theme=github-compact&hide_border=true&area=true" alt="Activity Graph" width="95%"/>

</div>

---

<div align="center">
<sub>Fintech platforms at JPMorgan Chase by day. Software that proves itself, by night.</sub>
</div>
