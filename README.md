\# 🏥 MaternaInsight — Maternal & Fetal Health Monitoring System

> **MaternaInsight is an end-to-end machine learning-based clinical decision support system for assessing maternal health risks and classifying fetal health conditions. Built with Python and Streamlit, the platform combines predictive analytics, explainable AI, and an interactive dashboard to support informed healthcare decision-making.**



---

## 🔗 Live Demo
https://maternova-maternal-new-beginnings-l45cbs7swct8rw4ktyk68c.streamlit.app/

---

## 📌 Overview

MaternaInsight is designed as a **research-oriented clinical decision support system** that assists healthcare professionals, nurses, and community health workers in evaluating maternal and fetal health conditions.

The system provides:

* **Maternal Health Risk Assessment** — Predicts pregnancy risk as **Low, Mid, or High** based on six key clinical parameters.
* **Fetal Health Classification** — Categorizes fetal health as **Normal, Suspect, or Pathological** using 21 Cardiotocography (CTG) measurements.
* **Explainable AI with SHAP** — Provides feature-level explanations to help users understand the factors influencing each prediction.
* **Performance & Clinical Dashboard** — Presents model performance metrics and relevant clinical reference information through an interactive interface.

---

## 🧠 Machine Learning Models

| Prediction Task                 | Model             | Accuracy | Macro F1-Score |
| ------------------------------- | ----------------- | -------- | -------------- |
| Maternal Health Risk Assessment | LightGBM + Optuna | 90.64%   | 91.04%         |
| Fetal Health Classification     | Stacking Ensemble | 94.13%   | 88.66%         |

---

## 🖼️ Application Screenshots

| Home Page                                                                                                                                                      | Maternal Risk Assessment                                                                                                                                                               | Fetal Health Classification                                                                                                                                                                |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| ![Home](https://github.com/Archana-SS/MaternaInsight---Maternal-Health-Risk-and-Fetal-Health-Monitoring-System/blob/main/MaternaInsightImages/Home%20Page.png) | ![Maternal](https://github.com/Archana-SS/MaternaInsight---Maternal-Health-Risk-and-Fetal-Health-Monitoring-System/blob/main/MaternaInsightImages/Maternal%20Health%20Risk%20Page.png) | ![Fetal](https://github.com/Archana-SS/MaternaInsight---Maternal-Health-Risk-and-Fetal-Health-Monitoring-System/blob/main/MaternaInsightImages/Fetal%20health%20classification%20page.png) |

---

## ⚙️ Technology Stack

* **Frontend & Visualization:** Streamlit, Plotly, streamlit-option-menu
* **Machine Learning:** LightGBM, XGBoost, Random Forest, and Stacking Ensemble
* **Explainable AI:** SHAP using TreeExplainer and KernelExplainer
* **Data Preprocessing:** Scikit-learn and SMOTETomek from imbalanced-learn
* **Hyperparameter Optimization:** Optuna with 100 optimization trials

---

## 📊 Datasets

| Dataset                      | Source                                                                                | Number of Records |
| ---------------------------- | ------------------------------------------------------------------------------------- | ----------------- |
| Maternal Health Risk Dataset | [UCI / Kaggle](https://www.kaggle.com/datasets/csafrit2/maternal-health-risk-data)    | 1,014             |
| Fetal Health CTG Dataset     | [UCI / Kaggle](https://www.kaggle.com/datasets/andrewmvd/fetal-health-classification) | 2,126             |

---

## 🚀 Run the Project Locally

```bash
git clone https://github.com/YOUR_USERNAME/maternainsight.git
cd maternainsight
pip install -r requirements.txt
streamlit run app.py
```

---

## ⚠️ Disclaimer

MaternaInsight is developed for **research and educational purposes** as a clinical decision support system. Its predictions are intended to support, not replace, professional medical judgment. All results should be interpreted and reviewed by qualified healthcare professionals.

This application has **not undergone clinical trial validation** and is **not approved for use as an independent diagnostic tool**.

---


