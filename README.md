<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,100:2563EB&height=190&section=header&text=Soumitri%20Mukherjee&fontSize=44&fontColor=FFFFFF&fontAlignY=36&desc=AI%20Engineer%20%C2%B7%20Agentic%20AI%20%26%20LLM%20Systems&descSize=18&descAlignY=58" alt="Soumitri Mukherjee, AI Engineer, Agentic AI and LLM Systems" width="100%"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=19&duration=3200&pause=900&color=2563EB&center=true&vCenter=true&width=640&lines=I+build+multi-agent+systems+with+LangGraph;Tool+calling+%C2%B7+MCP+%C2%B7+RAG+%C2%B7+GraphRAG;Grounded+answers%2C+validated+outputs;Full-stack%3A+FastAPI+%2B+React+%2F+TypeScript" alt="I build multi-agent systems with LangGraph. Tool calling, MCP, RAG, GraphRAG. Grounded answers, validated outputs. Full-stack: FastAPI plus React and TypeScript."/>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/soumitri-mukherjee"><img src="https://img.shields.io/badge/LinkedIn-soumitri--mukherjee-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:mail.soumitri@gmail.com"><img src="https://img.shields.io/badge/Email-mail.soumitri%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://img.shields.io/badge/Based%20in-Paderborn%2C%20Germany-111827?style=flat-square&logo=googlemaps&logoColor=white" alt="Based in Paderborn, Germany"/>
  <img src="https://img.shields.io/badge/Open%20to-roles%20across%20Germany-16A34A?style=flat-square" alt="Open to roles across Germany"/>
</p>

---

### `> whoami`

```python
class Soumitri(Agent):
    role       = "AI Engineer @ Fraunhofer IAO · Research Assistant @ Paderborn University"
    education  = "M.Sc. Computer Science, Paderborn University"
    experience = "3 years building production React/TypeScript apps (Cognizant, LTIMindtree)"
    builds     = ["multi-agent workflows", "RAG & GraphRAG", "MCP servers", "LLM evaluation"]
    tools      = ["LangGraph", "FastAPI", "Pydantic", "React", "TypeScript", "Neo4j", "Kubernetes"]
    principles = {
        "LLM output": "validated before anyone sees it",
        "scores and severity": "computed in code, not guessed by the model",
        "uncertain cases": "routed to a human in the loop",
    }
    languages  = {"English": "C1", "German": "B1, improving"}
```

### How I build agents

```mermaid
flowchart LR
    Q([Question]) --> U[Understand<br/>structured output]
    U --> R{Route}
    R -->|search| W[Web & docs agents]
    R -->|graph| G[GraphRAG<br/>Neo4j]
    R -->|tools| T[Tool calls<br/>MCP]
    W --> V[Validate<br/>evidence & schema]
    G --> V
    T --> V
    V -->|confident| A([Grounded answer])
    V -->|uncertain| H[Human in the loop]
    H --> A
```

### Impact so far

<table>
  <tr>
    <td align="center" width="25%"><h2>~60%</h2><sub>less time and manual effort in supplier risk assessments, with a multi-agent LangGraph workflow</sub></td>
    <td align="center" width="25%"><h2>94% / 90%</h2><sub>recall at precision for insider-threat signal extraction in the government-funded AeroKI project</sub></td>
    <td align="center" width="25%"><h2>93.44%</h2><sub>micro-average score on 200 stratified samples in my master's thesis on agentic supplier risk evaluation</sub></td>
    <td align="center" width="25%"><h2>~80×</h2><sub>faster rendering of a core UI flow in a telecom customer portal, with ~50% shorter load time</sub></td>
  </tr>
</table>

### Featured work

| | Project | What it does |
|:-:|---|---|
| 🛠️ | **[troubleshooting-kubernetes-issues-agent](https://github.com/SoumitriM/troubleshooting-kubernetes-issues-agent)** | Investigates Kubernetes incidents, asks follow-up questions, and recommends fixes from the official docs and historical GitHub incidents. Built with LangGraph, GraphRAG on Neo4j, conversation memory, FastAPI and React |
| 🛡️ | **[mitre-attack-mapping](https://github.com/SoumitriM/mitre-attack-mapping)** | Turns CVEs into evidence-grounded attack chains mapped to MITRE ATT&CK, with a CLI and a FastAPI service backed by Neo4j |
| 🔭 | **[artificial-tweet-analysis-with-binoculars](https://github.com/SoumitriM/artificial-tweet-analysis-with-binoculars)** | Analysis of AI-generated tweets with the [Binoculars](https://arxiv.org/abs/2401.12070) zero-shot detector (original method by Hans et al.) |
| 📚 | **[glossary-app-frontend](https://github.com/SoumitriM/glossary-app-frontend)** · **[backend](https://github.com/SoumitriM/glossary-app-backend)** | A university-wide English–German terminology platform used with DeepL, with automated tests, CI/CD and production deployment |

<details>
<summary><b>Also at work</b> (not public)</summary>
<br/>

- **Supplier cybersecurity risk platform** (Fraunhofer IAO). Specialised agents for web search, document discovery and evidence extraction, combining security, compliance and OSINT data into automated vendor risk assessments.
- **Insider-threat signal extraction** (AeroKI). A two-stage LLM system with deterministic severity scoring, confidence gating and human-in-the-loop review.
- **Research knowledge graph** (Paderborn University). Extracting and linking metadata for a university-wide graph of academic publications.
- **Disinformation detection** (Paderborn University). A real-time pipeline over Twitter and Bluesky streams, plus synthetic tweet datasets generated with multiple LLMs to train bot-tweet classifiers.
- **GenUI** (Paderborn University & OPTANO). An open-source RAG assistant that answers questions from an optimisation platform's technical documentation.

</details>

### Toolbox

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,ts,js,fastapi,nodejs,react,nextjs,tailwind,materialui&perline=9" alt="Python, TypeScript, JavaScript, FastAPI, Node.js, React, Next.js, Tailwind CSS, Material UI"/>
  <br/>
  <img src="https://skillicons.dev/icons?i=postgres,mongodb,elasticsearch,graphql,docker,kubernetes,gcp,githubactions,linux&perline=9" alt="PostgreSQL, MongoDB, Elasticsearch, GraphQL, Docker, Kubernetes, Google Cloud, GitHub Actions, Linux"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangGraph"/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain"/>
  <img src="https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=anthropic&logoColor=white" alt="MCP"/>
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face"/>
  <img src="https://img.shields.io/badge/Neo4j-4581C3?style=for-the-badge&logo=neo4j&logoColor=white" alt="Neo4j"/>
  <img src="https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white" alt="Pydantic"/>
  <img src="https://img.shields.io/badge/Claude%20Code-D97757?style=for-the-badge&logo=claude&logoColor=white" alt="Claude Code"/>
</p>

### Contribution graph, eaten

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/SoumitriM/SoumitriM/output/github-snake-dark.svg"/>
    <img src="https://raw.githubusercontent.com/SoumitriM/SoumitriM/output/github-snake.svg" alt="Animated snake eating the GitHub contribution graph"/>
  </picture>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2563EB,100:0F172A&height=110&section=footer" alt="" width="100%"/>
</p>
