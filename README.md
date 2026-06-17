# End-to-End ML Pipleine for Spam Message Classification using DVC & AWS S3

## Overview

An end-to-end Machine Learning pipeline for SMS spam detection built using NLP techniques, DVC for pipeline orchestration, DVCLive for experiment tracking, and AWS S3 as remote storage for versioned artifacts and datasets. The project follows MLOps best practices by enabling reproducible experiments, parameterized workflows, and automated pipeline execution.

---

## Key Features

* Automated ML pipeline using DVC
* Remote artifact storage with AWS S3
* Experiment tracking using DVCLive
* Parameter management with YAML
* NLP preprocessing using NLTK
* Random Forest classification
* Modular and scalable codebase
* End-to-end logging and monitoring

---

## Pipeline Workflow

```text
Data Ingestion
      ↓
Data Preprocessing
      ↓
Feature Engineering
      ↓
Model Training
      ↓
Model Evaluation
      ↓
DVCLive Experiment Tracking
      ↓
AWS S3 Artifact Versioning
```

---

## Project Structure

```text
.
├── data/
│   ├── raw/
│   ├── interim/
│   └── processed/
├── models/
├── reports/
├── logs/
├── src/
│   ├── data_ingestion.py
│   ├── data_preprocessing.py
│   ├── feature_engineering.py
│   ├── model_building.py
│   └── model_evaluation.py
├── params.yaml
├── dvc.yaml
├── dvc.lock
└── README.md
```

---

## Tech Stack

* Python
* Pandas
* Scikit-Learn
* NLTK
* DVC
* DVCLive
* AWS S3
* YAML
* Git & GitHub

---

## Model Performance

| Metric    | Score  |
| --------- | ------ |
| Accuracy  | 94.10% |
| Precision | 86.40% |
| Recall    | 69.23% |
| ROC-AUC   | 91.43% |

---

## Future Improvements

* Hyperparameter tuning
* Model deployment with FastAPI
* CI/CD automation using GitHub Actions
* Advanced transformer-based models (BERT)
