![Azure ML Biomedical AI Workspace](https://github.com/Dr-Sushant/azure-ml-learning/assets/your_image_id)

# Azure ML Learning Environment 🚀  
**Biomedical Data Science × AI Engineering**

This repository documents my Microsoft Learn AI exercises and Biomedical AI prototypes conducted in Microsoft Azure Machine Learning Studio.

---

## 🧠 Overview
From *clinical decision-making* to *computational modeling*, this workspace bridges medicine and machine learning.

### Modules Covered
- Supervised Learning – Linear Models & Regression  
- Model Optimization with Custom Cost Functions  
- Model Evaluation (MAE, RMSE, R²)  
- Azure AutoML & Experiment Logging  
- Model Deployment via Azure Endpoints  

---

## ⚙️ Environment Setup
This repository uses a **custom Conda environment** (`aml_user_env`) created in Azure ML Studio.

```bash
conda create -n aml_user_env python=3.10 -y
conda activate aml_user_env
pip install -r requirements.txt
python -m ipykernel install --user --name aml_user_env --display-name "Python (aml_user_env)"

## 🧮 Core Stack

| Layer | Libraries |
|:--|:--|
| AI Core | scikit-learn · statsmodels · tensorflow · torch |
| Biomedical | pydicom · scikit-image · simpleitk |
| Visualization | matplotlib · seaborn · plotly |
| Quantum | qiskit · pennylane |
| Azure SDK | azure-ai-ml · azureml-core · mlflow |

🧩 Project Use Cases

Anesthesia Drift Detector (DriftGuard) – Safety analytics for peri-operative monitoring

HCC Extractor – ICD-10 driven disease classification engine

PinkScan AI – Breast-cancer risk prediction pipeline

🌐 Integrations

Azure ML Workspace for model tracking

GitHub Actions for reproducibility

Quantum ML modules for computational biophysics

Guiding Principle: Innovation in healthcare begins where clinicians and coders speak the same language.
