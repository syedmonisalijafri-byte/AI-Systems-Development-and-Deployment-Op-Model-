# AI Systems Development and Deployment Operating Model (UK Public Sector)  
## Evaluation for Validation and Verification with Testing (E2VT)

**Version:** Draft  
**Status:** 1.0 (Peer-review)

---

## Table of Contents
- [Foreword](#foreword)
- [Who is this for?](#who-is-this-for)
- [Executive Summary](#executive-summary)
- [Chapter 1: Context](#chapter-1-context)
  - [1.1 Importance of evaluation for AI resilience and trust](#11-importance-of-evaluation-for-ai-resilience-and-trust)
  - [1.2 Challenges and opportunities](#12-challenges-and-opportunities)
- [Chapter 2: Vision, Mission and Objectives](#chapter-2-vision-mission-and-objectives)
  - [2.1 Vision and aim](#21-vision-and-aim)
  - [2.2 Pillars (Principles)](#22-pillars-principles)
- [Chapter 3: Operationalising AI Assurance](#chapter-3-operationalising-ai-assurance)
  - [3.1 Governance and accountability](#31-governance-and-accountability)
  - [3.2 Evaluation controls and documentation](#32-evaluation-controls-and-documentation)
  - [3.3 Managing AI risk](#33-managing-ai-risk)
  - [3.4 Secure configuration and shared capabilities](#34-secure-configuration-and-shared-capabilities)
  - [3.5 Data assets and quality](#35-data-assets-and-quality)
  - [3.6 Information and data security](#36-information-and-data-security)
  - [3.7 Model assurance and supply-chain risk](#37-model-assurance-and-supply-chain-risk)
  - [3.8 Threat information and security](#38-threat-information-and-security)
  - [3.9 Monitoring within organisations](#39-monitoring-within-organisations)
  - [3.10 Response preparation](#310-response-preparation)
  - [3.11 Incident response](#311-incident-response)
  - [3.12 Incident recovery and lessons learned](#312-incident-recovery-and-lessons-learned)
  - [3.13 Detection at scale](#313-detection-at-scale)
  - [3.14 Key Performance Indicators (KPIs)](#314-key-performance-indicators-kpis)
  - [3.15 AI assurance and partnerships](#315-ai-assurance-and-partnerships)
- [Chapter 4: Evaluation for Validation and Verification with Testing (E2VT)](#chapter-4-evaluation-for-validation-and-verification-with-testing-e2vt)
  - [4.1 Evidence Catalogue (what to collect)](#41-evidence-catalogue-what-to-collect)
  - [4.2 Test Harnesses & Datasets](#42-test-harnesses--datasets)
  - [4.3 Operating Model (Lifecycle with Governance Gates)](#43-operating-model-lifecycle-with-governance-gates)
- [Glossary](#glossary)
- [Appendix A: Alignment with already published resources](#appendix-a-alignment-with-already-published-resources)

---

## Foreword

Artificial Intelligence (AI) is transforming the way the UK public sector delivers services, analyses data for informed decision-making, and drives innovation. The **AI Opportunities Action Plan** explains that AI can enable economic growth and better public services, but must be used **safely, fairly and transparently**.

Evaluation is central to ensuring that AI works as intended, is trustworthy, and generates measurable public value. Trust must be built through carefully instrumented, evidence-based, and rigorous validation and verification conducted iteratively.

This document outlines how government bodies can embed evaluation throughout the AI lifecycle, combining:

- **Systemic verification**: assurance claims are backed by auditable evidence throughout the lifecycle.
- **Impact evaluation**: measuring benefits and mitigating harm.

> Impact evaluation for AI interventions is described in the **Magenta Book**.

This operating model provides an actionable, evidence-driven scheme for selecting, configuring, and operationalising **Evaluation for Validation and Verification with Testing (E2VT)** for AI-enabled systems.

It draws on:
- UK AI Assurance Roadmap (CDEI)
- NIST AI RMF
- ISO/IEC 42001 (AI Management Systems)
- Algorithmic Transparency Recording Standard (ATRS)
- HM Treasury’s Magenta Book

And aligns to:
- Service Manual and AI Playbook (Q1 2025)
- Digital Service Standards
- AI Assurance Guidance (Q1 2024)
- Risk Awareness Toolkit (Q3 2025)

---

## Who is this for?

Service owners, product owners, principal technologists, product & delivery leads, data scientists/ML engineers, safety/risk/assurance teams, commercial/procurement teams, and DDaT governance and technology oversight roles.

> Appendix A outlines alignment with the AI Playbook and Service Manual, and differences from the Magenta Book.

---

## Executive Summary

Artificial Intelligence (AI) offers significant potential to transform public services, but its deployment necessitates robust assurance to mitigate risks such as **bias, lack of transparency, and potential harm**.

This strategy introduces the **Evaluation for Validation and Verification with Testing (E2VT)** framework: a comprehensive approach for evaluation-driven AI development and deployment. E2VT emphasises context-specific, risk-aware assurance supported by governance and runtime controls.

### Key Themes

- **Context:** AI evaluation is essential for resilience and trust.
- **Approach:** Vision, mission, objectives driven by 7 pillars:
  1. Risk proportionate trustworthy and safe AI
  2. Evidence-first evaluation by design
  3. Model-agnostic verification and validation
  4. Secure By Design
  5. Human-centred impact-focused deployment
  6. Reproducible and auditable processes
  7. Continuous improvement
- **Operationalising AI Assurance:** governance, documentation, risk tiering, controls, secure configuration, supply chain, and monitoring.
- **E2VT Framework:** five components:
  - Standardised evidence catalogue
  - Use-case-specific test harnesses
  - Offline + online evaluation
  - Continuous monitoring + incident response
  - Governance gates preventing release without evidence

Ultimately, this strategy aims to foster a public sector that develops, deploys, and scales AI systems that are **trustworthy, safe, and deliver measurable public value**, guided by evaluation throughout the AI lifecycle.

---

# Chapter 1: Context

AI Assurance refers to the systematic, evidence-based evaluation of AI systems to establish and communicate confidence in their safety, fairness, robustness, and compliance.

It blends:
- **Technical assurance**: evaluation, validation, verification, and testing
- **Socio-technical assurance**: explainability, ethics, governance, human oversight

## 1.1 Importance of evaluation for AI resilience and trust

AI systems can deliver personalised services, optimise resource allocation and enhance decision-making. The UK Government recognises that trust is a prerequisite for adoption and that AI must be safe, secure and fair.

Without robust evaluation, AI systems may:
- amplify biases
- infringe rights
- erode public trust

## 1.2 Challenges and opportunities

AI development moves quickly and relies on complex data, models and supply chains.

Traditional approaches are often insufficient due to:
- lack of transparency
- unpredictable behaviour
- evolving performance after deployment

Public sector challenges include:
- **Rapid technological change**
- **Complex socio-technical systems**
- **Data quality and bias**
- **Transparency and explainability**
- **Lack of granular approaches** to selecting/configuring technical methods

Despite these challenges, AI offers significant opportunities. The UK’s AI assurance ecosystem can mature similar to cyber-security assurance.

---

# Chapter 2: Vision, Mission and Objectives

## 2.1 Vision and aim

**Vision:** A public sector that develops, deploys, and scales AI in ways that are trustworthy, safe and deliver measurable public value.

**Mission:** Build an evaluation-driven AI development and deployment strategy combining:
- systemic verification (technical, ethical, legal requirements)
- impact evaluation (outcomes for users and business cases)

**Objective:** Embed **E2VT** as a continuous, risk-tiered discipline across:
- Design
- Development
- Deployment
- Maintenance

## 2.2 Pillars (Principles)

### Risk proportionate trustworthy and safe AI
Controls scale with potential harm, impact, and autonomy of the use case.

### Evidence-first evaluation by design
Evaluation plans at the outset; claims require traceable empirical evidence.

### Model-Agnostic
Applicable across classical ML and generative models (adapt methods by failure mode).

### Secure By Design
Data minimisation, provenance, least privilege. Incorporate OWASP Top 10 mitigations for LLMs and agentic AI.

### Human-centred impact-focused deployment
Rigorous measurement of value, accessibility, human factors, and explainability.

### Reproducible and auditable
Deterministic pipelines, dataset snapshots, immutable logs.

### Continuous improvement
E2VT is ongoing: pre-prod, canary, post-deployment; not a one-off accreditation.

These pillars enable:
- **Reproducibility**
- **Traceability**
- **Integrity**
- **Accountability**
- **Governance readiness**

---

# Chapter 3: Operationalising AI Assurance

## 3.1 Governance and accountability

Departments should establish:
- clear accountability (SROs)
- ethics/AI governance boards
- alignment with principles: safety, transparency, fairness, responsibility, contestability

Independent audits verify adherence.

### RACI for Operationalising AI Assurance

| Area | Accountable | Responsible | Consulted | Informed |
|------|------------|-------------|-----------|----------|
| Risk Tiering | Service / Product Owner | Principal Technologist, Safety Lead | Legal, DPO | Team |
| Model Evaluation Plan | Principal Technologist | ML Eng, Data Scientist, QA Engineer | Domain SMEs, UserXP Researchers | Governance Board / Officers |
| Impact Evaluation Plan | Head of Evaluations | Social researchers / Data scientists | Domain SMEs, UserXP Researchers | All |
| Data Provenance | AI/Data Lead | ML Eng, Data Scientist | Domain SMEs, UserXP Researchers | Governance Board / Officers |
| Red Team | Safety Lead | Security, Red-Teamers | Product Owner, Legal | All |
| Go-Live | SRO | Service / Product Owner | Assurance Board | Stakeholders |
| Monitoring & Incidents | Service / Product Owner | SRE/Oncall/monitoring experts | Safety Lead, Comms | All |

## 3.2 Evaluation controls and documentation

Controls across lifecycle include:
- model cards / datasheets
- CI tests for bias, performance, security
- reproducible pipelines
- E2VT assessment templates (ATRS-aligned)

Practitioners should conduct:
- threat modelling
- DPIAs
- fairness impact assessments
- human oversight design

Impact assessments must be underpinned by robust impact evaluations (Magenta Book).

## 3.3 Managing AI risk

The AI Risk Management Toolkit is a starting point for building organisational risk management.

### 3.3.1 Risk Tiering & Control Mapping

This tiering applies across appetites except **Risk Averse** cases.

| Tier | Example impact | Typical controls |
|------|----------------|------------------|
| R1 Minimal | Non-personal content search, low consequence | Basic offline eval; logs; lightweight privacy/security checks; A/B only after sign-off |
| R2 Cautious | Staff productivity or non-critical user advice | Expanded offline eval; calibration; bias screen; red-team lite; monitoring SLOs |
| R3 Open | Eligibility, benefits triage, sensitive advice | Formal validation protocols (E2VT); domain SME panels; strong privacy/PII controls; comprehensive red-teaming; HITL; change freeze windows |
| R4 Eager | Safety/security, legal exposure, vulnerable cohorts | Independent assurance; external audit; rigorous canary w/ kill-switch; full traceability; quarterly re-certification |

## 3.4 Secure configuration and shared capabilities

Centralised services enable:
- secure hosting
- secure API gateways
- shared evaluation platforms
- consistent controls

## 3.5 Data assets and quality

Maintain:
- high-quality, representative datasets
- bias audits
- data inventories
- governance standards

## 3.6 Information and data security

Ensure:
- confidentiality, integrity, availability
- UK GDPR compliance
- secure architectures
- differential privacy / federated learning where appropriate

## 3.7 Model assurance and supply-chain risk

Assess:
- third-party vendors
- security and robustness requirements
- conformance to standards

## 3.8 Threat information and security

AI systems are vulnerable to adversarial attacks. Follow NCSC guidance. Conduct:
- red-teaming
- secure coding practices
- privacy and security controls

## 3.9 Monitoring within organisations

Monitor:
- drift
- bias
- safety violations
- automated alerts + human review
- user feedback

## 3.10 Response preparation

Prepare incident response plans including:
- roles
- escalation paths
- comms strategies
- logging requirements

## 3.11 Incident response

Contain harm, investigate root cause, involve authorities, and ensure transparency.

## 3.12 Incident recovery and lessons learned

Conduct PIRs, update controls, and share lessons.

## 3.13 Detection at scale

Cross-department dashboards and reporting mechanisms enable systemic oversight.

## 3.14 Key Performance Indicators (KPIs)

Suggested KPIs:
- Coverage of AI assurance
- Evaluation integration (E2VT adoption)
- Incident response readiness
- Public trust indicators
- Efficiency gains
- Error reduction
- Retention / cognitive impact
- User satisfaction

## 3.15 AI assurance and partnerships

Collaborate with:
- AI Safety Institute
- academia
- industry
- international partners

Support shared assurance platforms and benchmark contributions.

---

# Chapter 4: Evaluation for Validation and Verification with Testing (E2VT)

To achieve outcomes such as:
- faster approvals
- fewer post-deployment surprises
- safer user experiences
- reusable test assets

…teams must show full traceability from requirements to evidence.

E2VT is a risk-tiered lifecycle-integrated model comprising five components:
1. standardised evidence catalogue  
2. use-case-specific test harnesses  
3. offline + online evaluation blend  
4. continuous monitoring + incident response  
5. governance gates blocking deployment without evidence  

## 4.1 Evidence Catalogue (what to collect)

Agree a standard evidence catalogue aligned with risk tier.

### Data artefacts
- Data Card
- lineage/provenance graph
- lawful basis / consent
- quality profiles (missingness/leakage/bias)
- drift baselines

### Model artefacts
- Model Card
- training config + seeds
- versioned weights
- hyperparameters
- calibration curves
- uncertainty estimates
- adversarial robustness report

### System artefacts
- end-to-end test cases
- FMEA
- UX research notes
- accessibility checks
- escalation/override design
- safety filter tests

### Security & privacy
- threat model (STRIDE/LINDDUN)
- pen-test results
- red-team logs
- prompt injection tests
- PII leakage tests
- key management evidence

### Monitoring operations
- dashboards (quality/safety/latency)
- incident runbook
- rollbacks
- change control records
- post-incident reviews

### Assurance case
- auditable definition-of-done linking **requirements ➜ evidence ➜ conclusion**

#### Suggested procurement clauses
Suppliers must provide:
- Data/Model Cards
- eval plans
- reproducible test artefacts
- privacy/security test evidence
- monitoring SLOs

And:
- right to audit
- access to red-team results
- patching/retraining commitments
- portability and export of logs/artefacts

## 4.2 Test Harnesses & Datasets

- **Golden sets** (curated and versioned, with edge cases)
- **Red-team corpora** (updated quarterly)
- **Protected-attribute slices**
- **Synthetic data** (where lawful)
- **Human rating protocols**
  - double-blind
  - inter-rater agreement (Cohen’s κ) ≥ 0.7 for critical tasks

> Refer to the Cross-Gov testing framework for prescriptive insights.

## 4.3 Operating Model (Lifecycle with Governance Gates)

E2VT is a continuous loop spanning:
- pre-production
- canary (Controlled Live Testing / Early Rollout)
- live operation

It is underpinned by:
- deterministic execution
- versioned datasets
- immutable evidence

Depending on change size:
- major strategic changes require manual governance gates
- minor operational changes can use automated gates embedded in CI/CD

---

## Lifecycle Overview

### Design (Scope → Select)

**Key activities checklist**
- Define use case
- Risk tier (R1–R4)
- Identify legal/ethical/operational context
- Baseline datasets
- DPIA (initial)
- Success metrics / NFRs
- Evaluation plan

**Evidence outputs**
- Use-case risk register
- Evidence catalogue template
- Data lineage documentation
- Data quality report

✅ **Governance Gate 1:** approve to proceed only after evidence catalogue + risk register complete

---

### Development (Align → Evaluate)

**Key activities**
- Build models and pipelines
- Publish info about AI systems
- Configure task-level test harnesses
- Unit/integration/regression tests
- Offline evaluation (performance/bias/robustness)
- HITL checkpoints
- Counterfactual fairness testing
- Calibration and representativeness checks

**Evidence outputs**
- Dataset + Model Cards in registry
- Evaluation plan
- Offline metrics
- Bias/fairness screens
- Explainability/uncertainty plan
- Calibration test results
- Initial threat model

✅ **Governance Gate 2:** bias/robustness thresholds met before pre-prod release  
✅ Pre-deployment assurance gate verified by technical governance board

---

### Deployment (Integrate → Assure)

**Private Beta (limited users, HITL)**

**Key activities**
- Blend offline and online evaluation
- Pen testing (privacy/security)
- Red-team round 1
- Operational SLOs and drift monitors
- PII stress tests
- Safety filters and logging
- UX and oversight testing
- Decision boundary evaluation
- Support runbook
- Accessibility audit

**Evidence outputs**
- Deployment evaluation summary
- Pen-test report
- Red-team report
- Incident response plan

✅ **Governance Gate 3:** deployment blocked without evaluation + SLO sign-off  
✅ Canary validation review: ethics, operations, governance

---

### Monitoring & Maintenance (Operate)

**Public Beta / Live**

**Key activities**
- Continuous drift/bias monitoring
- Evaluation schedule (toxicity, hallucination, bias drift)
- Incident response and retraining triggers
- Feedback and impact loops
- Online KPIs (trust, errors, safety events)

**Evidence outputs**
- Monitoring dashboards
- Incident logs
- Version updates and audit trail
- Signed assurance case (GSN optional)

✅ **Governance Gate 4:** continuous readiness review

---

### Improvement & Reuse (Feedback Loop)
- update evidence catalogue
- periodic bias re-tests
- change control & re-certification triggers
- reuse harnesses across projects

### Retire / Replace
- end-of-life report
- model archive
- disposal audit
- teardown report
- future change plan

---

# Glossary

- **AI-enabled system:** Any service ingesting data and using ML/statistical models or generative AI to influence outputs/decisions.
- **AI assurance:** Measuring, evaluating and communicating the trustworthiness of AI systems.
- **ATRS:** Standard template for publishing info about algorithmic tools: purpose, deployment context, risks and mitigations.
- **Impact evaluation:** Assessment of outcomes of an intervention to establish whether and why impacts were achieved.
- **Systemic testing & verification:** Technical and ethical checks across lifecycle for robustness, fairness, security and transparency.
- **Evaluation:** Measuring performance against risk-aware metrics (offline & online).
- **Validation:** Checking system meets user, policy and regulatory needs.
- **Verification:** Checking the system was built right against specs/requirements.
- **Testing:** Executing controlled checks for correctness, safety, security and operability.
- **Assurance artefact:** Auditable evidence linked to a requirement.
- **Inter-rater agreement:** extent independent raters agree beyond chance.

---

# Appendix A: Alignment with already published resources

## Alignment with the Magenta Book

The Magenta Book provides overarching guidance for government evaluation. The **E2VT Strategy** extends these principles into a detailed technical framework for AI assurance.

- Magenta Book: evaluates whether interventions work and provide value.
- E2VT: evaluates trustworthiness and safety of AI systems through lifecycle technical assurance.

## Alignment with the AI Playbook and Service Manual

The AI Service Manual and AI Playbook set the principles for safe AI use. E2VT provides the practical operationalisation, including:
- risk tiering and control mapping
- evaluation and assurance throughout lifecycle
- transparency and explainability (ATRS)
- meaningful human control
- secure and high-quality data handling
- continuous monitoring and improvement

---
