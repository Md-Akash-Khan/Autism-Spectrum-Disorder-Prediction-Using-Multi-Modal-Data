# An ensemble framework for Autism Spectrum Disorder prediction using multi-modal data.

### 📌 Project Highlights
- **Project Type:** Machine Learning Lab Course Project  
- **Domain:** Healthcare, Autism Spectrum Disorder (ASD) Prediction  
- **Key Contribution:** Introduced a novel ensemble model **GENZ-Contrib** achieving **99% accuracy**  
- **Datasets:** Merged 3 publicly available ASD datasets (Children, Adolescents, Adults) into one unified dataset  
- **Platform:** Developed and executed in **Google Colab**  
- **Approach:** Comparative analysis of classical ML, deep learning, and ensemble methods  

---

## 📝 Project Description
This project presents a **machine learning framework for early Autism Spectrum Disorder (ASD) prediction** using behavioral and demographic data.  
We consolidated **three age-specific ASD datasets** (children, adolescents, adults) into a **single multi-modal dataset**, enabling comprehensive analysis across age groups—an approach **not previously explored** in earlier studies.  

Our novel **stacking ensemble model (GENZ-Contrib)** consistently outperformed traditional models such as Logistic Regression, SVM, KNN, Random Forest, XGBoost, and ANN, achieving **state-of-the-art accuracy (99%) and AUC (0.999)**.

---

## 🚀 Features
- ✅ **Unified dataset** spanning children, adolescents, and adults  
- ✅ **Leakage-free pipeline** with nested GroupKFold cross-validation  
- ✅ **Novel ensemble model (GENZ-Contrib)** giving the best performance  
- ✅ **Comparison across 7 models:**  
  - Logistic Regression (LR)  
  - Support Vector Machine (SVM)  
  - K-Nearest Neighbors (KNN)  
  - Random Forest (RF)  
  - XGBoost (XGB)  
  - Artificial Neural Networks (ANN)  
  - GENZ-Contrib (Stacking Ensemble)  

---

## 📊 Dataset
- **Source:** Three publicly available ASD screening datasets  
- **Size:** **1,100+ samples** across children, adolescents, and adults  
- **Features:**  
  - **AQ questionnaire scores (A1–A10)**  
  - **Demographic details** (age, gender, family history, etc.)  
- **Preprocessing Steps:**  
  - Missing value imputation  
  - One-hot encoding for categorical variables  
  - Min-Max scaling for numerical features  
  - Age binning for uniformity  

---

## 🧠 Models & Results
| Model              | Accuracy | Precision | Recall | F1-score | AUC  |
|---------------------|----------|-----------|--------|----------|------|
| **GENZ-Contrib**   | **0.990**| 0.973     | 0.995  | 0.984    | 0.999|
| Logistic Regression | 0.986    | 0.955     | 1.000  | 0.976    | 0.999|
| ANN                | 0.982    | 0.946     | 1.000  | 0.971    | 0.999|
| XGBoost            | 0.962    | 0.923     | 0.981  | 0.949    | 0.997|
| Random Forest      | 0.925    | 0.914     | 0.921  | 0.915    | 0.986|
| SVM                | 0.951    | 0.963     | 0.854  | 0.899    | 0.974|
| KNN                | 0.911    | 0.822     | 0.989  | 0.894    | 0.985|

➡️ **GENZ-Contrib achieved the best overall performance.**

---

## ⚙️ Tools & Platforms
- **Programming Language:** Python  
- **Frameworks & Libraries:** Scikit-learn, XGBoost, TensorFlow/Keras, Pandas, NumPy, Matplotlib, SHAP  
- **Development Environment:** Google Colab  

---

## 📌 Contributions
- 📂 **Dataset Innovation:** First to merge **child, adolescent, and adult ASD datasets** for unified analysis.  
- 🤖 **Model Innovation:** Introduced **GENZ-Contrib stacking ensemble**, outperforming existing methods.  
- 📈 **Evaluation Metrics:** Accuracy, Precision, Recall, F1, AUC, Confusion Matrices.  
- 🔍 **Explainability:** Feature importance & SHAP analysis identified **AQ scores and family history** as key predictors.  

---

## 🏗️ Repository Structure
      ├── ASDF.ipynb # Main Jupyter notebook (Google Colab code)
      ├── Datasets/ # ASD datasets (Children, Adolescents, Adults)
      ├── Project Paper/ # Research paper PDF
      └── README.md # Project documentation

---

## 📖 References
Full references and background studies are included in the attached project paper (see `Project Paper/`).

