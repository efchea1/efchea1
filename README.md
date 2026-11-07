# Emmanuel Fle Chea

**Clinical Data Scientist · R/SAS/Python Statistical Programming (CDISC/ADaM) · Founder & CEO, Lexify Health**

**R/Pharma 2026 Speaker · RConsortium pharma-skills Contributor · Kaggle AGI Benchmark · HeatMap 2026 1st Place · TAC Member, MN Community Health Worker Alliance**

> *"Equity lives in the data. I build systems that make it measurable."*

📍 California, USA  |  🌍 Liberian-rooted  |  🏥 Building clinical AI and statistical programming tools that actually work in production

---

## 👋 About Me

I'm a clinical data scientist and AI/software engineer working at the intersection of clinical trial data, healthcare AI, and technology governance. I write production R, SAS, and Python for clinical data, build CDISC-aligned derivations with the pharmaverse ecosystem, and test whether AI coding agents can be trusted with regulated clinical work. My work is rooted in a conviction that equity has to be measurable, not aspirational.

Before founding Lexify Health, I built automated QC pipelines across millions of EHR records, wrote Medicaid claims logic for large patient populations, and developed LLM evaluation frameworks for healthcare AI.

**Clinical programming & open source:** merged contributor to RConsortium pharma-skills with two merged pull requests, **PR #152** (fixed `derive_vars_merged_lookup` enforcement, confirmed by four independent re-runs, score improving from 94.4% to 98.9%) and **PR #187** (implemented a previously dead-stubbed PPROTFL derivation in admiral-adsl, including SAS XPT 8-character variable-name compliance; both the AI agent and the baseline model had failed identically on this assertion before the fix). Authored 20 benchmark cases (Issues #36-40, #165-175) spanning admiral PK/RECIST/ADTTE/SAFFL derivations, Bayesian adaptive dose-finding, group-sequential non-inferiority and platform trial designs, and r2rtf survival tables, driving measurable skill improvements confirmed by independent maintainer re-runs.

**Speaking:** presented *"Benchmarking AI for Clinical Trial Design: Silent Failures in the RConsortium pharma-skills Skill"* at **R/Pharma 2026**.

**Also:** built and deployed a full **RAG automation agent** for enterprise IT operations (publicly live at [rag-automation-agent.onrender.com](https://rag-automation-agent.onrender.com/), 50 passing tests, documented security/governance layer); independent AI safety researcher (Calibration Blindspot Benchmark, Kaggle AGI Hackathon 2026); and 1st place winner at HeatMap Hackathon 2026, sponsored by the American Burn Association.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Emmanuel_Fle_Chea-0077B5?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/emmanuel-fle-chea)
[![Google Scholar](https://img.shields.io/badge/Google_Scholar-Profile-4285F4?logo=google-scholar&logoColor=white)](https://scholar.google.com/citations?user=UeIJ3uQAAAAJ)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0005--1563--2558-A6CE39?logo=orcid&logoColor=white)](https://orcid.org/0009-0005-1563-2558)
[![Email](https://img.shields.io/badge/Email-emmanuelf.chea@gmail.com-D14836?logo=gmail&logoColor=white)](mailto:emmanuelf.chea@gmail.com)

---

## 🎓 Education & Certifications

- **MPH, Public Health Data Science** - University of Minnesota School of Public Health (2025)
- **BA, Physics & Mathematics** - Wells College
- **Certifications:** SAS Base Certified · Tableau Desktop Specialist · Microsoft Power BI Data Analyst (PL-300)

---

## 🏢 Lexify Health - Clinical Policy Intelligence

**I founded [Lexify Health](https://lexify.health) to solve a problem I lived for 7 years.**

Clinical data scientists spend hours, sometimes days, manually translating a medical policy document into production SQL. Lexify does it within minutes.

> Selected to pitch Lexify Health at **Walleye Tank 2026** · MN Cup 2026 Applicant (Life Science/Health IT) · VIP Invitation - Convene Conference

[![Lexify](https://img.shields.io/badge/Lexify-lexify.health-0D9488?style=for-the-badge)](https://lexify.health)

**Supports:** OMOP CDM · Epic Clarity · PostgreSQL · Snowflake · Databricks SQL · Microsoft SQL Server · Google BigQuery · Oracle Health (Cerner)

**Outputs:** Production SQL · Logic Spec · Test Cases · QC Report · Python Wrapper · Policy Metadata · Narrative

---

## 📌 Featured Projects

### 🧪 RConsortium pharma-skills - AI Benchmark Contributions
Designed and contributed 20 silent-failure benchmark cases evaluating AI coding agents against the {admiral} ADaM ecosystem, group-sequential trial design, Bayesian adaptive simulation, and r2rtf reporting, then diagnosed root causes and shipped two merged pull requests fixing the gaps the benchmarks exposed. Presented at R/Pharma 2026.

**Tech:** R · {admiral}/{admiralonco} · gsDesign/gsDesign2 · r2rtf · CDISC ADaM/SDTM · SAS XPT · Claude Code

📄 [PR #152](https://github.com/RConsortium/pharma-skills/pull/152) · [PR #187](https://github.com/RConsortium/pharma-skills/pull/187)

[![Repo](https://img.shields.io/badge/GitHub-Repository-181717?logo=github)](https://github.com/efchea1/pharma-skills-benchmarks)

---

### 🔬 ATN vs Machine-Learned Plasma Biomarker Phenotypes
Comparative analysis of theory-driven ATN classification versus data-driven biomarker phenotypes using k-means, Gaussian mixture models, PCA, and variational autoencoders (VAE) in 4,465 HRS participants. Accepted as a poster at the 5th African Symposium on Big Data, Analytics & Machine Intelligence.

**Tech:** R · Unsupervised ML · GMM · PCA · VAE

📄 [Preprint - DOI: 10.64898/2026.01.02.26343331](https://doi.org/10.64898/2026.01.02.26343331)

[![Repo](https://img.shields.io/badge/GitHub-Repository-181717?logo=github)](https://github.com/efchea1/ATN-vs-Machine-Learned-Plasma-Biomarker-Phenotypes)

---

### 🧠 Equity & Transportability of Plasma ATN Phenotypes
Fairness, calibration, and population-representative evaluation of Alzheimer's plasma biomarkers across U.S. aging cohorts. Includes subgroup performance, calibration drift, and transportability diagnostics.

**Tech:** R · Fairness metrics · Calibration · Transportability

📄 [Preprint - DOI: 10.64898/2026.01.31.26344775](https://doi.org/10.64898/2026.01.31.26344775)

[![Repo](https://img.shields.io/badge/GitHub-Repository-181717?logo=github)](https://github.com/efchea1/Equity-Transportability-Plasma-ATN-Phenotypes)

---

### 🧬 Scalable Plasma Biomarker Phenotyping for Alzheimer's Disease
Large-scale Alzheimer's heterogeneity analysis using plasma biomarkers, ATN endotyping, clustering, and variational autoencoders.

**Tech:** R · Keras/TensorFlow · pROC · cluster · DESeq2

[![Repo](https://img.shields.io/badge/GitHub-Repository-181717?logo=github)](https://github.com/efchea1/Scalable-Plasma-Biomarker-Phenotyping-for-Alzheimer-s-Disease)

---

### 🤖 RAG Automation Agent - Enterprise IT Operations
A publicly deployed RAG agent that ingests PDF/DOCX/HTML documents into a vector database plus hybrid keyword search, then runs a full agentic pipeline: query rewriting, grounded/cited retrieval, triage classification, guided-remediation runbook matching with human-approval gates, and downstream automation into ServiceNow, Microsoft Graph, and Power Automate. Exposed as a Python library, CLI, and authenticated REST API. 50 passing tests, dry-run-by-default on every mutating integration, and a governance layer (PII redaction, structured audit log, API key auth + rate limiting).

**Tech:** Python · Streamlit · FastAPI · ChromaDB · BM25/TF-IDF Hybrid Retrieval · Anthropic/OpenAI/Azure OpenAI · Microsoft Graph · ServiceNow API · Power Automate · AWS · Azure · pytest

🔗 [Live Demo](https://rag-automation-agent.onrender.com/)

[![Repo](https://img.shields.io/badge/GitHub-Repository-181717?logo=github)](https://github.com/efchea1/rag-automation-agent)

---

## 🏆 Recognition & Open Source Contributions

| Work | Description | Link |
|------|-------------|------|
| **R/Pharma 2026 - Speaker** | *Benchmarking AI for Clinical Trial Design: Silent Failures in the RConsortium pharma-skills Skill* | [R/Pharma](https://rinpharma.com) |
| **RConsortium pharma-skills** | Merged contributor with **2 merged PRs** (#152, #187) and **20 benchmark cases** authored across group-sequential-design, admiral-adsl/admiral-bds, clinical-trial-simulation, and r2rtf skills (Issues #36-40, #165-175). Acknowledged by project lead Yilong Zhang (Meta) and reviewed by core contributors jeffreyad and elong0527. | [GitHub](https://github.com/efchea1/pharma-skills-benchmarks) · [PR #152](https://github.com/RConsortium/pharma-skills/pull/152) · [PR #187](https://github.com/RConsortium/pharma-skills/pull/187) |
| **Calibration Blindspot Benchmark** | AI safety research on metacognitive calibration across frontier LLMs. Core finding: models expressed 100% confidence while failing to predict their own errors, yet detected externally planted errors near-perfectly (Anti-Confab Score 0.972-1.000). Kaggle AGI Hackathon 2026; presented at MinneAnalytics DataTech 2026. | [GitHub](https://github.com/efchea1/calibration-blindspot-benchmark) · [Kaggle](https://www.kaggle.com/competitions/kaggle-measuring-agi/writeups/calibration-blindspot-benchmark-cbb) |
| **HeatMap Hackathon 2026 - 1st Place** | Geospatial analysis of burn care access disparities across all 50 U.S. states; county-level gap identification. 19 teams, 90+ participants. Sponsored by American Burn Association, BData, HealthcareMN | [GitHub](https://github.com/efchea1/HeatMap_Burn_2026_Hackathon_Burn_Care_Access_Analysis) |

---

## Additional Projects

| Project | Description | Tech |
|---------|-------------|------|
| [RBC Storage Duration Analysis](https://github.com/efchea1/Evaluation-of-RBC-Storage-Duration-on-Prostate-Cancer-Recurrence-Post-Prostatectomy) | SAS-based retrospective clinical outcomes analysis of allogeneic RBC storage duration on biochemical recurrence timing | SAS |
| [Prostate Cancer Recurrence](https://github.com/efchea1/Biomarkers-and-Clinical-Covariates-for-Predicting-Prostate-Cancer-Recurrence) | Clinical outcomes study integrating 40 biomarkers with clinical covariates for 5-year recurrence prediction post-prostatectomy | R |
| [Cardiovascular Risk Prediction](https://github.com/efchea1/Predictive-Analytics-for-Cardiovascular-Disease-Prevention) | Chronic disease risk prediction using BRFSS 2021; Logistic Regression, Decision Trees, KNN, and Random Forest compared across 400k+ records | R |
| [CDC PLACES Health Mapping](https://github.com/efchea1/Analytic_Project_Regional-Health-Mapping-Harnessing-CDC-PLACES-Data-for-Minnesota-Community-Health-) | County-level chronic disease surveillance and health equity analytics for Minnesota; interactive R Shiny dashboard | R · R Shiny |
| [Stroke Prediction Models](https://github.com/efchea1/Build-and-deploy-stroke-prediction-models-using-R) | Predictive modeling and deployment for stroke risk assessment | R · R Shiny |
| [Liver Disease Prediction](https://github.com/efchea1/Liver-Disease-Prediction-Project) | ML classification using clinical and biochemical features | Python · scikit-learn |

---

## 🛠️ Technical Skills

### Clinical Statistical Programming
![CDISC](https://img.shields.io/badge/CDISC-SDTM%20%7C%20ADaM-005A9C)
![admiral](https://img.shields.io/badge/pharmaverse-admiral-276DC3)
![gsDesign](https://img.shields.io/badge/gsDesign-Group_Sequential-276DC3)
![r2rtf](https://img.shields.io/badge/r2rtf-TLFs-276DC3)
![SAS](https://img.shields.io/badge/SAS-Base_Certified-1F4788)
![Survival Analysis](https://img.shields.io/badge/Survival_Analysis-E97451)
![Mixed Models](https://img.shields.io/badge/Mixed_Models-52B788)

### Statistical Computing & Data
![R](https://img.shields.io/badge/R-276DC3?logo=r&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4169E1?logo=postgresql&logoColor=white)
![OMOP CDM](https://img.shields.io/badge/OMOP_CDM-0D9488)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?logo=snowflake&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?logo=databricks&logoColor=white)

### Agentic AI & Machine Learning
![RAG](https://img.shields.io/badge/RAG-6E56CF)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F61)
![Anthropic API](https://img.shields.io/badge/Anthropic_API-D97757)
![OpenAI API](https://img.shields.io/badge/OpenAI_API-412991?logo=openai&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7)
![Microsoft Graph](https://img.shields.io/badge/Microsoft_Graph-0078D4?logo=microsoft&logoColor=white)
![Power Automate](https://img.shields.io/badge/Power_Automate-0066FF?logo=microsoftpowerautomate&logoColor=white)

### Infrastructure & MLOps
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?logo=microsoftazure&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD-GitHub_Actions-2088FF?logo=githubactions&logoColor=white)
![HIPAA](https://img.shields.io/badge/HIPAA-Aware_Design-DC143C)

### Visualization
![Tableau](https://img.shields.io/badge/Tableau-E97627?logo=tableau&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?logo=powerbi&logoColor=black)
![R Shiny](https://img.shields.io/badge/R_Shiny-276DC3?logo=r&logoColor=white)

---

## 🌍 Mission

Rooted in Liberia, building in California. I bridge public health, clinical trial data science, AI safety, and technology governance to build systems that are fast, auditable, and equitable: from CDISC-aligned clinical programming, to Lexify's clinical policy engine, to benchmarks that test whether AI systems can be trusted at all.

**Building systems where equity is not aspirational, it's measurable.**

---

## 📄 License

Licensing varies by project:

- **Lexify Health** is proprietary software. All rights reserved.
- **RAG Automation Agent** is public for demonstration and evaluation purposes only. All rights reserved, see the repo's [LICENSE](https://github.com/efchea1/rag-automation-agent/blob/main/LICENSE).
- Most research repositories are licensed under **MIT**, see each repo for its specific license.
- A subset of research work is licensed under [Creative Commons Attribution-NonCommercial 4.0](https://creativecommons.org/licenses/by-nc/4.0/).

[![CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)
[![MIT License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

<div align="center">

**[lexify.health](https://lexify.health) · [LinkedIn](https://www.linkedin.com/in/emmanuel-fle-chea) · [Google Scholar](https://scholar.google.com/citations?user=UeIJ3uQAAAAJ)**

</div>
