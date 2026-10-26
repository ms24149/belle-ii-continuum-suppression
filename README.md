# belle-ii-continuum-suppression
# Continuum Suppression in High Energy Physics (Belle II Data)

## 📌 Project Overview
This project focuses on binary classification to separate **Signal** events from **Continuum Background** noise using features from the Belle II detector dataset. The goal is to compare multiple machine learning classifiers, analyze feature importance, and perform feature reduction to optimize signal detection.

---

## 📊 Dataset & Exploratory Data Analysis (EDA)
- **Dataset:** Belle II Monte Carlo (MC) simulated dataset.
- **Data Storage:** Processed using CSV/SQLite format.
- **EDA Steps:**
  - Class balance distribution (Signal vs. Background).
  - Feature correlation matrices and heatmaps.
  - Distribution plots for key physics variables.

---

## ⚙️ Machine Learning Pipeline & Models
We trained and compared multiple models against a baseline approach:
1. **Baseline Model:** Simple cut / Majority-class baseline
2. **Logistic Regression**
3. **Random Forest Classifier**
4. **Gradient Boosting Classifier (or Decision Tree / SVM)**

### 🔍 Feature Reduction & Feature Importance
- Correlation analysis to drop redundant features.
- Evaluated feature importance metrics using tree-based models (PCA / Recursive Feature Elimination).

---

## 📈 Evaluation & Results
Models were evaluated using the following performance metrics:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**
- **ROC-AUC Score**

*Visualizations included:* Confusion Matrix and ROC Curve comparison plots.

---

## 📂 Project Structure
├── data/                  # Raw and processed datasets (or SQLite DB)
├── notebooks/             # Google Colab / Jupyter Notebooks with EDA & Models
├── visualisations/        # Saved plots (Confusion Matrix, ROC Curve)
└── README.md              # Project documentation

## 🚀 How to Run the Project
1. Clone the repository:
   https://github.com/ms24149/belle-ii-continuum-suppression.git
