<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Emmanuel Fle Chea - Profile</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Roboto', 'Helvetica', 'Arial', sans-serif;
            background: linear-gradient(135deg, #6B7FED 0%, #8B5FC7 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }

        .container {
            background: rgba(255, 255, 255, 0.95);
            border-radius: 24px;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
            max-width: 900px;
            width: 100%;
            overflow: hidden;
        }

        .header {
            background: linear-gradient(135deg, #7B8EED 0%, #9B6FD7 100%);
            color: white;
            padding: 60px 50px;
            position: relative;
            border-radius: 20px;
            margin: 15px;
        }

        .header::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: radial-gradient(circle at 20% 50%, rgba(255,255,255,0.1) 0%, transparent 50%),
                        radial-gradient(circle at 80% 80%, rgba(255,255,255,0.1) 0%, transparent 50%);
            border-radius: 20px;
        }

        .header-content {
            position: relative;
            z-index: 1;
        }

        .name-section {
            display: flex;
            align-items: center;
            gap: 15px;
            margin-bottom: 20px;
        }

        .icon {
            font-size: 3em;
            background: rgba(255, 255, 255, 0.2);
            padding: 12px;
            border-radius: 12px;
            backdrop-filter: blur(10px);
        }

        h1 {
            font-size: 2.8em;
            font-weight: 700;
            letter-spacing: -0.5px;
        }

        .tagline {
            font-size: 1.25em;
            font-style: italic;
            line-height: 1.6;
            margin-bottom: 25px;
            opacity: 0.95;
            border-left: 4px solid rgba(255, 255, 255, 0.6);
            padding-left: 20px;
        }

        .bio {
            font-size: 1.1em;
            line-height: 1.8;
            margin-bottom: 25px;
            font-weight: 300;
        }

        .location-info {
            display: flex;
            gap: 30px;
            flex-wrap: wrap;
            font-size: 1.05em;
            margin-bottom: 20px;
        }

        .location-item {
            display: flex;
            align-items: center;
            gap: 8px;
            background: rgba(255, 255, 255, 0.15);
            padding: 8px 16px;
            border-radius: 20px;
            backdrop-filter: blur(5px);
        }

        .mission {
            font-size: 1.05em;
            line-height: 1.7;
            padding: 20px 24px;
            background: rgba(139, 95, 199, 0.4);
            border-radius: 16px;
            backdrop-filter: blur(10px);
            display: flex;
            align-items: flex-start;
            gap: 12px;
        }

        .mission-icon {
            font-size: 1.3em;
            flex-shrink: 0;
        }

        .content {
            padding: 50px;
            background: white;
        }

        .section-title {
            color: #7B8EED;
            font-size: 2em;
            margin-bottom: 30px;
            display: flex;
            align-items: center;
            gap: 12px;
            font-weight: 700;
        }

        .badges {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
        }

        .badge {
            display: inline-flex;
            align-items: center;
            gap: 12px;
            padding: 16px 28px;
            background: linear-gradient(135deg, #7B8EED 0%, #9B6FD7 100%);
            color: white;
            text-decoration: none;
            border-radius: 30px;
            font-weight: 600;
            font-size: 1.05em;
            transition: all 0.3s ease;
            box-shadow: 0 6px 20px rgba(123, 142, 237, 0.4);
        }

        .badge:hover {
            transform: translateY(-4px);
            box-shadow: 0 10px 30px rgba(123, 142, 237, 0.6);
        }

        .badge-icon {
            font-size: 1.3em;
        }

        @media (max-width: 768px) {
            h1 {
                font-size: 2em;
            }

            .header {
                padding: 40px 30px;
            }

            .content {
                padding: 35px 30px;
            }

            .tagline {
                font-size: 1.1em;
            }

            .location-info {
                flex-direction: column;
                gap: 12px;
            }

            .name-section {
                flex-direction: column;
                align-items: flex-start;
            }
        }

        @media (max-width: 480px) {
            .badges {
                flex-direction: column;
            }

            .badge {
                width: 100%;
                justify-content: center;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <div class="header-content">
                <div class="name-section">
                    <div class="icon">📊</div>
                    <h1>Emmanuel Fle Chea</h1>
                </div>
                
                <div class="tagline">
                    "Equity lives in the data. I build systems that make it measurable."
                </div>
                
                <div class="bio">
                    Public health data scientist and biomedical researcher transforming clinical and population‑level data into translational, equitable, and operationally meaningful insights.
                </div>
                
                <div class="location-info">
                    <div class="location-item">
                        <span>📍</span>
                        <span>U.S.-based</span>
                    </div>
                    <div class="location-item">
                        <span>🌍</span>
                        <span>Liberian-rooted</span>
                    </div>
                </div>
                
                <div class="mission">
                    <span class="mission-icon">🎯</span>
                    <span>Building AI systems that advance healthcare equity, national security, and the global public good</span>
                </div>
            </div>
        </div>
        
        <div class="content">
            <h2 class="section-title">
                <span>🔗</span>
                <span>Research Profiles</span>
            </h2>
            
            <div class="badges">
                <a href="https://scholar.google.com/citations?user=UeIJ3uQAAAAJ" class="badge" target="_blank">
                    <span class="badge-icon">🎓</span>
                    <span>Google Scholar</span>
                </a>
                
                <a href="https://orcid.org/0009-0005-1563-2558" class="badge" target="_blank">
                    <span class="badge-icon">🆔</span>
                    <span>ORCID: 0009-0005-1563-2558</span>
                </a>
            </div>
        </div>
    </div>
</body>
</html>


# 📊 Emmanuel Fle Chea

**"Equity lives in the data. I build systems that make it measurable."**

Public health data scientist and biomedical researcher transforming clinical and population‑level data into translational, equitable, and operationally meaningful insights.

📍 U.S.-based | 🌍 Liberian-rooted  
🎯 Building AI systems that advance healthcare equity, national security, and the global public good

### 🔗 Research Profiles
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-Profile-blue?logo=google-scholar)](https://scholar.google.com/citations?user=UeIJ3uQAAAAJ)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0005--1563--2558-brightgreen?logo=orcid)](https://orcid.org/0009-0005-1563-2558)

---

# 👋 About Me

I’m a public health data scientist and biomedical researcher specializing in **large‑scale clinical analytics**, **health economics**, and **machine‑learned biomarker phenotyping**. My work sits at the intersection of:

- **Health services research**  
- **Clinical informatics & NLP**
- **EHR & claims analytics**
- **Predictive modeling & fairness evaluation**  
- **Reproducible pipelines for multi‑million‑record datasets**  
- **Population neuroscience & neurodegeneration research**

I build transparent, equity‑driven analytic frameworks that strengthen health system decision‑making, accelerate translational research, and support national‑scale public health infrastructure.

---

## 📌 Featured Projects

### **Tier 1 - Flagship Research (Core Scientific Identity)**
These projects represent high‑impact, identity‑defining work in **Alzheimer’s biomarkers, equity analytics, and population‑level evaluation**.

---

### 🔬 **ATN vs Machine‑Learned Plasma Biomarker Phenotypes**
Comparative analysis of theory‑driven ATN classification versus data‑driven biomarker phenotypes using k‑means clustering, Gaussian mixture models, PCA, and variational autoencoder (VAE) latent structure. Evaluates concordance, phenotype divergence, and population‑based biomarker patterns.  
**Tech:** R, unsupervised ML phenotyping, clustering, GMM, PCA, VAE  
**Preprint:** https://doi.org/10.64898/2026.01.02.26343331  
**Peer‑review journal publication:** *In progress*  
🔗 https://github.com/efchea1/ATN-vs-Machine-Learned-Plasma-Biomarker-Phenotypes

---

### 🧠 **Equity & Transportability of Plasma ATN Phenotypes**
Fairness, calibration, and population‑representative evaluation of Alzheimer’s plasma biomarkers across U.S. aging cohorts. Includes subgroup performance, calibration drift, and transportability diagnostics.  
**Tech:** R, fairness metrics, calibration, transportability  
**Preprint:** https://doi.org/10.64898/2026.01.31.26344775  
**Peer‑review journal publication:** *In progress*  
🔗 https://github.com/efchea1/Equity-Transportability-Plasma-ATN-Phenotypes

---

### 🧬 **Scalable Plasma Biomarker Phenotyping for Alzheimer’s Disease**
Large‑scale Alzheimer’s heterogeneity analysis using plasma biomarkers, ATN endotyping, clustering, and variational autoencoders (VAE).  
**Tech:** R, Keras/TensorFlow (R), pROC, cluster, DESeq2  
🔗 https://github.com/efchea1/Scalable-Plasma-Biomarker-Phenotyping-for-Alzheimer-s-Disease

---

## 📁 Additional Projects
These projects demonstrate breadth across **Python, R, SAS, ML, clinical outcomes, and public health analytics**.

---

### 🩺 **Liver Disease Prediction (Python)**
Machine‑learning models for liver disease classification using clinical and biochemical features.  
**Tech:** Python, scikit‑learn, pandas, matplotlib  
🔗 https://github.com/efchea1/Liver-Disease-Prediction-Project

---

### ❤️ **Stroke Prediction Models**
Predictive modeling and evaluation for stroke risk using clinical and behavioral risk factors.  
**Tech:** R, R Shiny  
🔗 https://github.com/efchea1/Build-and-deploy-stroke-prediction-models-using-R

---

### 🧪 **Biomarkers & Clinical Covariates for Predicting Prostate Cancer Recurrence**
Clinical outcomes study integrating biomarkers and covariates to model biochemical recurrence after prostate cancer treatment.  
**Tech:** R  
🔗 https://github.com/efchea1/Biomarkers-and-Clinical-Covariates-for-Predicting-Prostate-Cancer-Recurrence

---

### 🩸 **RBC Storage Duration & Prostate Cancer Recurrence (SAS)**
SAS‑based clinical outcomes analysis evaluating the impact of allogeneic RBC storage duration on biochemical recurrence after radical prostatectomy.  
**Tech:** SAS  
🔗 https://github.com/efchea1/Evaluation-of-RBC-Storage-Duration-on-Prostate-Cancer-Recurrence-Post-Prostatectomy

---

### 💓 **Cardiovascular Risk Prediction**
Machine‑learning models for chronic disease risk prediction using BRFSS data.  
**Tech:** R  
🔗 https://github.com/efchea1/Predictive-Analytics-for-Cardiovascular-Disease-Prevention

---

### 🗺️ **CDC PLACES Regional Health Mapping**
Community‑level chronic disease mapping and health equity analytics for Minnesota.  
**Tech:** R, R Shiny  
🔗 https://github.com/efchea1/Analytic_Project_Regional-Health-Mapping-Harnessing-CDC-PLACES-Data-for-Minnesota-Community-Health-

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
