# 📊 Sole Fitness Analytics

A business analytics project developed for the *EBA5001: Practice Module in Analytics Project Management* as part of the Master’s in Business Analytics (NUS).  
Our team, **FitForward Analytics**, partnered with Sole Fitness Singapore to tackle real-world retail and marketing inefficiencies using data-driven solutions.
Note: As this project was done for a operational company, the data is confidential, relevant details can be found in 04 - sole-fitness-project-report.pdf
---

## 🚀 Project Overview

Sole Fitness, a sports equipment SME in Singapore, was facing challenges in unifying sales data sources (Website, Lazada, Shopee), optimising their advertising spend and product mix across its website and marketplace platforms (Lazada and Shopee).  
This project uses data integration on postgreSQL, clustering, regression modelling, and power BI dashboarding. 

---

## 🎯 Project Objectives

### 🧩 Business Objectives

- Developed a postgreSQL data base that integrates sales data sources from Sole Fitness Website, Lazada and Shopee pages. 
- Diversify revenue sources by reducing reliance on treadmill sales.
- Optimise advertising spend across platforms and product categories.

### 🧪 Technical Deliverables

- Cleaned and integrated multi-source sales and ad data on postgreSQL
- Implemented clustering (K-Means) for product segmentation.
- Built correlation metrics to link ad spend with revenue.
- Developed Power BI dashboards updated via automated ETL.

---

## 🧰 Tools & Tech Stack

- **PostgreSQL** for database modelling
- **Sentence-BERT** for product name matching
- **Python** (pandas, scikit-learn, seaborn, matplotlib)
- **Power BI** for dashboards
- **Google Colab** for collaboration
- **Excel** for source data analysis

---

## 📂 Project file Structure as on Github

The project files are organised as follows:

| File Name                             | Description                                                                 |
|--------------------------------------|-----------------------------------------------------------------------------|
| `01 - postgreSQL database.sql`       | SQL dump file for recreating the PostgreSQL database schema and data       |
| `02 - sole-fitness-clustering.ipynb` | Python notebook for clustering analysis using scikit-learn |
| `03 - sole-fitness-dashboards.pbix`  | Power BI dashboard visualising key project findings                         |
| `04 - sole-fitness-project-report.pdf`| Final project report documenting business problems, methodology, analysis, and recommendations |
