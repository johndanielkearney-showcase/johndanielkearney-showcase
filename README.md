<div align="center">

# John Daniel Kearney

**AI Safety Researcher · Security-Native Alignment · Adversarial Evaluation**

[![Authensor](https://img.shields.io/badge/Authensor-org-171717?style=flat&logo=github&logoColor=white)](https://github.com/AUTHENSOR)
&ensp;
[![15 Research Lab](https://img.shields.io/badge/15_Research_Lab-org-171717?style=flat&logo=github&logoColor=white)](https://github.com/15-Research-Lab)
&ensp;
[![Portfolio](https://img.shields.io/badge/Portfolio-authensor.com-0A66C2?style=flat&logo=googlechrome&logoColor=white)](https://authensor.com)
&ensp;
[![Email](https://img.shields.io/badge/Email-john@authensor.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:john@authensor.com)

</div>

---

### What I work on

I look at AI alignment through the lens of offensive security. The same
kill chains, evasion techniques, and detection gaps that security teams
have dealt with for decades keep showing up in agentic AI systems, and
the safety community isn't making enough use of that overlap.

I'm building the mappings, tooling, and runtime infrastructure to close
that gap.

I run two GitHub orgs:
**[AUTHENSOR](https://github.com/AUTHENSOR)** (open-source agent safety
stack, 47K+ LoC, 1,300+ tests, 16 packages) and
**[15 Research Lab](https://github.com/15-Research-Lab)** (AI security
benchmarks, adversarial datasets, research papers, 7+ repos).


---

### Pre-prints

| Paper | DOI |
|:---|:---|
| **The Verbosity Premium: What RLHF-Induced Token Inflation Costs the AI Industry** | [10.5281/zenodo.19346709](https://zenodo.org/records/19346709) |
| **Grokking Has Finite Capacity: Measuring and Overcoming Limits on Simultaneous Algorithmic Discovery** | [10.5281/zenodo.19346536](https://zenodo.org/records/19346536) |
| **Side-Channel Exfiltration and Narrative Erosion in Frontier Language Models** | [10.5281/zenodo.19346069](https://zenodo.org/records/19346069) |

All through [15 Research Lab](https://github.com/15-Research-Lab).

---

### Projects

<table>
<tr><td width="50%" valign="top">

**Mapping Security Frameworks to Alignment**
- [ATT&CK to Alignment Rosetta Stone](https://github.com/15-Research-Lab/attack-alignment-rosetta): Bidirectional mapping of all 14 MITRE ATT&CK tactics to alignment failure modes. 20 technique-level cross-references, ATLAS bridge layer, OWASP Agentic Top 10 integration.
- [Hawthorne Protocol](https://github.com/AUTHENSOR/hawthorne-protocol): Can agents detect when they're being benchmarked? Study of evaluation integrity with a reference detector (22 indicators, 5 categories) and countermeasures.

</td><td width="50%" valign="top">

**Adversarial Evaluation**
- [Prompt Injection Benchmark](https://github.com/AUTHENSOR/prompt-injection-benchmark): 240 scored test cases across 7 threat categories. Pluggable scanner adapters for comparing safety tools.
- [AI SecLists](https://github.com/AUTHENSOR/ai-seclists): 2,000+ attack payloads in 10 categories (prompt injection, jailbreaks, memory poisoning, exfiltration, tool abuse). Encoding utilities for 18 formats and 10 mutation types.
- [Chainbreaker](https://github.com/AUTHENSOR/chainbreaker): Red-team harness for running structured attack campaigns against agent guardrails.

</td></tr>
<tr><td width="50%" valign="top">

**Agent Safety Infrastructure (AUTHENSOR)**
- [Authensor](https://github.com/AUTHENSOR/AUTHENSOR): Runtime agent safety stack. Synchronous policy engine (zero deps), Aegis content scanner (210+ rules), Sentinel behavioral monitor (EWMA/CUSUM), MCP gateway, approval workflows, SHA-256 hash-chained audit receipts. TS and Python SDKs, 8 framework adapters, 10/10 OWASP Agentic coverage. MIT licensed.

</td><td width="50%" valign="top">

**Post-Hoc Analysis**
- [Attack Surface Mapper](https://github.com/AUTHENSOR/attack-surface-mapper): Static analyzer for AI agent configs. Finds dangerous permission combos, maps to OWASP Agentic Top 10, outputs SARIF for GitHub Security.
- [Agent Forensics](https://github.com/AUTHENSOR/agent-forensics): Reconstructs decision trees from cryptographic receipt chains. 6 anomaly types, Mermaid visualizations.
- [Behavioral Fingerprinting](https://github.com/AUTHENSOR/behavioral-fingerprinting): Per-agent statistical profiles across 8 behavioral dimensions with drift detection (EWMA/CUSUM).

</td></tr>
</table>

---

### Research interests

<table>
<tr><td width="50%" valign="top">

**Adversarial Alignment**
- Modeling misalignment as a progressive threat actor through kill chain stages
- Formal mappings between security frameworks (ATT&CK, ATLAS) and alignment failure taxonomies
- Evaluation-awareness and benchmark gaming in frontier models
- Anti-forensics behaviors in autonomous agents

</td><td width="50%" valign="top">

**Agent Safety and Control**
- Policy-first behavioral controls for tool-using agents
- Cryptographic audit mechanisms for agentic decision chains
- Bypass-proof hook enforcement for agent tool calls
- Red-teaming methodology for multi-step agentic workflows

</td></tr>
</table>

---

### Background

I come from inventory database systems and penetration testing. That
background shapes how I think about AI safety: structured red-teaming,
threat modeling, and failure analysis applied to alignment and agent
control problems.

I also run a proprietary data pipeline (30 automated collectors, ~3M
records/month across prediction markets, DeFi, BGP, DNS, and other
domains) for cross-domain signal research.

---

### Where the work lives

| Org / Account | Focus | Scale |
|:---|:---|:---|
| **[AUTHENSOR](https://github.com/AUTHENSOR)** | Open-source agent safety stack | 47K LoC · 1,300+ tests · 16 packages · TS + Python SDKs |
| **[15 Research Lab](https://github.com/15-Research-Lab)** | AI security research and adversarial evaluation | 7+ repos · 3 pre-prints · 2,000+ attack payloads · 240 benchmark cases |

---

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)

</div>

<div align="center">
<p>Primary activity is under <a href="https://github.com/AUTHENSOR">AUTHENSOR</a> and <a href="https://github.com/15-Research-Lab">15 Research Lab</a>. This account serves as an index.</p>
</div>
