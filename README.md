<div align="center">

# Hi, I'm Pranavi 👋

**Data Science & AI student building explainable ML systems for credit, risk and fintech**

B.Tech Data Science & AI · Sai University, Chennai · CGPA 8.84

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Pranavi%20Devulapalli-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pranavi-devulapalli-359ba2281/)
[![GitHub](https://img.shields.io/badge/GitHub-Pranavi0525-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Pranavi0525)
![Status](https://img.shields.io/badge/Open%20to-Internships%20from%20Jan%202027-2ea44f?style=flat-square)

</div>

---

## About me

I'm a final-year Data Science & AI student who likes the part of machine learning that comes after the notebook: serving a model behind an API, explaining each prediction, auditing it for fairness, and keeping a record of every decision. My focus is **credit risk and fintech**, and I'm increasingly drawn to **agentic AI** systems.

I've interned at **CareEdge Analytics** (climate risk for credit models) and **Britannia Industries** (analytics and automation). I'm looking for a **data science / ML internship from January 2027**, ideally in credit, risk or fintech.

---

## Experience

| Role | Where | What I did |
| --- | --- | --- |
| **Intern, Product Development (Consulting)** | CareEdge Analytics (CARE Ratings) · Jul–Aug 2026 | Built a climate-risk data pipeline that maps **19,586 Indian pincodes** to seismic, cyclone, landslide and terrain hazards, with **99.89% coverage**. It feeds PD/LGD credit risk models in the SEBI/RBI climate-disclosure context. Used Open-Meteo APIs and geospatial processing, and worked with Urban Cooperative Bank datasets. |
| **Data Analytics Intern** | Britannia Industries | Built Power BI dashboards on SAP data and automated reporting workflows in Python. |

---

## Featured projects

### 🛡️ [OpenFinGuard](https://github.com/Pranavi0525/OpenFinGaurd): AI credit intelligence platform
An end-to-end, production-patterned credit risk system trained on 150K borrowers.

- GradientBoosting champion model: **AUC-ROC 0.863 · KS 0.512 · PR-AUC 0.489**, with inference in **under 10 ms**
- Four-model comparison, with a composite champion score (AUC, KS, PR-AUC, speed)
- **SHAP** adverse-action reasons for every decision, in plain English
- **Fairness audit** using the ECOA 80% rule across age, income and dependents
- **PostgreSQL audit trail** of every prediction, with features, explanations and model version
- Streamlit dashboard, FastAPI backend, fully containerised with Docker Compose

`Python` `scikit-learn` `SHAP` `FastAPI` `PostgreSQL` `Docker` `Streamlit` `MLflow`

### ⚡ [Real-Time Fraud Detection](https://github.com/Pranavi0525/realtime-fraud-detection)
A streaming fraud-scoring pipeline on **590K IEEE-CIS transactions** (**AUC-ROC 0.949**), with an LLM agent on top for analyst-style explanations.

`Kafka` `Redis` `XGBoost` `Groq (LLaMA)` `Python`

### 🤖 Trust-Based Autonomous Shopping Agent *(team project)*
An agent that turns natural-language shopping requests into structured intents and executes them against Shopify via MCP. A Gemini planner produces schema-validated plans, and a deterministic LangGraph executor runs them, with SQLite state and a Streamlit UI.

`Gemini` `LangChain` `LangGraph` `Shopify MCP` `Pydantic` `SQLite` `Streamlit`

### 📋 PlaceWise: job application tracker
A full-stack tracker for internship and job applications, with Gmail OAuth to pick up application emails and Gemini to help categorise them. Deployed on Vercel and Render.

`React` `FastAPI` `PostgreSQL` `Gmail OAuth` `Gemini API`

### 🏦 [CreditSafe](https://github.com/Pranavi0525/Credit_Risk_System): loan risk assessment app
An XGBoost loan-default predictor with an applicant view (instant risk result, auto-generated offer or appeal letter) and a password-protected manager dashboard with live KPIs. Applications are logged to Google Sheets. **[Live demo →](https://creditrisksystem-2i4vpzd3mgyisouna38rbg.streamlit.app/)**

`XGBoost` `Streamlit` `Google Sheets API`

---

## Tech stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189AB4?style=flat-square)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

| Area | Tools |
| --- | --- |
| **ML & modelling** | scikit-learn, XGBoost, SHAP, MLflow, imbalanced-data handling, credit scorecard metrics (AUC, KS, PR-AUC) |
| **Responsible AI** | Explainability, fairness auditing (ECOA 80% rule), audit trails |
| **Backend & data** | FastAPI, PostgreSQL, SQLAlchemy, Pydantic, Kafka, Redis |
| **Agentic AI** | LangChain, LangGraph, MCP, Gemini, Groq / LLaMA |
| **Analytics** | Power BI, SAP data, Pandas, geospatial pipelines |
| **Deployment** | Docker, Docker Compose, Streamlit Cloud, Vercel, Render |

---

## Domain interests

- **Credit risk modelling:** PD/LGD, rating methodologies (CAMEL-style frameworks for Urban Cooperative Banks), climate risk in lending
- **Fintech compliance:** KYC frameworks (PMLA, V-CIP, eKYC, CDD/EDD), adverse-action and fairness requirements
- **Production ML:** the gap between a good notebook and a system someone can trust

---

## Currently

- 🔨 Building agentic systems with planner/executor architectures
- 📚 Deepening fintech system design and credit-domain knowledge
- 🎯 Looking for a data science / ML internship starting **January 2027**

---

## Let's connect

If you're hiring interns in credit, risk or fintech ML, or just want to talk about any of the above, reach me on [LinkedIn](https://www.linkedin.com/in/pranavi-devulapalli-359ba2281/).
