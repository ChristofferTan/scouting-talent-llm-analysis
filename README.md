# Reconstructing the perception of sports talent through the view of scouts:  A textual analysis with Large Language Models

This project analyzes how player “talent” is described in NHL scouting reports using a combination of large language models (LLMs) and statistical analysis. We extract structured information from unstructured scouting reports and study how different traits are used to evaluate players across positions and over time.

---

## 📊 Project Overview

Scouting reports are inherently subjective and written in natural language. This project aims to make these evaluations more interpretable and quantifiable by:

- Extracting key phrases describing player attributes
- Classifying phrases as **strengths** or **weaknesses**
- Categorizing them into four trait dimensions:
  - Physical  
  - Technical  
  - Tactical  
  - Psychological  

Using this structured representation, we analyze:
- Differences between **forwards and defensemen**
- Common language used by scouts
- **Temporal trends** across draft years

---

## 📁 Repository Structure
```bash
nhl-scouting-trait-analysis/
│
├── data/
│ └── scouting_traits_processed.xlsx
├── notebooks/
│ ├── 01_llm_pipeline.ipynb
│ └── 02_visualizations.ipynb
└── README.md
```
### 📂 Description

- **data/**
  - `scouting_traits_processed.xlsx`: Processed output from the LLM pipeline containing extracted traits and classifications.

- **notebooks/**
  - `01_llm_pipeline.ipynb`: Extracts phrases from scouting reports and classifies them into trait categories.
  - `02_visualizations.ipynb`: Generates all visualizations, including trait distributions, temporal trends, and word clouds.

---

## ⚙️ How to Run

### 1. LLM Pipeline
Run: `notebooks/01_llm_pipeline.ipynb`
This notebook:
- Processes scouting reports
- Extracts phrases
- Assigns sentiment and trait categories
- Outputs structured data to `data/scouting_traits_processed.xlsx`

---
### 2. Data Visualization
Run: `notebooks/02_visualizations.ipynb`
This notebook:
- Generates all figures used in the analysis:
  - Trait distribution (bar plots)
  - Phrase clouds (word clouds)
  - Temporal trends (stacked area charts)
  - Radar plots

---

## 📈 Key Findings
- Strengths differ by position:
  - Forwards emphasize technical traits  
  - Defensemen emphasize physical and tactical traits  

- Weaknesses are consistent across positions:
  - Physical limitations dominate for both  

- Trait distributions are stable over time, with some convergence in later years  

---

## 🧠 Methodology

- Large Language Model (LLM) used to extract and classify phrases from scouting reports  
- Traits categorized into four dimensions: physical, technical, tactical, and psychological  
- Statistical analysis performed on player-level and aggregate distributions  
- Visualization techniques used to analyze positional differences and temporal trends  

---

## 📌 Notes

This repository accompanies a research project on quantifying talent in sports using NLP and statistical methods.

