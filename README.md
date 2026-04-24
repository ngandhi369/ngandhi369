<h1 align="center">Nirdosh Gandhi</h1>

<p align="center">
  <b>Data Engineer · Azure Databricks · Lakehouse Architecture · MLflow · PySpark</b>
</p>

<p align="center">
  <a href="https://linkedin.com/in/nirdosh-gandhi">
    <img src="https://img.shields.io/badge/LinkedIn-Nirdosh%20Gandhi-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://databricks-asset-bundle-deployment.onrender.com">
    <img src="https://img.shields.io/badge/Live%20API-Render.com-46E3B7?style=flat-square&logo=render&logoColor=white"/>
  </a>
  <img src="https://img.shields.io/badge/Databricks%20Certified-Data%20Engineer%20Associate-FF6B35?style=flat-square&logo=databricks&logoColor=white"/>
  <img src="https://img.shields.io/badge/M.Tech%20AI-DTU%20·%208.95%20CGPA-blue?style=flat-square"/>
</p>

---

> *I build data pipelines that survive production.*

Currently at **Axtria (Bengaluru)**, designing Spark-based Lakehouse systems for pharmaceutical clients — serving **300+ sales reps** across 10 markets with ML-driven HCP engagement recommendations via Veeva CRM.

- 🏗️ Specialise in **medallion Lakehouse architecture** (Bronze → Silver → Gold) with Unity Catalog governance across DEV / UAT / PROD
- ⚡ Reduced Spark ETL execution time by **60%** through partition strategy refinement and join optimisation
- 🤖 Build **ML-integrated data workflows** — from raw ingestion to model scoring pipelines consumed by downstream CRM systems
- 🚀 Automate everything — **Databricks Asset Bundles + GitHub Actions** = zero-touch, repeatable deployments

---

## 🔥 Featured Project

### [Databricks End-to-End Data Product](https://github.com/ngandhi369/databricks-e2e-data-product)

![CI/CD](https://img.shields.io/github/actions/workflow/status/ngandhi369/databricks-e2e-data-product/deploy.yml?label=CI%2FCD&logo=githubactions&style=flat-square)
![Python](https://img.shields.io/badge/Python-3.12-blue?style=flat-square&logo=python)
![Databricks](https://img.shields.io/badge/Databricks-Asset%20Bundle-FF6B35?style=flat-square&logo=databricks)

> Production-grade data product: CSV ingestion → Medallion Lakehouse → ML segmentation → AI-assisted dashboard → automated report delivery → live REST API. Fully automated. No manual steps.

**🌐 Live API:** https://databricks-asset-bundle-deployment.onrender.com  
**📖 Swagger UI:** https://databricks-asset-bundle-deployment.onrender.com/docs

- Architected a fully automated, end-to-end Databricks data product covering CSV ingestion, Bronze → Silver → Gold medallion transformation, ML training, dashboard analytics, and live API serving — deployed with zero manual steps via GitHub Actions CI/CD.
- Implemented idempotent Delta MERGE-based ETL using PySpark alongside a parallel Delta Live Tables (DLT) pipeline with `@dlt.expect` constraints for declarative data quality enforcement and pipeline lineage tracking.
- Trained and registered a scikit-learn KMeans customer segmentation model in Unity Catalog Model Registry via MLflow, evaluating cluster quality with silhouette score and elbow method across k=2–6.
- Built a Databricks SQL Dashboard ("Customer Intelligence Dashboard") with 4 visualisations — top customers, revenue by city, recency distribution, and ML segment breakdown — integrated with Databricks Genie for natural language querying; configured automated hourly report delivery to subscribed stakeholders post pipeline completion.
- Deployed a FastAPI on Render.com backed by Databricks Serverless (Spark Connect) for live query execution, with API key authentication and Swagger UI. Automated full deployment via Databricks Asset Bundles (DAB) and GitHub Actions across DEV/PROD with approval gates, ruff linting, and pytest smoke tests.

| Component | Stack |
|---|---|
| Medallion ETL (Bronze → Silver → Gold) | PySpark · Delta Lake · Delta MERGE |
| Declarative pipeline with data quality | Delta Live Tables · `@dlt.expect` |
| KMeans customer segmentation | scikit-learn · MLflow · Unity Catalog Model Registry |
| Customer Intelligence Dashboard | Databricks SQL · Genie AI (natural language queries) |
| Automated report delivery to subscribers | Databricks Dashboard Subscriptions (hourly) |
| Live REST API with authentication | FastAPI · Spark Connect · Render.com |
| Zero-touch CI/CD across DEV & PROD | GitHub Actions · Databricks Asset Bundles |

---

## 🛠️ Tech Stack

**Data Engineering**

![Databricks](https://img.shields.io/badge/Databricks-FF6B35?style=flat-square&logo=databricks&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta%20Lake-00ADD8?style=flat-square)
![Unity Catalog](https://img.shields.io/badge/Unity%20Catalog-1A1F36?style=flat-square)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![ADF](https://img.shields.io/badge/Azure%20Data%20Factory-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)

**ML & Experimentation**

![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Databricks Genie](https://img.shields.io/badge/Databricks%20Genie-FF6B35?style=flat-square&logo=databricks&logoColor=white)

**CI/CD & Orchestration**

![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure%20DevOps-0078D7?style=flat-square&logo=azuredevops&logoColor=white)
![Databricks Asset Bundles](https://img.shields.io/badge/Databricks%20Asset%20Bundles-FF6B35?style=flat-square&logo=databricks&logoColor=white)

**API & Serving**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=white)

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

---

## 🏅 Certifications

<p align="center">
  <img alt="Databricks Certified Data Engineer Associate" src="https://github.com/user-attachments/assets/d0ce3c5b-80cb-4095-9c83-3cf06e0babbc" height="180"/>
  &nbsp;&nbsp;
  <img alt="Azure AI Fundamentals" src="https://github.com/user-attachments/assets/3959f339-932f-49a2-8f4a-8a55defeb32a" height="180"/>
  &nbsp;&nbsp;
  <img alt="ML Specialization" src="https://github.com/user-attachments/assets/68140509-a671-4515-9177-8fb7a6e7b8e7" height="180"/>
</p>

---

## 📝 Latest Writing

- 🚀 [From Azure DevOps to GitHub Actions: How We Modernised Our Databricks CI/CD](https://www.linkedin.com/in/nirdosh-gandhi/)

---

## 🤝 Let's Connect

<p align="center">
  <a href="https://linkedin.com/in/nirdosh-gandhi">
    <img src="https://img.shields.io/badge/LinkedIn-%231E77B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://medium.com/@nirdoshgandhi">
    <img src="https://img.shields.io/badge/Medium-%23000000.svg?&style=for-the-badge&logo=medium&logoColor=white"/>
  </a>
  <a href="https://scholar.google.com/citations?user=2qR2A08AAAAJ&hl=en">
    <img src="https://img.shields.io/badge/Google%20Scholar-%2300acee.svg?&style=for-the-badge&logo=googlescholar&logoColor=white"/>
  </a>
  <a href="mailto:nirdoshgandhi02@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
</p>

---

<p align="center">
  <i>M.Tech Artificial Intelligence · Delhi Technological University · CGPA 8.95 · IEEE Published · Axtria Bravo Award 2025</i>
</p>
