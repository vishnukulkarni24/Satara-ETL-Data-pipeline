# Satara-ETL-Data-pipeline
Data Engineering project demonstrating Extract–Transform–Load (ETL) workflow with Pandas and Parquet outputs.

# 🧱 SATARA 1991 ETL Data Pipeline (Jupyter Notebook)

This project demonstrates a **complete ETL (Extract → Transform → Load)** pipeline using **Python and Jupyter Notebook** for the 1991 Satara district dataset.

It follows a structured approach commonly used by **Data Engineers** for data ingestion, cleaning, transformation, enrichment, and storage.

---

## 🚀 Project Overview

**Goal:**  
To clean, enrich, and analyze demographic data for Satara district (1991), generating insights such as:
- ✅ Literacy rate  
- ✅ Sex ratio (Females per 1000 Males)  
- ✅ CSV and Parquet output formats  
- ✅ Visualized distributions for insights  

---

## 🧩 Tech Stack

| Component | Technology |
|------------|-------------|
| Language | Python 3 |
| Environment | Jupyter Notebook / VS Code |
| Data Libraries | Pandas, NumPy, Matplotlib |
| File Formats | CSV, Parquet |
| Config Management | YAML |

---

## 🗂️ Project Structure

satara_etl_project/
│
├── data/
│ └── SATARA_1991.csv
│
├── output/
│ ├── SATARA_1991_enriched.csv
│ └── SATARA_1991_enriched.parquet
│
├── SATARA_1991_ETL.ipynb ← main ETL notebook
├── requirements.txt
└── README.md
