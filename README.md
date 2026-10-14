# Awesome-Artificial-Intelligence-Decision-Model
# Awesome-Artificial-Intelligence-Decision-Model

## Top Artificial Intelligence Decision Model Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Business Rules, Decision Automation & Causal Inference*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Artificial Intelligence Decision Models**. These tools enable organizations to encode business logic, automate high-volume decisions, and apply causal reasoning—ensuring every decision is consistent, auditable, and explainable.



**Examples** include Jev, InRule, DataRobot, Pega, FICO Platform, Decisions, Peak AI, Aera Technology, Progress Corticon, and causaLens (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, rule engines, and open causal ML—ideal for enterprises, data scientists, and developers seeking transparent, vendor-independent decision infrastructure.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## Sector Overview & Market Dynamics

The global Decision Intelligence and AI decision automation market is valued at approximately **$16B–$21B** (projected to reach $50B+ by the early 2030s with a 15–25% CAGR). The market structure is **moderately fragmented**—anchored by established enterprise giants (such as FICO, Pega, IBM, and Microsoft) for core mission-critical workflows, yet driven by an influx of innovative startups and open-source ecosystems specializing in agentic AI decision layers and causal ML rather than a single winner-take-all monopoly.



## SaaS/Hosted Platforms

| Product | Scale (Revenue / Valuation) | Description | Pricing | Free Tier / Trial Limits |
| :--- | :--- | :--- | :--- | :--- |
| **[FICO Platform](https://www.fico.com/)** | ~$15.6B Market Cap (~$1.7B ARR) | Enterprise decision management platform with advanced analytics, business rules (Blaze Advisor), and mathematical optimization. | Starting at ~$5,000/month ($60,000/year base platform license tier scaling by transaction volume) | 30-day evaluation trial available for Blaze Advisor upon sales qualification; free Community License for Xpress Optimization (max 5,000 variables) |
| **[Pega](https://www.pega.com/)** | ~$5.8B Market Cap (~$1.4B ARR) | AI-powered decisioning and workflow automation with real-time decision management and Customer Decision Hub. | Starting at $90/user/month (standard case management edition, billed annually) | 30-day free trial on Community Edition (self-extendable once for +15 days, total 45-day limit; 1 active instance) |
| **[DataRobot](https://www.datarobot.com/)** | ~$6.3B Valuation (Peak primary / ~$200M ARR) | Enterprise AI lifecycle platform with unified workbench for predictive and generative AI, MLOps, and decision intelligence. | Starting at ~$1,250/month ($15,000/year annual minimum contract scaling by AI units/modeling seats) | 30-day free trial; includes full workbench access, vector DBs, and standard modeling worker quota |
| **[Progress Corticon](https://www.progress.com/corticon)** | ~$1.6B Market Cap (Parent Progress Software / ~$1B ARR) | Business rules management system (BRMS) with visual decision modeling, testing, and real-time DMN execution. | Starting at ~$1,200/month ($14,400/year base server deployment tier, billed annually) | 90-day free evaluation trial via `CcLicense.jar`; includes Corticon Studio and Corticon Server with full modeling capabilities |
| **[Aera Technology](https://www.aera.io/)** | ~$350M–$400M Valuation (~$97M ARR) | Cognitive automation for enterprise decisions providing autonomous execution across supply chains, finance, and operations. | Starting at $500/user/month (typically requiring a 10-user minimum / $5,000/month plus deployment integration fees) | No free tier or self-serve trial; live custom pilot demonstration provided upon enterprise engagement |
| **[causaLens](https://causalens.com/)** | ~$250M Valuation (~$15M ARR) | Causal AI platform for enterprise decision intelligence featuring causal discovery, counterfactual reasoning, and decision engines. | Enterprise packages starting at ~$4,166/month ($50,000/year annual contract tier via AWS Marketplace or direct sales) | No self-service free tier; guided pilot trial and interactive cloud sandbox access provided upon qualified sales consultation |
| **[Decisions](https://decisions.com/)** | ~$150M Valuation (~$15M–$25M ARR) | No-code workflow, automation, and business rules engine featuring visual decision tables, flow designer, and process mining. | Starting at $483/month ($5,800/year entry tier; core enterprise platform typically starts at $2,500/month billed annually) | 14-day guided free trial; includes dedicated cloud sandbox instance, sample pre-loaded apps, and 30-min onboarding kickoff |
| **[Peak AI](https://peak.ai/)** | ~$119M+ Raised (Acquired by UiPath, 2025 / ~$10M ARR) | AI decision intelligence platform for commercial teams covering demand forecasting, pricing, and inventory optimization. | Essentials tier starting at ~$3,500/month ($42,000/year billed annually based on connected SKU models and data connectors) | No free tier or self-service trial; guided customized proof-of-concept available upon qualification |
| **[InRule](https://inrule.com/)** | Private Equity backed (OpenGate Capital / ~$15M ARR) | Enterprise decision automation platform with business rules, decision tables, and AI integration across cloud and on-prem. | Enterprise licensing starting at ~$4,166/month ($50,000/year billed annually based on server cores and execution volume) | 30-day free trial upon enterprise request; includes irAuthor access and irServer test evaluation |
| **[Jev](https://jev.io/)** | Early-stage / Seed (TypeSafe AI) | AI decision model with `Choice`, `Score`, and `Noul` primitives. Lightweight, fast, per-step decisions in agent workflows. Open-weight fine-tunes available (WebJev). | $0.042 / 1M input tokens (output tokens 100% free; prepaid credit packages start at $5.00) | No permanent free tier; initial access requires waitlist approval or minimum $5 prepaid credit pack |



## Open-Source GitHub Projects



- **[Ordo](https://github.com/Pama-Lee/Ordo)**  

  Open-source decision platform built in Rust — author, test, and govern business rules at scale. Features **platform workspace** (organizations, projects, server fleets, release center), **Studio** (visual flow editor, decision table editor, trace-driven testing, version history), and **Engine** (sub-microsecond rule execution, JIT-compiled, runs everywhere via HTTP, gRPC, WASM, CLI). Claims 1.63 µs interpreter, 50–80 ns JIT (Cranelift), 54k QPS HTTP single-thread. Docker Compose for full stack .



- **[IBM Decision Manager Open Edition](https://www.ibm.com/products/business-automation-manager-open-editions/decision-manager)**  

  Open-core, cloud-native decision automation platform using open standards (DMN). Features high-volume rule evaluation, event-driven containerized decision microservices, automatic API generation, and **MCP Server integration** so AI agents can directly consume decision services. Runs on OpenShift and Kubernetes . Related open-source projects at [DecisionsDev](https://github.com/DecisionsDev) .



- **[MindOT](https://pypi.org/project/mindot/)**  

  Decision engine for agent systems (MIT) providing structured reasoning for complex trade-offs. Features task decomposition (Project → Operation → Job → Task), hierarchical planning, and multiple decision methods including **Bayesian inference**, **MCDA** (multi-criteria decision analysis), **decision trees**, **rule engines**, and **ML evaluation** (AUC, F1, LogLoss) .



- **[OpenDecision](https://pypi.org/project/open-decision-ai/)**  

  Open-source decision engine for LLM workflows. Features `Choice`, `Binary`, and `Score` questions batched into single forward pass. Confidence-aware output with `abstain_threshold` for routing to human review. Python SDK, Docker, and in-process loading. Benchmarks: 0.932 accuracy on CLINC150, 0.923 on Banking77 .



- **[ADI (Agent Decision Intelligence)](https://github.com/dimgouso/adi-Agent-Decision-Intelligence)**  

  Python library for structured multi-criteria decisions (alpha). Deterministic ranking with weighted criteria, confidence-aware output, explainable decisions (criterion contributions, constraint reports, counterfactual guidance), scenario analysis, and feedback-driven learning. Ships **OpenAI and Anthropic tool schemas** out of the box for agent integration .



- **[DoWhy](https://github.com/py-why/dowhy)**  

  Leading open-source causal inference library (7,088 GitHub stars). Supports explicit modeling and testing of causal assumptions with unified language combining graphical models and potential outcomes. Python-native causal reasoning foundation .



- **[EconML](https://github.com/microsoft/EconML)**  

  Microsoft Research's causal ML library for estimating heterogeneous treatment effects. 3,721 GitHub stars. Foundation for uplift modeling and personalized decision-making .



- **[CausalML (Uber)](https://github.com/uber/causalml)**  

  Uplift modeling and causal inference with machine learning algorithms. 4,951 GitHub stars. Widely used for treatment effect estimation in business contexts .



- **[causal-learn](https://github.com/py-why/causal-learn)**  

  Causal discovery in Python with independence tests and score functions. Part of the py-why ecosystem alongside DoWhy .



- **[IBM DecisionsDev](https://github.com/DecisionsDev)**  

  Open-source projects, tools, and samples for IBM decision automation. 66 repositories including Rule Designer, ODM on Kubernetes, and MCP servers for decision intelligence .



- **[LogicForge](https://github.com/)**  

  Simplified system for defining, executing, and managing business rules and complex events declaratively. Provides rule engine, DMN engine, and CEP (Complex Event Processing) engine .



### Additional Strong Open-Source Options



- **[DoubleML](https://github.com/DoubleML/doubleml-for-py)** — Double Machine Learning in Python for causal inference with high-dimensional controls .

- **[CausalPy](https://github.com/pymc-labs/CausalPy)** — Causal inference in quasi-experimental settings (synthetic control, difference-in-differences) .

- **[Scikit-uplift](https://github.com/maks-sh/scikit-uplift)** — Uplift modeling in scikit-learn style .

- **[YLearn](https://github.com/DataCanvasIO/YLearn)** — Python package for causal inference and decision optimization .

- **[GoRules Zen-Engine](https://github.com/gorules/zen)** — Decision engine with JDM graphs, decision tables, and expression language .

- **[Datacendia Core](https://github.com/datacendia/datacendia-core)** — Open-source AI decision intelligence engine with multi-agent deliberation and immutable audit trails .

- Community **n8n** workflows for decision automation and rule-triggered actions.



**Frameworks for building custom systems**: Combine **Ordo** for high-performance rule execution with **DoWhy** or **EconML** for causal inference, **MindOT** for structured multi-criteria reasoning, **OpenDecision** for LLM-integrated decision routing, and **PostgreSQL** for persistence—creating a fully self-hosted, enterprise-grade decision model platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Decision models handling business logic must comply with applicable regulations (financial services, healthcare, etc.) and ensure decisions are explainable and auditable.

- Self-hosted open-source solutions require proper security hardening, rule governance, and ongoing maintenance. **Decision logic is business logic**—version control, testing, and approval workflows are essential for production rule engines. Causal inference requires domain expertise to validate assumptions; correlation-based ML is insufficient for counterfactual decisions.



---



**Made for decision architects, data scientists, business rules analysts, and developers building transparent decision intelligence solutions.**  

Let's make Artificial Intelligence Decision Models more open, data-driven, and explainable.
