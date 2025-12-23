# Emmanuel Fle Chea 🧠📊
<svg width="720" height="120" viewBox="0 0 720 120" xmlns="http://www.w3.org/2000/svg">

  <!-- Background -->
  <rect x="0" y="0" width="720" height="120" fill="#0d1117" />

  <!-- Grid settings -->
  <!-- 20 columns (weeks) x 7 rows (days) -->
  <!-- Each cell: 12x12, with 3px gap -->
  <!-- Colors inspired by GitHub dark contribution graph -->

  <!-- Contribution cells -->
  <g id="grid" transform="translate(20, 10)">
    <!-- Define colors for activity levels -->
    <!-- You can randomize / tweak these manually -->
    <!-- Row = day of week, Col = "week" -->

    <!-- Generate some sample data by hand -->
    <!-- y = row * 15, x = col * 15 -->

    <!-- Row 0 -->
    <rect x="0" y="0" width="12" height="12" rx="2" fill="#161b22" />
    <rect x="15" y="0" width="12" height="12" rx="2" fill="#0e4429" />
    <rect x="30" y="0" width="12" height="12" rx="2" fill="#26a641" />
    <rect x="45" y="0" width="12" height="12" rx="2" fill="#39d353" />
    <rect x="60" y="0" width="12" height="12" rx="2" fill="#161b22" />
    <rect x="75" y="0" width="12" height="12" rx="2" fill="#0e4429" />
    <rect x="90" y="0" width="12" height="12" rx="2" fill="#0e4429" />
    <rect x="105" y="0" width="12" height="12" rx="2" fill="#26a641" />
    <rect x="120" y="0" width="12" height="12" rx="2" fill="#39d353" />
    <rect x="135" y="0" width="12" height="12" rx="2" fill="#161b22" />
    <rect x="150" y="0" width="12" height="12" rx="2" fill="#0e4429" />
    <rect x="165" y="0" width="12" height="12" rx="2" fill="#26a641" />
    <rect x="180" y="0" width="12" height="12" rx="2" fill="#161b22" />
    <rect x="195" y="0" width="12" height="12" rx="2" fill="#161b22" />
    <rect x="210" y="0" width="12" height="12" rx="2" fill="#0e4429" />
    <rect x="225" y="0" width="12" height="12" rx="2" fill="#39d353" />
    <rect x="240" y="0" width="12" height="12" rx="2" fill="#0e4429" />
    <rect x="255" y="0" width="12" height="12" rx="2" fill="#26a641" />
    <rect x="270" y="0" width="12" height="12" rx="2" fill="#161b22" />
    <rect x="285" y="0" width="12" height="12" rx="2" fill="#0e4429" />

    <!-- Row 1 -->
    <!-- You can copy/paste and change y and fill for variety -->
    <rect x="0" y="15" width="12" height="12" rx="2" fill="#161b22" />
    <rect x="15" y="15" width="12" height="12" rx="2" fill="#161b22" />
    <rect x="30" y="15" width="12" height="12" rx="2" fill="#0e4429" />
    <rect x="45" y="15" width="12" height="12" rx="2" fill="#26a641" />
    <rect x="60" y="15" width="12" height="12" rx="2" fill="#39d353" />
    <rect x="75" y="15" width="12" height="12" rx="2" fill="#26a641" />
    <rect x="90" y="15" width="12" height="12" rx="2" fill="#0e4429" />
    <rect x="105" y="15" width="12" height="12" rx="2" fill="#161b22" />
    <rect x="120" y="15" width="12" height="12" rx="2" fill="#0e4429" />
    <rect x="135" y="15" width="12" height="12" rx="2" fill="#26a641" />
    <rect x="150" y="15" width="12" height="12" rx="2" fill="#39d353" />
    <rect x="165" y="15" width="12" height="12" rx="2" fill="#26a641" />
    <rect x="180" y="15" width="12" height="12" rx="2" fill="#0e4429" />
    <rect x="195" y="15" width="12" height="12" rx="2" fill="#161b22" />
    <rect x="210" y="15" width="12" height="12" rx="2" fill="#161b22" />
    <rect x="225" y="15" width="12" height="12" rx="2" fill="#0e4429" />
    <rect x="240" y="15" width="12" height="12" rx="2" fill="#26a641" />
    <rect x="255" y="15" width="12" height="12" rx="2" fill="#39d353" />
    <rect x="270" y="15" width="12" height="12" rx="2" fill="#26a641" />
    <rect x="285" y="15" width="12" height="12" rx="2" fill="#0e4429" />

    <!-- Add more rows (y=30,45,60,75,90) the same way if you want a full 7-day grid -->

  </g>

  <!-- Moving highlight overlay -->
  <!-- A semi-transparent vertical band that sweeps across the grid -->
  <rect id="scanner" x="-60" y="0" width="80" height="120" fill="url(#scannerGradient)" opacity="0.75">
    <animate
      attributeName="x"
      from="-80"
      to="720"
      dur="5s"
      repeatCount="indefinite"
    />
  </rect>

  <!-- Gradient for the moving scanner -->
  <defs>
    <linearGradient id="scannerGradient" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#7c3aed" stop-opacity="0.0" />
      <stop offset="40%" stop-color="#7c3aed" stop-opacity="0.4" />
      <stop offset="60%" stop-color="#22c55e" stop-opacity="0.8" />
      <stop offset="100%" stop-color="#22c55e" stop-opacity="0.0" />
    </linearGradient>
  </defs>

</svg>

**"Equity lives in the data"**

Public health data scientist and biomedical researcher decoding clinical and population-level data for translational impact.

📍 Based in the U.S. | 🌍 Rooted in Liberia  
🎯 Building AI systems for healthcare equity, national security, and global public good

---

# About Me

I’m a public health data scientist and biomedical researcher focused on transforming complex clinical and population‑level data into meaningful, actionable insights. My work spans health services research, informatics, and large‑scale analytics, with expertise in:

* 📊**EHR & claims analytics** at scale
* 🤖**NLP‑derived clinical data and predictive modeling**
* 🧠**Epidemiological modeling for neurodegenerative & mental health outcomes**
* 🛠️**Reproducible** R, Python, SAS & SQL pipelines for multi‑million‑record datasets
* 🔐**Data governance**, HIPAA/GDPR compliance & multi‑site data integration

Currently focused on building transparent, equity‑driven analytic frameworks that advance translational research, strengthen health system decision‑making, and support global public health data infrastructure.

---

## 📌 Featured Projects

| Project | Description | Tech |
|--------|-------------|------|
| [Scalable Plasma Biomarker Phenotyping for Alzheimer's Disease](https://github.com/efchea1/Scalable-Plasma-Biomarker-Phenotyping-for-Alzheimer-s-Disease) | Alzheimer’s disease heterogeneity using plasma biomarkers, ATN endotyping, clustering, and variational autoencoding (VAE) | R; **Deep Learning:** Keras (R interface), Tensorflow (R interface); **Statistical & Machine Learning Libraries:** nnet, pROC, cluster, factoextra, DESeq2 |
| [AI-Mastery-Portfolio](https://github.com/efchea1/AI-Mastery-Portfolio) | Public learning plan & weekly builds | Python, PyTorch, LangChain, NLP, JAX, XLA, CUDA, Explainable AI, SQL, FastAPI, Docker, Supabase |
| [CDC PLACES Mapping](https://github.com/efchea1/Analytic_Project_Regional-Health-Mapping-Harnessing-CDC-PLACES-Data-for-Minnesota-Community-Health-) | Regional health analytics | R |
| [Stroke Prediction Models](https://github.com/efchea1/Build-and-deploy-stroke-prediction-models-using-R) | ML models for stroke risk | R |
| [Prostate Cancer Recurrence](https://github.com/efchea1/Evaluation-of-RBC-Storage-Duration-on-Prostate-Cancer-Recurrence-Post-Prostatectomy) | SAS-based clinical study | SAS |
| [Cardiovascular Risk Prediction](https://github.com/efchea1/Predictive-Analytics-for-Cardiovascular-Disease-Prevention) | ML on BRFSS data | R |

---

## 🛠️ Skills / Stack Highlights

### 🧠 Core AI  
![Python](https://img.shields.io/badge/Python-3.13-blue?logo=python) ![PyTorch](https://img.shields.io/badge/PyTorch-Framework-orange?logo=pytorch) ![LangChain](https://img.shields.io/badge/LangChain-LLM%20Framework-green) ![Transformers](https://img.shields.io/badge/NLP-Transformers-purple) ![JAX](https://img.shields.io/badge/JAX-ML%20Library-orange) ![XLA](https://img.shields.io/badge/XLA-Accelerated%20Linear%20Algebra-yellow) ![CUDA](https://img.shields.io/badge/CUDA-GPU%20Programming-green?logo=nvidia) ![XGBoost](https://img.shields.io/badge/XGBoost-Gradient%20Boosting-blue) ![GLMs](https://img.shields.io/badge/GLMs-Generalized%20Linear%20Models-lightblue) ![Explainable AI](https://img.shields.io/badge/Explainable%20AI-Model%20Transparency-yellowgreen)

### 🛠️ Backend & Infra  
![SQL](https://img.shields.io/badge/SQL-Postgres-blue?logo=postgresql) ![FastAPI](https://img.shields.io/badge/Backend%20AI%20APIs-FastAPI-blue) ![Docker](https://img.shields.io/badge/Docker-Ready-blue?logo=docker) ![Supabase](https://img.shields.io/badge/Supabase-Backend-lightgreen?logo=supabase)

### 📊 MLOps & Compliance  
![Secure Pipeline](https://img.shields.io/badge/Secure%20Pipeline-HIPAA%2FGDPR%20Ready-red) ![API Tests](https://img.shields.io/badge/API%20Tests-pytest-yellow) ![CI/CD](https://img.shields.io/badge/CI%2FCD-GitHub%20Actions-blue?logo=githubactions) ![Portfolio](https://img.shields.io/badge/Portfolio-Building-success) ![Last Updated](https://img.shields.io/github/last-commit/efchea1/AI-Mastery-Portfolio)

### 📐 Statistical Computing  
![R](https://img.shields.io/badge/R-Statistical%20Computing-blue?logo=r) ![SAS](https://img.shields.io/badge/SAS-Clinical%20Analytics-lightgray) ![GLMs](https://img.shields.io/badge/GLMs-Generalized%20Linear%20Models-lightblue) ![Survival Analysis](https://img.shields.io/badge/Survival%20Analysis-Cox%20Models%2C%20Kaplan--Meier-orange) ![Mixed Models](https://img.shields.io/badge/Mixed%20Models-LME%2C%20GLMMs-yellowgreen) ![Reproducible Research](https://img.shields.io/badge/Reproducible%20Research-RMarkdown%2C%20Quarto-blueviolet) 

### 📚 Public Health & Policy  
![Public Health Analytics](https://img.shields.io/badge/Public%20Health%20Analytics-Equity%20Focused-green) ![Policy Writing](https://img.shields.io/badge/Policy%20Writing-Advocacy%20Driven-orange)

### 📈 Visualization & Productivity  
![Tableau](https://img.shields.io/badge/Tableau-Data%20Viz-blue?logo=tableau) ![Power BI](https://img.shields.io/badge/Power%20BI-Business%20Intelligence-yellow?logo=powerbi) ![Excel](https://img.shields.io/badge/Excel-Data%20Analysis-green?logo=microsoft-excel) ![Google Sheets](https://img.shields.io/badge/Google%20Sheets-Collaborative%20Spreadsheets-lightgreen?logo=google-sheets) ![PowerPoint](https://img.shields.io/badge/PowerPoint-Strategic%20Comms-orange?logo=microsoft-powerpoint)

---

## 🤝 Contributor Guide & 📫 Connect

All projects are shared under a non-commercial license. Contributions are welcome under the same terms. For commercial inquiries or licensing exceptions, please contact:
- 🌐 [LinkedIn](https://www.linkedin.com/in/emmanuel-fle-chea)  
- 📬 Email: emmanuelf.chea@gmail.com

All contributions must comply with the CC BY-NC 4.0 license. Commercial use requires written permission.

----

## 📄 License

All projects on this GitHub are licensed under the [Creative Commons Attribution-NonCommercial 4.0 International License](https://creativecommons.org/licenses/by-nc/4.0/). For licensing exceptions or commercial inquiries, please contact Emmanuel at emmanuelf.chea@gmail.com.
