# Data Engineering Projects – Medallion Architecture

## Overview
This repository demonstrates end-to-end data engineering pipelines using the **Medallion Architecture** (Bronze, Silver, Gold layers). It highlights how raw data is ingested, transformed, and curated into business-ready datasets using **Azure Fabric, Python, SQL, and KQL**.

The project reflects my learning journey in data engineering, showcasing practical applications of industry-standard practices and my commitment to continuous upskilling.

---

## Architecture

- **Bronze Layer (Raw Data)**
  - Stores raw, unprocessed files (CSV, JSON, Parquet).
  - Purpose: Preserve data exactly as ingested for reproducibility.

- **Silver Layer (Enriched Data)**
  - Applies cleaning, deduplication, type casting, and schema alignment.
  - Purpose: Create standardized, analytics-ready datasets.

- **Gold Layer (Curated Data)**
  - Applies business logic, joins, and KPI calculations.
  - Purpose: Deliver curated datasets for downstream consumption.

---

## Tech Stack
- **Languages:** Python, SQL
- **Platform:** Microsoft Fabric (Lakehouse, Pipelines)
- **Tools:** GitHub for version control
- **Certifications:** 
  - Microsoft DP-900 (Azure Data Fundamentals)
  - Microsoft DP-700 (Fabric Data Engineer Associate – in progress)

---

## Repository Structure
Medallion_Architecture/
├── bronze/   # Raw files and ingestion scripts
├── silver/   # Transformation scripts and enriched outputs
├── gold/     # Curated datasets and business-ready outputs
└── docs/     # Architecture diagrams, notes
pipelines/      # Fabric pipeline definitions
notebooks/      # PySpark notebooks
sql/            # Warehouse scripts
README.md       # Project overview


---

## How to Use
1. Clone the repository.
2. Explore the Bronze → Silver → Gold flow.
3. Run notebooks/pipelines to reproduce transformations.
4. Review curated outputs in the Gold layer.

---

## Future Work
- Add small sample datasets to each layer (anonymized for sharing).
- Document transformation rules applied in the Silver layer.
- Include architecture diagrams in `/docs`.
- Add unit tests for data validation.

---

## Author
**Imraan Thabang Leeuw**  
- Passionate about data engineering and continuous learning.  
- Actively building skills in Python, SQL, KQL, and Azure Fabric.  
- Certified in DP-900, preparing for DP-700.  
