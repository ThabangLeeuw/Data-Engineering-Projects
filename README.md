# Data Engineering Projects – Medallion Architecture

## Overview
This repository showcases my journey in data engineering using the **Medallion Architecture** (Bronze, Silver, Gold layers). It demonstrates how raw data is ingested, enriched, and curated into structured outputs using **Azure Fabric, Python, SQL, and KQL**.  

The repo includes datasets, code snippets, and architecture visuals to illustrate the complete pipeline lifecycle.

---

## Architecture

- **Bronze Layer (Raw Data)**
  - Contains raw datasets in the `raw_data` directory.
  - Purpose: Preserve ingested data in its original form for reproducibility.

- **Silver Layer (Enriched Data)**
  - Transformation scripts and enriched outputs.
  - Purpose: Apply cleaning, deduplication, type casting, and schema alignment.

- **Gold Layer (Curated Data)**
  - Business-ready datasets with applied logic and KPIs.
  - Purpose: Deliver curated outputs for downstream consumption.

---

## Tech Stack
- **Languages:** Python, SQL, KQL  
- **Platform:** Microsoft Fabric (Lakehouse, Eventhouse, Pipelines)  
- **Tools:** GitHub for version control  
- **Certifications:**  
  - Microsoft DP-900 (Azure Data Fundamentals)  
  - Microsoft DP-700 (Fabric Data Engineer Associate – in progress)  

---

## Repository Structure

Medallion_Architecture/
├── bronze/        # Raw ingestion scripts
├── silver/        # Transformation logic
├── gold/          # Curated outputs
raw_data/            # Sample raw datasets
imgs/                # Lakehouse & DWH snippets, architecture visuals
pipelines/           # Fabric pipeline definitions
notebooks/           # PySpark/KQL notebooks
dwh/                 # Warehouse scripts
README.md            # Project overview

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
