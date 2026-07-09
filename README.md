<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&width=650&lines=I+build+AI+infrastructure+%26+full-stack+products;MCP+servers+%C2%B7+RAG+systems+%C2%B7+quantum+hardware;178.8%C3%97+amplification+on+real+IBM+quantum+hardware;Recent+CIS+grad+who+ships" alt="Typing SVG" />
  </a>
</p>

---

## 👋 About Me

I'm **Lokesh Pullakandam** — a full-stack & AI engineer and recnce graduate from Rowan University. 🎓
I build things that matter: MCP servers, RAG systems, real-time data pipelines, and production-grade full-stack apps. 🛠️
I learn by doing and ship real projects — not toy demos. My ethaims.**
Currently based in NJ and open to full-stack & AI engineering roles — remote, hybrid, or on-site. 🌎

---

## 🚀 Featured Projects

### ⚛️ [Quantum Hardware MCP Server](https://github.com/Lokesh-2025/quantum-hardware-mcp)
> Open-source MCP server connecting AI assistants directly to lS Braket hardware.

- **34 tools** — device intelligence, job lifecycle, pre-flightting, calibration drift alerts, reproducibility scoring, quantum search, quantum chemistry
- **178.8× quantum amplitude amplification** on ibm_fez — firstcal collision: C(14,6) = C(15,5) = C(78,2) = 3003 simultaneously in one job (34% of shots on exact target, 25× cleaner than noise)
- Discovered IBM heavy-hex topology is an Ising lattice — scraped LNAA (Lattice-Native Amplitude Amplification) from scratchusing native RZZ+RX gates. No routing, no SWAP, no ancilla. Result: 27.78× → 178.8× across successive hardware runs
- Built `equality_oracle_search` — two-register quantum circuitngle collisions **without being told the answer first**. FoundC(16,2)=C(10,3)=120 blind on first run
- Diagnosed degree-4 qubit routing failure causing 263→1,037 gauting_overhead` to catch this before wasting QPU credits
- Built in collaboration with [Jack Woehr](https://github.com/jwoehr) (IBM Quantum veteran, Qiskit contributor) — he runs this server on his own machine
- Automated calibration snapshot pipeline across 19 backends evvention
- Listed on [Glama](https://glama.ai), [mcp.so](https://mcp.so), and [PulseMCP](https://pulsemcp.com)

**Stack:** `Python` `MCP SDK` `Qiskit` `IBM Quantum Runtime` `IonQ` `AWS Braket` `FastAPI` `SQLite` `Docker` `GitHub Actions`

---

### 🌐 [Quantum Hardware Web](https://github.com/Lokesh-2025/quantum-hardware-web)
> Visual frontend for running real quantum circuits on IBM hardd.

- Live device comparison, job submission, circuit playground wistory
- Talks directly to real quantum hardware — no simulated data behind any Run button
- Built on top of quantum-hardware-mcp via a thin FastAPI layer

**Stack:** `Next.js` `TypeScript` `Tailwind CSS` `FastAPI`

---

### 💳 [Stripe MCP Server](https://github.com/Lokesh-2025/strip
> Open-source MCP server connecting Claude to your Stripe account via natural language.

- 7 tools: customers, revenue, invoices, failed payments, subscriptions, refunds, disputes
- Idempotency keys on write operations — safe to retry, won't d
- Pinned Stripe API version to prevent silent breakage on upstream changes
- Listed on Glama and mcp.so

**Stack:** `Node.js` `MCP SDK` `Stripe API` `Zod`

---

### 🧠 [Second Brain — Offline RAG System](https://github.com/L
> A fully offline Retrieval-Augmented Generation system — no cloud, no API keys, total privacy.

- Local LLM inference via Ollama + ChromaDB vector store
- Wrote the evaluation harness first — tracking retrieval qualiindependent failure modes (hit-rate vs ROUGE-L)
- Achieved **10/10 top-1 retrieval accuracy** on benchmark queries

**Stack:** `Python` `Ollama` `ChromaDB` `RAG` `SQLite`

---

### 🏨 [Multi-Property Motel Booking Platform](https://github.com/Lokesh-2025/lokesh-portfolio)
> Custom booking platform built for a real client — multi-prope

- Scoped requirements directly with the client, built and deploently
- Cross-property availability logic, third-party reservation system integration (ASI WebRes)
- Mobile-first responsive design end to end

**Stack:** `Next.js` `TypeScript` `Tailwind CSS` `Vercel`

---

## 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?stColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&log

**AI / ML**

![MCP](https://img.shields.io/badge/MCP-Protocol-58A6FF?style=f
![RAG](https://img.shields.io/badge/RAG-Systems-10B981?style=flat)
![Ollama](https://img.shields.io/badge/Ollama-Local%20LLM-black
![ChromaDB](https://img.shields.io/badge/ChromaDB-Vector%20DB-orange?style=flat)
![Stripe](https://img.shields.io/badge/Stripe-API-635BFF?style=ite)
![Qiskit](https://img.shields.io/badge/Qiskit-6929C4?style=flat&logo=ibm&logoColor=white)

**Web / Backend**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&l
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?stoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?stColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)

**Infrastructure**

![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=github-actions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=

---

## 📊 GitHub Stats

<p align="center">
  <img height="165"
src="https://github-readme-stats.vercel.app/api?username=Lokeshokyonight&hide_border=true&count_private=true" />
  &nbsp;&nbsp;
  <img height="165"src="https://github-readme-stats.vercel.app/api/top-langs/?username=Lokesh-2025&layout=compact&theme=tokyonight&hide_border=true&langs_count=7" />
</p>

---

## 🤝 Connect

<p>
  <a href="https://linkedin.com/in/lokesh-pullakandam">
    <img src="https://img.shields.io/badge/LinkedIn-Lokesh%20Puogo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  &nbsp;
  <a href="https://lokesh-portfolio-blue.vercel.app">
    <img src="https://img.shields.io/badge/Portfolio-lokesh--poo=vercel&logoColor=white" alt="Portfolio" />
  </a>
</p>
