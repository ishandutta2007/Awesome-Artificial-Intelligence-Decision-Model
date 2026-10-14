# Awesome-Artificial-Intelligence-Decision-Model
# Awesome-Artificial-Intelligence-Decision-Model

# Top Artificial Intelligence Decision Model Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Business Rules, Decision Automation & Causal Inference*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Artificial Intelligence Decision Models**. These tools enable organizations to encode business logic, automate high-volume decisions, and apply causal reasoning—ensuring every decision is consistent, auditable, and explainable.

**Examples** include Jev, InRule, DataRobot, Pega, FICO Platform, Decisions, Peak AI, Aera Technology, Progress Corticon, and causaLens (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, rule engines, and open causal ML—ideal for enterprises, data scientists, and developers seeking transparent, vendor-independent decision infrastructure.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Jev](https://jev.io/)**  
  AI decision model with `Choice`, `Score`, and `Noul` (probability of truth) primitives. Lightweight, fast, and designed for per-step decisions in agent workflows. Open-weight fine-tunes available including WebJev (Apache-2.0) .

- **[InRule](https://inrule.com/)**  
  Enterprise decision automation platform with business rules, decision tables, and AI integration. Features rule authoring, testing, and deployment across cloud and on-prem.

- **[DataRobot](https://www.datarobot.com/)**  
  Enterprise AI platform with unified experience for developing, delivering, and governing predictive and generative AI. Workbench, Registry, and Console for full lifecycle.

- **[Pega](https://www.pega.com/)**  
  AI-powered decisioning and workflow automation. Features real-time decision management, customer journey orchestration, and predictive analytics.

- **[FICO Platform](https://www.fico.com/)**  
  Decision management platform with advanced analytics, business rules, and optimization. Widely used in financial services for credit, fraud, and customer decisions.

- **[Decisions](https://decisions.com/)**  
  No-code workflow, automation, and rules engine. Features decision tables, workflow designer, and integrations for business process automation.

- **[Peak AI](https://peak.ai/)**  
  AI decision intelligence platform for commercial teams. Features demand forecasting, pricing optimization, and inventory decisions.

- **[Aera Technology](https://www.aera.io/)**  
  Cognitive automation for enterprise decisions. Features decision intelligence, data harmonization, and autonomous execution across supply chain, finance, and operations.

- **[Progress Corticon](https://www.progress.com/corticon)**  
  Business rules management system with decision modeling, testing, and deployment. Supports DMN standards and real-time decision services.

- **[causaLens](https://causalens.com/)**  
  Causal AI platform for decision intelligence. Features causal discovery, counterfactual reasoning, and decision optimization beyond correlation-based ML.

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
