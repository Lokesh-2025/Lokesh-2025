<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&width=650&lines=I+build+AI+infrastructure+%26+full-stack+products;MCP+servers+%C2%B7+RAG+systems+%C2%B7+quantum+hardware;178.8%C3%97+amplification+on+real+IBM+quantum+hardware;Recent+CIS+grad+who+ships" alt="Typing SVG" />
  </a>
</p>

---

## 👋 About Me

I'm **Lokesh Pullakandam** — a full-stack & AI engineer and recent Computer Information Science graduate from Rowan University. 🎓
I build things that matter: MCP servers, RAG systems, real-time data pipelines, and production-grade full-stack apps. 🛠️
I learn by doing and ship real projects — not toy demos. My ethos is simple: **proof over claims.**
Currently based in NJ and open to full-stack & AI engineering roles — remote, hybrid, or on-site. 🌎

---

## 🚀 Featured Projects

### ⚛️ [Quantum Hardware MCP Server](https://github.com/Lokesh-2025/quantum-hardware-mcp)
> Open-source MCP server connecting AI assistants directly to live IBM Quantum, IonQ, and AWS Braket hardware.

- **34 tools** — device intelligence, job lifecycle, pre-flight validation, credit-aware routing, calibration drift alerts, reproducibility scoring, quantum search, quantum chemistry
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
