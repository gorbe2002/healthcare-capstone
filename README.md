# Environmental Carcinogenesis Decoded: Tracing Cancer's Roots with Advanced Machine Learning

By: Danielle Grunwald, Gabriel Orbe, Badr Abushaar

This repository contains the code, data, and documentation for our research, which investigates the relationship between environmental pollution and cancer incidence rates for bladder and lung cancers.

## Table of Contents

- [Abstract](#abstract)
- [Repository Structure](#repository-structure)
- [Getting Started](#getting-started)
- [Data Sources](#data-sources)
- [Methodology Overview](#methodology-overview)
- [Results](#results)

## Abstract

## Repository Structure

The data/ folder contains the preprocessed data utilized when creating our models.

```bash
healthcare-capstone/
├── data/                                   # Preprocessed datasets
├── data_pulls/                             # Raw data sources
├── feature_engineering.ipynb               # Feature engineering steps
├── MLPmodel.ipynb                          # Multilayer Perceptron model
├── decisionTreeModel.ipynb                 # Decision Tree model
├── model.ipynb                             # Additional modeling approaches
├── modelcomparison_transformer.ipynb       # Model comparison using transformers
├── StatAnalysis.ipynb                      # Statistical analysis
├── OtherMLApproaches.ipynb                 # Other machine learning models
└── README.md                               # Project documentation
```

## Getting Started

1. **Clone the Repository**

   ```bash
   git clone https://github.com/gorbe2002/healthcare-capstone.git
   cd healthcare-capstone

   ```

2. **Set Up Your Environment**

   ```bash
   python -m venv venv
   source venv/bin/activate
   ```

3. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

## Data Sources

Cancer Incidence:

- National Health Institute: "Surveillance, Epidemiology, and End Results (SEER) Program"
- Centers for Disease Control and Prevention: "Wonder Incidence"

Air Pollution:

- United States Environmental Protection Agency: "Air Quality System (AQS)"

Bladder Pollution:

- United States Environmental Protection Agency: "Toxics Release Inventory (TRI)"
- United States Environmental Protection Agency: "Assessment, Total Maximum Daily Load (TMDL) Tracking and Implementation System (ATTAINS)"

## Methodology Overview

## Results
