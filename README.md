<div align="center">

# Kanhaiya Mehta

**CS undergrad at IIIT Dharwad · Applied AI, data systems and quantum computing**

I build AI systems that show their work: SQL agents whose every number traces back to a query,
RL environments for LLM agents, and quantum experiments run on real hardware.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/kanhaiya-mehta-b70aa7324)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:kanhaiyakumar76618@gmail.com)
[![Dev.to](https://img.shields.io/badge/Dev.to-0A0A0A?style=flat-square&logo=devdotto&logoColor=white)](https://dev.to/kanha_9650)
[![ORCID](https://img.shields.io/badge/ORCID-A6CE39?style=flat-square&logo=orcid&logoColor=white)](https://orcid.org/0009-0000-6458-9043)

</div>

---

### ⚡ Highlights

- 🏆 **3 hackathon podiums** and a **national finalist** spot (top 800 of 32,000+ teams, Meta × PyTorch × Hugging Face).
- 🧩 **Jenkins contributor:** 2 merged pull requests in Jenkins core and 5 more open.
- ⚛️ **Quantum research:** ran QAOA on IBM's 156-qubit `ibm_kingston` for a co-authored paper on database join ordering.
- 🔭 **Currently:** competing in the Solar Filament Segmentation Challenge (IEEE BigData Cup 2026) with a U-Net + YOLO11-seg ensemble tuned for Panoptic Quality.

---

### 🏆 Achievements

| Result | Event | Project |
|:--|:--|:--|
| 🥇 **1st place** | GND_0 VLSI Club Hackathon, IIIT Dharwad | |
| 🥈 **1st runner-up** | ZeroDay OSS Hacktoberfest 2026 (IIIT Dharwad × MLH × Google Gemma), Track PS1 *Talk to Your Data* | [DataMind](https://github.com/Kanhaiya76618/DataMind) |
| 🥉 **2nd runner-up** | HAL Hackathon | RagVault: offline, privacy-first RAG |
| 🎯 **National finalist**, top 800 of 32,000+ teams | Meta × PyTorch × Hugging Face OpenEnv Hackathon 2026 | [EnterpriseOps Arena](https://github.com/Kanhaiya76618/Meta-Hackathon) |

---

### 🧩 Open Source

**[Jenkins](https://github.com/jenkinsci/jenkins)**, the open-source automation server ([all my PRs](https://github.com/jenkinsci/jenkins/pulls?q=is%3Apr+author%3AKanhaiya76618)):

| Pull request | Area | Status |
|:--|:--|:--|
| [Canonicalize cached label expressions to share load statistics](https://github.com/jenkinsci/jenkins/pull/27428) | Java core | ![status](https://img.shields.io/github/pulls/detail/state/jenkinsci/jenkins/27428?label=&style=flat-square) |
| [Fix TypeError in breadcrumbs-overflow when logo item is missing](https://github.com/jenkinsci/jenkins/pull/27414) | Web UI, Vitest | ![status](https://img.shields.io/github/pulls/detail/state/jenkinsci/jenkins/27414?label=&style=flat-square) |
| [Fix quoted label atom and unquoted expression cache collision](https://github.com/jenkinsci/jenkins/pull/27457) | Java core | ![status](https://img.shields.io/github/pulls/detail/state/jenkinsci/jenkins/27457?label=&style=flat-square) |
| [Use XML 1.1 replacement mode in XStream2 PrettyPrintWriter](https://github.com/jenkinsci/jenkins/pull/27467) | Java core | ![status](https://img.shields.io/github/pulls/detail/state/jenkinsci/jenkins/27467?label=&style=flat-square) |
| [Bound console output DOM nodes during live tailing](https://github.com/jenkinsci/jenkins/pull/27434) | Web UI | ![status](https://img.shields.io/github/pulls/detail/state/jenkinsci/jenkins/27434?label=&style=flat-square) |
| [Show active system notifications badge on the System link](https://github.com/jenkinsci/jenkins/pull/27448) | Java, Jelly UI | ![status](https://img.shields.io/github/pulls/detail/state/jenkinsci/jenkins/27448?label=&style=flat-square) |

---

### 🚀 Selected Projects

| Project | What it does | Built with |
|:--|:--|:--|
| **[DataMind (Nexora)](https://github.com/Kanhaiya76618/DataMind)** | Ask Snowflake questions in plain English. A local Gemma 4 model writes the SQL; six layers of code check it, and every number in the answer is traced to the rows it came from. **94% (62/66)** on a hand-written benchmark over TPC-H (8.7M rows); 206 automated tests. | Python, FastAPI, Snowflake, DuckDB, Ollama, React |
| **[EnterpriseOps Arena](https://github.com/Kanhaiya76618/Meta-Hackathon)** | Multi-agent RL environment where IT, manager, finance and oversight agents run a simulated enterprise. Trained Qwen2.5-3B with GRPO and 4-bit LoRA on a single T4; peak episode score **+77%**. | PyTorch, TRL, Unsloth, OpenEnv |
| **[QAOA for Join Ordering](https://github.com/Kanhaiya76618/Qunatum-Research)** | Co-authored paper. Encodes a TPC-H Q5 join order as a 9-qubit QUBO: QAOA finds the optimum in simulation, while on IBM `ibm_kingston` the 263-layer transpiled circuit is indistinguishable from noise, which measures today's hardware gap. | Qiskit, Qiskit Runtime, IBM Quantum |
| **[The Quadratic Bet](https://github.com/Kanhaiya76618/the-quadratic-bet)** | Prices an option with quantum amplitude estimation against Monte Carlo. Under IBM noise the textbook estimate misses ($7.34); a noise-aware estimator recovers the fair price ($6.56 vs $6.58). Qollab × IonQ hackathon. | Qiskit, IonQ, JavaScript |
| **[Mutation Testing Pitfall](https://github.com/Kanhaiya76618/java-mutation-testing-research)** | Methods note showing why "tests added by a bug fix raise the mutation score" holds by construction, plus a PIT kill-matrix protocol that avoids the trap. 10-bug pilot on Apache Commons Lang; every reported number is generated from data. | Java, Maven, PIT, Python, LaTeX |
| **[FlowForge](https://github.com/Kanhaiya76618/log-sup_forge)** | Resolves supply-chain disruptions through a watcher → diagnosis → planner → verifier → human gate → executor pipeline, with OR-Tools CP-SAT and Monte Carlo risk scoring. [Live demo](https://log-sup-forge.vercel.app) | Python, FastAPI, OR-Tools, React |

More: [CaseGuard](https://github.com/Kanhaiya76618/CaseGuard) (fraud-investigation agent on TigerGraph) · [Amazon ML Challenge 2026](https://github.com/Kanhaiya76618/amazon-ml-entity-resolution) (entity resolution, 1.7M vs 10M records) · [PakkaHisaab](https://github.com/Kanhaiya76618/PakkaHisaab) (multimodal bookkeeping agent) · [The Locked Museum](https://github.com/Kanhaiya76618/quantum-odyssey-locked-museum) (quantum puzzle game)

---

### 🛠️ Tech Stack

<p>
  <img src="https://skillicons.dev/icons?i=py,ts,js,java,fastapi,react,nextjs,tailwind,postgres,pytorch,sklearn,docker,githubactions,linux" alt="Python, TypeScript, JavaScript, Java, FastAPI, React, Next.js, Tailwind CSS, PostgreSQL, PyTorch, scikit-learn, Docker, GitHub Actions, Linux" />
</p>

| Area | Tools I've shipped with |
|:--|:--|
| **Languages** | Python, TypeScript, JavaScript, Java, SQL |
| **AI / ML** | PyTorch, Hugging Face (Transformers, TRL, PEFT), Unsloth, scikit-learn, LightGBM, LangGraph, Ollama, Ultralytics YOLO |
| **Data** | Snowflake, DuckDB, PostgreSQL (Supabase), TigerGraph, pandas |
| **Backend & Web** | FastAPI, Pydantic, React, Next.js, Vite, Tailwind CSS, Three.js |
| **Quantum** | Qiskit, Qiskit Runtime (IBM Quantum), IonQ |
| **Tooling** | Docker, GitHub Actions, pytest, Vitest, Maven, PIT, LaTeX |
