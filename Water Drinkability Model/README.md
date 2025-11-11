# 💧 Water Drinkability Model

This repository contains a Jupyter notebook and dataset for exploring a **simple water drinkability (potability) prediction model** using basic ML techniques.

---

## 📁 Files in this Repository

* **`Copy_of_water_drinkability.ipynb`** — Jupyter notebook with EDA, preprocessing, model training & evaluation
* **`water_drinkability.csv`** — Dataset of water quality measurements used in the notebook

---

## ⚡ Quick Summary

This project demonstrates:

* 🔍 **Loading & inspecting the data**
* 📊 **Exploratory Data Analysis (EDA)** — plots, correlations, distributions
* 🧹 **Basic preprocessing** — missing values, scaling, encoding
* 🤖 **Training a classification model** to predict potability
* 📈 **Evaluation** — accuracy, precision, recall, confusion matrix, ROC AUC
* 💾 *(Optional)* saving the trained model

---

## 🧪 Dataset Assumptions

The project assumes the dataset includes physicochemical features such as:

* `ph`
* `Hardness`
* `Solids`
* `Chloramines`
* `Sulfate`
* `Conductivity`
* `Organic_carbon`
* `Trihalomethanes`
* `Turbidity`
* **`Potability`** (target: `1 = safe`, `0 = unsafe`)

🎯 If your CSV uses different column names, update the notebook accordingly.

---

# 🚀 Getting Started (Local Setup)

## 1️⃣ Install Python 3.8+ (3.10/3.11 recommended)

## 2️⃣ Create & activate virtual environment (Windows PowerShell)

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

## 3️⃣ Install Required Packages

Recommended libraries:

* pandas
* numpy
* scikit-learn
* matplotlib
* seaborn
* jupyterlab / jupyter

Install quickly:

```powershell
pip install pandas numpy scikit-learn matplotlib seaborn jupyterlab
```

---

# 📓 Open & Run the Notebook

Start Jupyter:

```powershell
jupyter lab
# or
jupyter notebook
```

Then open **`Copy_of_water_drinkability.ipynb`** and run cells step by step.

---

# 📈 What You’ll See

* 🧾 **Data summary tables**
* 📊 **Visualizations for each feature**
* 🧹 **Preprocessing pipeline**
* 🤖 **Baseline classifier (LR/RF/etc.)**
* 🧮 **Performance metrics:** accuracy, recall, precision, F1
* 🧩 **Confusion matrix**

---
