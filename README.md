# MLflow Demo — 2025 ITU MLOps Course Presentation

This demo project is prepared for the 2025 MLOps classroom presentation at ITU.  
It demonstrates tracking experiment runs, logging parameters/metrics, storing models, and comparing runs visually using the MLflow UI — the core goal of this notebook.
---

## Presentation Goals

Show how to:

- Track ML experiment runs centrally

- Log hyperparameters using mlflow.log_params

- Log performance metrics using mlflow.log_metric

- Store sklearn model objects in a standard format via mlflow.sklearn.log_model

- Compare multiple runs via the

---

##  Demo Details

Dataset: Digits Dataset (harder classification than Iris)

Models logged:

- Logistic Regression

- Random Forest 

- KNN
---

## Project Structure
- README.md  ← this file
- mlflow_demo.ipynb ← notebook that showcasing different experiments on different models for class demo
- mlflow_quickstart.ipynb ← notebook that mlflow provides for quickstart
---

## Local Setup (VS Code / Jupyter)

Make sure Python/conda is active in your terminal, then run:

```bash
pip install mlflow scikit-learn matplotlib
mlflow ui --host 127.0.0.1 --port 5000
```
Then open in your browser
http://127.0.0.1:5000


