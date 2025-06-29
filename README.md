# 🧠 AI-based Autism Screening using Machine Learning (XGBoost + SHAP)

This project presents a machine learning-based autism screening tool designed to assist in the early indication of Autism Spectrum Disorder (ASD) risk using publicly available datasets, the AQ-10 questionnaire, and an explainable AI interface powered by SHAP.

> ⚠️ **Disclaimer:**  
> This tool is intended for educational and research purposes only. It is **not a diagnostic tool** and should **not** be used as a substitute for professional medical evaluation or diagnosis.

## 📁 Contents

| File/Folder            | Description |
|------------------------|-------------|
| `AI Powered Autism Prediction.ipynb` | Main Colab notebook |
| `Datasets/`            | Merged and cleaned CSV files used for training |
| `shap_result.html`     | Interactive SHAP explanation plot |
| `xgb_model.pkl`        | Trained XGBoost model |
| `Working Video .mp4`    | Video demonstration of the system |
| `questionnaire.py`     | Script used to serve AQ-10 questionnaire |
| `shap_result.txt`      | Text output of SHAP summary |
| `questionnaire.txt`    | AQ-10 questionnaire in plain text |

---

## 📊 Dataset & Feature Selection

- Merged multiple ASD-related public datasets
- Removed invalid/missing values
- Selected 15 most informative features using **Entropy & Information Gain**

---

## 🤖 ML Models Evaluated

| Model               | Accuracy | Precision | Recall |
|--------------------|----------|-----------|--------|
| XGBoost (✅ Best)   | 89.69%   | 77.38%    | 85.53% |
| Random Forest       | 89.35%   | 77.11%    | 84.21% |
| Logistic Regression | 88.32%   | 76.25%    | 80.26% |

---

## 📈 SHAP Explainability

- SHAP visualizations help explain why the model predicted ASD or not
- `shap_result.html` provides an interactive force plot

---

## 🌐 FastAPI Interface

- User form collects AQ-10 responses + personal data
- Backend predicts ASD risk using the trained model
- SHAP explanation shown after prediction

---

## 🎥 Demo

📽️ See `Working Video..mp4`  


---

## 📝 Paper Reference

This project is based on the research paper:
**“AI-based Autism Screening using Machine Learning and SHAP Explainability”**  
by *Areeha Zainab – AI Course Final Project*

---

## 👩‍💻 Author

**Areeha Zainab**  
AI Course – 2025  
GitHub: [@Areeeha](https://github.com/Areeeha)

---

## 🔑 Keywords

`Autism`, `ASD`, `Machine Learning`, `XGBoost`, `Explainable AI`, `SHAP`, `AQ-10`, `FastAPI`, `Healthcare AI`
