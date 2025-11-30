# MLflow Demo — 2025 ITU MLOps Course Presentation

This demo project is prepared for the 2025 MLOps classroom presentation at ITU.  
It demonstrates for tracking experiments, logging parameters/metrics, storing models, and comparing runs visually with a dashboard UI.

---

## 🎯 Presentation Goals

Show how to:

- Track ML experiment runs centrally
- Log hyperparameters (`log_param`)
- Log performance metrics (`log_metric`)
- Store models in a standard format (`sklearn.log_model`)
- Compare multiple runs via MLflow UI

---

## 🧪 Demo Details

- **Dataset**: Iris (classic ML benchmark)
- **Model**: Random Forest (**:contentReference[oaicite:2]{index=2}**)
- **ML training library**: **:contentReference[oaicite:3]{index=3}**
- **Visualization**: Metrics and artifacts shown on MLflow dashboard

---

## 📂 Project Structure

mlflow-demo/
├── README.md ← This file
├── demo.ipynb ← Training + MLflow logging notebook
└── mlruns/ ← Auto-generated logs and artifacts

---

## ⚙️ Local Setup (VS Code / Jupyter)

Make sure Python/conda is active in your terminal, then run:

```bash
pip install mlflow scikit-learn matplotlib
mlflow ui --host 127.0.0.1 --port 5000
```
http://127.0.0.1:5000


