# Football Players Selection System (Scouting & Recommendation)
**PSUT Graduation Project (GP) — 2025/2026**

A data-driven football scouting and player recommendation system that helps clubs evaluate, compare, and shortlist players using multi-season performance data and machine learning.

---

## Overview
This project supports **objective, explainable player selection** by combining:
- A complete **data pipeline** (collection → cleaning → integration → feature engineering)
- **Machine Learning models** for player/position analysis (with strong focus on LR & SVM)
- Clear outputs for **profiling and comparison** (scores, rankings, and performance summaries)

The goal is to help decision-makers shortlist players based on performance indicators and role fit, instead of relying only on subjective scouting.

---

## Key Objectives
- Build a reliable, structured dataset from multiple football statistics sources (multi-season).
- Clean and standardize data to make it suitable for analysis and modeling.
- Create **composite features** that summarize performance (general + position-aware).
- Train and evaluate ML models (focus: **Logistic Regression** and **SVM**) and report results clearly.
- Produce documentation and presentation material as an academic deliverable.

---

## What’s Included in This Repository
Depending on the version of the repository, it may include:
- Jupyter notebooks for **EDA, preprocessing, and modeling**
- Feature engineering code for **composite metrics**
- Model training and evaluation code (LR/SVM + supporting experiments)
- Project documentation and final report files
- (Optional) small sample outputs or figures used in the report/presentation

> Note: Some datasets may not be included due to size and/or licensing.

---

## Data & Feature Engineering (High Level)
### Data Processing
- Cleaned raw football statistics data (types, missing values, duplicates)
- Standardized categorical fields (e.g., competitions, seasons, positions)
- Integrated multiple statistical tables into a unified analysis-ready structure

### Composite Features
To make scouting decisions easier and more consistent, we engineered composite metrics that summarize multiple raw indicators into higher-level signals (e.g., overall contribution, defensive/attacking involvement, passing effectiveness), including position-aware variations.

---

## Modeling (High Level)
### Main Models (Core Focus)
- **Logistic Regression (LR)**
- **Support Vector Machine (SVM)**

Work included:
- preparing model-ready features
- selecting suitable preprocessing steps
- training + evaluation using standard classification metrics
- documenting decisions and results clearly for the GP report

### Supporting Components
Additional experiments and supporting pipelines were used as needed to validate features, compare approaches, and build the overall system workflow.

---
## Team & Contributions
This is a team graduation project at Princess Sumaya University for Technology (PSUT).

**Team Members**
- **Mariam Raed Yaqoub**
  - Data preprocessing (cleaning, standardization, integration, analysis-ready dataset)
  - Led **Logistic Regression (LR)** and **SVM** modeling
  - Model evaluation + reporting (results interpretation and documentation)

- **Husam Sawaqed**
  - Composite features / feature engineering
  - Literature review
  - Added composite features to the dataset + validation support

- **Seddiq Al-Khazraji**
  - System design + overall pipeline structure
  - Dataset preparation, experiments, and integration tasks
  - Documentation/presentation support + end-to-end alignment

> All members collaborated across planning, implementation, testing, reporting, and presentation.  
> The bullets above describe each member’s primary responsibilities.

