# Credit Score Prediction

## Project Overview

**Business Issue:** A fictional company wants to make its credit analysis process more efficient, scalable, and data-oriented. Currently, part of the client analysis still depends on manual labor, which makes the process slow and prone to inconsistencies.

**Main Objective:** Build a predictive model capable of classifying a client's credit score based on financial information, payment history, credit profile, and behavior.

## Dataset

This project uses the [Credit Score Classification](https://www.kaggle.com/datasets/parisrohan/credit-score-classification) dataset, publicly available on Kaggle. It contains credit-related information used to classify individuals into credit score categories (Poor, Standard, Good).

> Data files are not included in this repository (see `.gitignore`). To reproduce this project, download the dataset from the link above and place it in `data/raw/`.

## Technologies Used

- **Language:** Python
- **Environment:** Google Colab
- **Tools:** Pandas, Scikit-learn, Seaborn, Matplotlib

## Project Status

This repository is being published incrementally, as each stage of the project is completed.

- [x] Acquire data - Initial Data Exploration
- [ ] Scrub - Data Preparation
- [ ] Explore - Exploratory Data Analysis
- [ ] Model - Predictive Modeling
- [ ] Interpret - Model Evaluation
- [ ] Communicate - Final Report & Documentation

## Project Organization

This repository follows the [Cookiecutter Data Science](https://cookiecutter-data-science.drivendata.org/) structure.

```text
.
├── data/                   <- Data files (not versioned, see .gitignore)
├── notebooks/              <- Jupyter/Colab notebooks
├── reports/                <- Generated analysis and figures
├── src/                    <- Source code for use in this project
│   ├── __init__.py         <- Makes credit_score_prediction a Python module
│   ├── config.py           <- Store useful variables and configuration
│   ├── dataset.py          <- Scripts to download or generate data
│   ├── features.py         <- Code to create features for modeling
│   ├── modeling/                
│   │   ├── __init__.py 
│   │   ├── predict.py      <- Code to run model inference with trained models          
│   │   └── train.py        <- Code to train models
│   └── plots.py            <- Code to create visualizations
└── README.md

