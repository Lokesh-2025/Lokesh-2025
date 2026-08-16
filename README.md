<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&width=650&lines=I+build+AI+infrastructure+%26+full-stack+products;MCP+servers+%C2%B7+RAG+systems+%C2%B7+quantum+hardware;178.8%C3%97+amplification+on+real+IBM+quantum+hardware;A+safety+gate+that+caught+4+real+bugs+on+real+hardware;Recent+CIS+grad+who+ships" alt="Typing SVG" />
  </a>
</p>

---

## 👋 About Me

I'm **Lokesh Pullakandam** — a full-stack & AI engineer and recent graduate from Rowan University. 🎓
I build things that matter: MCP servers, RAG systems, real-time data pipelines, and production-grade full-stack apps. 🛠️
I learn by doing and ship real projects — not toy demos. My work runs on real infrastructure and real hardware, and I check it before I claim it.
Currently based in NJ and open to full-stack & AI engineering roles — remote, hybrid, or on-site. 🌎

---

## 🚀 Featured Projects

### 🛡️ [quantum-verifier](https://github.com/Lokesh-2025/quantum-verifier)
> A safety gate between an AI-generated quantum circuit and real quantum hardware — checks whether a claimed result is actually real before a dollar gets spent.

- **35 tools, 41 tests** — semantic/topology/gate-synthesis checks, an auto-generated control-experiment method that isolates a real effect size without needing a known answer, and account/budget preflight checks for both IBM and IonQ
- **Caught 4 real bugs on real hardware, automatically, before any of them cost money:** a transpiler silently doubling gate counts and mispredicting noise, a gate family defaulting to retired hardware, an API key pointed at an unfunded account, and a cost estimate wrong by ~2x
- **First real hardware confirmation**: a graded series of entangling circuits on IonQ, checked, cost-estimated, budget-verified, and submitted for real — all 3 circuits confirmed correct on Forte-Enterprise-1, with a genuine finding along the way (more entanglement isn't automatically better on real hardware — proven with a control experiment, not assumed)
- Companion project to `quantum-hardware-mcp` below — carries over its general infrastructure, adds a mandatory correctness layer nothing else in this space has

**Stack:** `Python` `MCP SDK` `Qiskit` `IonQ` `IBM Quantum Runtime` `SQLite`

---

### ⚛️ [Quantum Hardware MCP Server](https://github.com/Lokesh-2025/quantum-hardware-mcp)
> Open-source MCP server connecting AI assistants directly to real IBM Quantum, IonQ, and AWS Braket hardware.

- **43 tools** — device intelligence, job lifecycle, pre-flight validation, calibration drift alerts, reproducibility scoring, quantum search, quantum chemistry
- **178.8× quantum amplitude amplification** on `ibm_fez` — first hardware-confirmed 4-way Pascal's Triangle collision: C(14,6) = C(15,5) = C(78,2) = 3003 simultaneously in one job (34% of shots landed on the exact target, 25× cleaner than noise)
- Discovered IBM's heavy-hex topology is an Ising lattice — built LNAA (Lattice-Native Amplitude Amplification) from scratch, using native RZZ+RX gates. No routing, no SWAP, no ancilla. Result: 27.78× → 178.8× across successive hardware runs
- Built `equality_oracle_search` — a two-register quantum circuit that finds collisions **without being told the answer first**. Found C(16,2)=C(10,3)=120 blind, on the first run
- Diagnosed a degree-4 qubit routing failure causing a 263→1,037 gate explosion; built `check_routing_overhead` to catch this before wasting QPU credits
- Built in collaboration with [Jack Woehr](https://github.com/jwoehr) (IBM Quantum veteran, Qiskit contributor) — he runs this server on his own machine
- Automated calibration snapshot pipeline across 19 backends every 2 hours, via GitHub Actions
- Listed on [Glama](https://glama.ai), [mcp.so](https://mcp.so), and [PulseMCP](https://pulsemcp.com)

**Stack:** `Python` `MCP SDK` `Qiskit` `IBM Quantum Runtime` `IonQ` `AWS Braket` `FastAPI` `SQLite` `Docker` `GitHub Actions`

---

### 🌐 [Quantum Hardware Web](https://github.com/Lokesh-2025/quantum-hardware-web)
> Visual frontend for running real quantum circuits on IBM hardware.

- Live device comparison, job submission, circuit playground, results history
- Talks directly to real quantum hardware — no simulated data behind any Run button
- Built on top of quantum-hardware-mcp via a thin FastAPI layer

**Stack:** `Next.js` `TypeScript` `Tailwind CSS` `FastAPI`

---

### 💳 [Stripe MCP Server](https://github.com/Lokesh-2025/stripe-mcp-server)
> Open-source MCP server connecting Claude to your Stripe account via natural language.

- 7 tools: customers, revenue, invoices, failed payments, subscriptions, refunds, disputes
- Idempotency keys on write operations — safe to retry, won't double-charge
- Pinned Stripe API version to prevent silent breakage on upstream changes
- Listed on Glama and mcp.so

**Stack:** `Node.js` `MCP SDK` `Stripe API` `Zod`

---

### 🧠 [Second Brain — Offline RAG System](https://github.com/Lokesh-2025/second-brain)
> A fully offline Retrieval-Augmented Generation system — no cloud, no API keys, total privacy.

- Local LLM inference via Ollama + ChromaDB vector store
- Wrote the evaluation harness first — tracking retrieval quality across independent failure modes (hit-rate vs ROUGE-L)
- Achieved **10/10 top-1 retrieval accuracy** on benchmark queries

**Stack:** `Python` `Ollama` `ChromaDB` `RAG` `SQLite`

---

### 🏨 [Multi-Property Motel Booking Platform](https://github.com/Lokesh-2025/lokesh-portfolio)
> Custom booking platform built for a real client — multi-property, live reservations.

- Scoped requirements directly with the client, built and deployed independently
- Cross-property availability logic, third-party reservation system integration (ASI WebRes)
- Mobile-first responsive design end to end

**Stack:** `Next.js` `TypeScript` `Tailwind CSS` `Vercel`

---

## 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)

**AI / ML**

![MCP](https://img.shields.io/badge/MCP-Protocol-58A6FF?style=flat)
![RAG](https://img.shields.io/badge/RAG-Systems-10B981?style=flat)
![Ollama](https://img.shields.io/badge/Ollama-Local%20LLM-black?style=flat)
![ChromaDB](https://img.shields.io/badge/ChromaDB-Vector%20DB-orange?style=flat)
![Qiskit](https://img.shields.io/badge/Qiskit-6929C4?style=flat&logo=ibm&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-API-635BFF?style=flat&logo=stripe&logoColor=white)

**Web / Backend**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)

**Infrastructure**

![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=github-actions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

## 📊 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Lokesh-2025&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
  &nbsp;&nbsp;
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Lokesh-2025&layout=compact&theme=tokyonight&hide_border=true&langs_count=7" />
</p>

---

## 🤝 Connect

<p>
  <a href="https://linkedin.com/in/lokesh-pullakandam">
    <img src="https://img.shields.io/badge/LinkedIn-Lokesh%20Pullakandam-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  &nbsp;
  <a href="https://lokesh-portfolio-blue.vercel.app">
    <img src="https://img.shields.io/badge/Portfolio-lokesh--pullakandam-000000?style=flat&logo=vercel&logoColor=white" alt="Portfolio" />
  </a>
</p>
