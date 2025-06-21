# 🏅 Tokyo Olympic Data Analytics | Azure End-to-End Data Engineering Project

This project showcases a full-stack Azure Data Engineering pipeline for analyzing Tokyo Olympics data. Using enterprise-grade tools like 
**Azure Data Factory**, 
**Data Lake Gen2**, 
**Databricks**, and 
**Synapse Analytics**, the project processes raw CSV data into insightful dashboards via **Power BI** and **Tableau**.

![Architecture Diagram](Workflow%20Diagram.png)

---

## 🚀 Architecture Overview

1. **Data Ingestion:**
   - Raw `.csv` files (athletes, medals, teams, coaches, etc.) sourced from public Olympic datasets
   - Ingested using **Azure Data Factory** pipelines

2. **Storage Layer:**
   - Files are stored in **Azure Data Lake Storage Gen2** under a raw zone
   - Post-transformation data is saved in a curated/clean zone

3. **Transformation:**
   - **Azure Databricks** used to clean, join, and transform datasets using PySpark and notebooks
   - Data reshaped for reporting and analysis

4. **Analytics:**
   - Transformed data queried and analyzed using **Azure Synapse Analytics**

5. **Dashboarding:**
   - Final visualizations created using **Power BI**, **Looker Studio**, and **Tableau**

---

## 📊 Key Datasets

- `Athletes.csv` – Athlete demographics and countries
- `Coaches.csv` – Assigned coaches per sport/team
- `Medals.csv` – Medal winners and countries
- `EntriesGender.csv` – Gender participation metrics
- `Teams.csv` – Teams by country and sport

---

## 📌 Project Goals

- Analyze medal distribution by country and gender
- Identify athlete and coach trends by sport and region
- Track gender-based participation and performance
- Build a reusable cloud-native analytics workflow

---

## 🛠 Tech Stack

| Layer            | Tool                        |
|------------------|-----------------------------|
| Ingestion        | Azure Data Factory          |
| Storage          | Azure Data Lake Storage Gen2|
| Processing       | Azure Databricks (PySpark)  |
| Analytics Engine | Azure Synapse Analytics     |
| Visualization    | Power BI / Tableau / Looker |

---

## 🧠 Insights Delivered

- Country-wise medal tally and podium trends
- Female vs male participation across events
- Coach assignment analysis by gender and nation
- Identification of top-performing athletes and sports

---

## 🔄 Future Improvements

- Real-time dashboard updates via Azure Event Grid or Streaming
- Add historical Olympics data for temporal comparison
- Use ML models in Databricks for medal prediction or clustering

---
