# 📊 Metadata-Driven Pipeline Project

## Overview
This project demonstrates a **metadata-driven data ingestion pipeline** built in Microsoft Fabric.  
It automates ingestion of CSV files, applies conditional logic, and integrates with Microsoft Teams for alerts.  

---

## 🎯 What I Learned

### 1. Metadata-Driven Design
- How to use **Get Metadata** activities to dynamically retrieve file information.  
- Why metadata-driven pipelines are more **scalable and reusable** than hard-coded ones.  

### 2. Conditional Logic & Iteration
- Implementing **For Each loops** to process multiple files.  
- Using **If Condition / IfNotSatisfied** activities to handle exceptions gracefully.  
- Designing pipelines that adapt to different scenarios without manual intervention.  

### 3. Error Handling & Notifications
- Configuring **failure notifications** to ensure issues are caught early.  
- Integrating with **Microsoft Teams alerts** for real-time monitoring.  
- Understanding the importance of **observability** in data engineering.  

### 4. Data Lifecycle Management
- How to filter and clean incoming CSV files before ingestion.  
- Why separating **raw, staging, and curated zones** in ADLS Gen2 improves governance.  
- Best practices for deleting or archiving unnecessary files safely.  

### 5. Professional Project Documentation
- Exporting pipeline and activity definitions as **JSON files** for reproducibility.  
- Structuring a GitHub repo with clear folders (`activities/`, `datasets/`, `linkedServices/`, `docs/`).  
- Writing READMEs that explain **architecture, lessons learned, and usage instructions**.  

---
