# MLflow Experiments

This project demonstrates how to manage machine learning experiments using **MLflow**. It includes tracking of metrics, parameters, artifacts, and model versions in a reproducible workflow. The goal is to showcase MLOps best practices by integrating model experimentation with versioning and model registry.

---

## 🚀 Features

- End-to-end machine learning pipeline for regression/classification tasks
- Automatic logging of:
  - Parameters
  - Metrics
  - Artifacts (plots, data files)
  - Trained models
- Integration with **MLflow Tracking** and **Model Registry**
- Version control for reproducible experiments
- Modular pipeline: Data preprocessing, model training, and evaluation

---

## 📁 Project Structure

mlflow_experiments/
│
├── data/                    # Sample data files
├── notebooks/               # Jupyter notebooks for EDA and MLflow demo
├── src/
│   ├── data_loader.py       # Data loading & preprocessing
│   ├── train.py             # ML model training and MLflow tracking
│   └── evaluate.py          # Model evaluation logic
├── mlruns/                  # MLflow experiment logs (auto-generated)
├── requirements.txt
└── README.md

---

## 📊 MLflow Tracking UI

Once you run the training script, launch MLflow UI to visualize experiments:

```bash
mlflow ui

By default, the UI is hosted at: http://localhost:5000

⸻

🧪 How to Run

1. Install dependencies

pip install -r requirements.txt

python src/train.py

. View experiment results in MLflow UI

⸻

✅ Tech Stack
	•	Python
	•	Scikit-learn
	•	Pandas, NumPy
	•	Matplotlib / Seaborn
	•	MLflow

⸻

📌 Highlights
	•	Demonstrates MLOps in action with minimal setup
	•	Supports multiple model versions and comparison
	•	Clean modular code for real-world extensibility

⸻

📬 Contact

Created by Subhash Govindharaj
📧 Email: subhashgovindharaj@gmail.com
