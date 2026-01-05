

## Overview
This project demonstrates a complete machine learning lifecycle for predicting financial risk (e.g., claim severity or credit default) using structured tabular data.

## Business Problem
Financial institutions need accurate and interpretable risk models to minimize losses and optimize decision-making. Manual rules are insufficient at scale.

## Solution
We built an end-to-end ML pipeline covering data ingestion, feature engineering, model training, evaluation, and deployment.

## Tech Stack
- Python, Pandas, NumPy
- Scikit-learn, XGBoost
- MLflow
- Docker

## Pipeline Flow
Raw Data → Feature Engineering → Model Training → Evaluation → Model Registry → Inference

## Key Features
- Robust feature engineering
- Reproducible experiments using MLflow
- Containerized inference pipeline
- Modular, production-style codebase

## How to Run
```bash
docker build -t risk-model .
docker run risk-model
