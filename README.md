# Markets for Traders — Mechanism-First Financial Systems (Pillar III)

Governance-first · auditable · reproducible · human-accountable  
Built for **MBA / Master of Finance cohorts** and **professional trading / research practitioners** who need market-structure literacy under constraint.

This repository is **Pillar III** of our algo trading training suite:  
a market-by-market mechanism laboratory where the objective is not prediction — it is **understanding how markets actually work** when constraints bind.

---

## What this repository is

**Markets for Traders** is the governed home of a synthetic-first laboratory suite that teaches trading by teaching **market mechanism**.

Most trading education over-teaches “signals” and under-teaches what actually determines outcomes:

- microstructure and execution reality  
- curve / surface geometry as the true object of trade  
- carry, convexity, liquidity, and regime switching  
- constraint binding (leverage, margin, inventory, funding)  
- fragility, cascades, and forced deleveraging dynamics  
- governance discipline so results are reviewable and defensible  

This pillar is intentionally explicit about its limits:

- it does **not** promise deployable strategies  
- it does **not** claim alpha discovery  
- it does **not** treat backtests as evidence  

It is a mechanism-first teaching and research environment designed to be:

- deterministic under seed  
- synthetic-only (no external market data)  
- auditable via mandatory artifacts  
- structured for experimentation without parameter-fishing  

**Core premise:**  
**Capability ↑ ⇒ Risk ↑ ⇒ Controls ↑**

---

## Canonical links (aligned to this repo)

### Repository
- https://github.com/alexdibol/markets_for_traders

### Notebooks
- Folder: https://github.com/alexdibol/markets_for_traders/tree/main/notebooks

**Individual notebooks (GitHub)**
- CHAPTER 1: https://github.com/alexdibol/markets_for_traders/blob/main/notebooks/CHAPTER%201.ipynb
- CHAPTER 2: https://github.com/alexdibol/markets_for_traders/blob/main/notebooks/CHAPTER%202.ipynb
- CHAPTER 3: https://github.com/alexdibol/markets_for_traders/blob/main/notebooks/CHAPTER_3.ipynb
- CHAPTER 4: https://github.com/alexdibol/markets_for_traders/blob/main/notebooks/CHAPTER_4.ipynb
- CHAPTER 5: https://github.com/alexdibol/markets_for_traders/blob/main/notebooks/CHAPTER_5.ipynb
- CHAPTER 6: https://github.com/alexdibol/markets_for_traders/blob/main/notebooks/CHAPTER_6.ipynb
- CHAPTER 7: https://github.com/alexdibol/markets_for_traders/blob/main/notebooks/CHAPTER_7.ipynb
- CHAPTER 8: https://github.com/alexdibol/markets_for_traders/blob/main/notebooks/CHAPTER_8.ipynb
- CHAPTER 9: https://github.com/alexdibol/markets_for_traders/blob/main/notebooks/CHAPTER_9.ipynb
- CHAPTER 10: https://github.com/alexdibol/markets_for_traders/blob/main/notebooks/CHAPTER_10.ipynb

**Open in Colab**
- CHAPTER 1: https://colab.research.google.com/github/alexdibol/markets_for_traders/blob/main/notebooks/CHAPTER%201.ipynb
- CHAPTER 2: https://colab.research.google.com/github/alexdibol/markets_for_traders/blob/main/notebooks/CHAPTER%202.ipynb
- CHAPTER 3: https://colab.research.google.com/github/alexdibol/markets_for_traders/blob/main/notebooks/CHAPTER_3.ipynb
- CHAPTER 4: https://colab.research.google.com/github/alexdibol/markets_for_traders/blob/main/notebooks/CHAPTER_4.ipynb
- CHAPTER 5: https://colab.research.google.com/github/alexdibol/markets_for_traders/blob/main/notebooks/CHAPTER_5.ipynb
- CHAPTER 6: https://colab.research.google.com/github/alexdibol/markets_for_traders/blob/main/notebooks/CHAPTER_6.ipynb
- CHAPTER 7: https://colab.research.google.com/github/alexdibol/markets_for_traders/blob/main/notebooks/CHAPTER_7.ipynb
- CHAPTER 8: https://colab.research.google.com/github/alexdibol/markets_for_traders/blob/main/notebooks/CHAPTER_8.ipynb
- CHAPTER 9: https://colab.research.google.com/github/alexdibol/markets_for_traders/blob/main/notebooks/CHAPTER_9.ipynb
- CHAPTER 10: https://colab.research.google.com/github/alexdibol/markets_for_traders/blob/main/notebooks/CHAPTER_10.ipynb

### Book
- Folder: https://github.com/alexdibol/markets_for_traders/tree/main/book
- ABC PDF: https://github.com/alexdibol/markets_for_traders/blob/main/book/ABC_OF_TRADING.pdf
- Book PDF: https://github.com/alexdibol/markets_for_traders/blob/main/book/BOOK%20MARKETS%20FOR%20TRADERS.pdf
- Book notes: https://github.com/alexdibol/markets_for_traders/blob/main/book/readme.md

---

## Market index (10 governed notebooks)

Each chapter is one market mechanism laboratory (synthetic-first, constraint-first, execution-aware):

1) **Cryptos**  
2) **Oil and Commodities Trading**  
3) **FX Carry Trade**  
4) **Yield Curve Dynamics**  
5) **Credit Spreads**  
6) **Volatility Trading**  
7) **Equity Factors**  
8) **Order Flow Mechanism**  
9) **Cross-Asset Macro Coupling**  
10) **Cascading Stress**

---

## What every notebook enforces (non-negotiable)

This repository uses a strict “laboratory contract.” Every notebook:

- is **synthetic-first** (no external market data)
- is **deterministic under seed**
- models explicit **economic mechanisms** (carry, curve shape, liquidity, regimes, cascades)
- defines a **tradable surface** (curve / matrix / tensor) as the central object
- constrains the action space (agents pick from predefined actions only)
- includes a portfolio + execution environment with:
  - transaction costs
  - leverage limits
  - feasibility constraints and stop-if rules
- includes a baseline rule policy and an optional LLM policy (bounded, rationales only)
- runs a closed-loop backtest with diagnostics:
  - equity curve
  - regime plot
  - cost accumulation
  - action counts
  - interpretive table (what happened and why, mechanism-first)

This is not “process for process.”  
This is what makes market reasoning **defensible**.

---

## How to use this repository

Recommended learning posture:

1) Read the book chapter for the market first.  
2) Run the companion notebook **as-is** (no tuning).  
3) Inspect the diagnostic surfaces and constraint-binding events.  
4) Stress the system structurally (regimes, liquidity, leverage, shocks).  
5) Document failure modes (where the mechanism breaks).  
6) Only then modify **one mechanism at a time** and rerun.

**Operating rule:** If the “result” only holds when you ignore execution, liquidity, or constraints, then the mechanism is not understood.

---

## Shared governance spine (applies across this repo)

- **Generation ≠ verification**  
  Outputs are learning artifacts, not validated claims.

- **Facts vs assumptions discipline**  
  Mechanism definitions and assumptions must be explicit.

- **Scope and boundary control**  
  These labs are educational: no external data, no performance claims.

- **Auditability by design**  
  Runs must be reconstructible and reviewable.

- **Human accountability**  
  Responsibility never leaves the human professional.

- **Synthetic-first honesty**  
  These are controlled laboratories to understand structure, not “proof” about markets.

---

## Use of generative AI tools (transparency statement)

Generative AI tools may have been used to assist drafting, editing, formatting, or code scaffolding.

However:

- conceptual design  
- mechanism selection and economic framing  
- governance logic and control definitions  
- integration decisions  
- final editorial judgment and acceptance  

were **human-led, human-supervised, and human-approved** at all times.

The author assumes **full responsibility** for the content, structure, interpretation, and conclusions presented in this work.

---

## IMPORTANT DISCLAIMERS (read before use)

### Educational / Non-Reliance
All materials are provided **for educational and research purposes only**.  
Nothing in this repository constitutes:

- investment advice  
- trading advice  
- legal advice  
- tax advice  
- accounting or audit advice  
- compliance determinations  
- operational recommendations  

Qualified human professionals must review, verify, and approve any real-world use.

### Not verified
Unless explicitly stated otherwise in a particular artifact, treat all outputs, claims, calculations, citations, and conclusions as **Not verified**.

### Confidentiality and data hygiene
Do not paste confidential, proprietary, regulated, or personally identifying information into external systems.  
Use anonymization/redaction and **minimum-necessary** inputs by default.  
You are responsible for compliance with privacy, confidentiality, recordkeeping, and information security obligations.

### No fabricated sources or claims
Zero tolerance for invented citations, performance claims, fees, terms, or consequences.  
When evidence is missing, the correct output is a **verification task list**, not persuasive narrative.

---

## License (MIT)

This project is released under the **MIT License**.

**Copyright (c) 2026 Alejandro Reynoso**

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the “Software”), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

---

## Contact

Alejandro Reynoso  
Email: areynoso@yahoo.com  
GitHub: https://github.com/alexdibol
