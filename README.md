# 📊 Sole Fitness Analytics

A business analytics project developed for the *EBA5001: Practice Module in Analytics Project Management* at NUS.  
Our team, **FitForward Analytics**, partnered with Sole Fitness Singapore to address retail and marketing inefficiencies through data-driven solutions.

> 📌 *Note: Due to confidentiality, raw data is not shared. Key findings and methods are documented in the final report.*

---

## 🚀 Project Overview

Sole Fitness, a fitness equipment SME in Singapore, faced challenges integrating sales data from its website, Lazada, and Shopee, and lacked visibility on advertising ROI and product category performance.

This project delivered end-to-end analytics using PostgreSQL, clustering, regression, and Power BI dashboards.

---

## 🎯 Objectives

### 🧩 Business Goals
- Integrate sales data across all platforms into a single database.
- Reduce revenue dependence on treadmill sales.
- Optimise ad spend by platform and product category.

### 🧪 Technical Outcomes
- Built a normalised **PostgreSQL** database for sales and ad data.
- Applied **K-Means clustering** to segment products.
- Conducted **correlation analysis** between ad spend and sales.
- Developed interactive **Power BI dashboards** refreshed via automated ETL.

---

## 🧰 Tech Stack

- **PostgreSQL** – Data warehousing  
- **Python** – Analysis (`pandas`, `scikit-learn`, `matplotlib`, `seaborn`)  
- **Sentence-BERT** – Product name matching  
- **Power BI** – Dashboard development  
- **Google Colab**, **Excel** – Data processing & collaboration  

---

## 📁 File Structure

| File Name                             | Description                                                         |
|--------------------------------------|---------------------------------------------------------------------|
| `01 - postgreSQL database.sql`       | SQL dump to recreate the PostgreSQL schema and base tables          |
| `02 - sole-fitness-clustering.ipynb` | Clustering notebook using scikit-learn                              |
| `03 - sole-fitness-dashboards.pbix`  | Power BI dashboard file                                             |
| `04 - sole-fitness-project-report.pdf`| Full project documentation with insights, visuals, and recommendations |

