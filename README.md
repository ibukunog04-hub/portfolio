# 📊 Comparative Analysis of Machine Learning Algorithms for Fraud Detection in Healthcare Insurance

> **Undergraduate Final Year Project**  
> Submitted to: Department of Computer Science, Redeemer's University, Ede, Osun State, Nigeria  
> Author: **OGUNBIYI, IBUKUNOLUWA TOYOSI**  
> Matric Number: RUN/CMP/20/9518  
> Year: July 2024

---

## 📌 Overview
Healthcare insurance fraud is a major global challenge, leading to massive financial losses and increased cost of care. This project applies and compares four machine learning algorithms to detect fraudulent claims in healthcare insurance, using real-world datasets. The aim is to identify the most accurate and reliable model for fraud detection in the Nigerian healthcare insurance context.

**Algorithms Compared:**
- Decision Tree Classifier
- Logistic Regression
- Random Forest Classifier
- AdaBoost Classifier

---

## 📝 Abstract
Healthcare fraud involves submitting false claims or misrepresenting facts to obtain unauthorized payments, wasting resources and raising costs. This study uses machine learning techniques to detect fraud in healthcare insurance. Models were trained and tested on datasets obtained from Kaggle, covering beneficiary information, inpatient, and outpatient records. Performance was evaluated using **Accuracy, Precision, Recall, and F1-Score**.

**Results:**
- ✅ Random Forest: **95.3% Accuracy** — *Best performing model*
- Decision Tree: 92% Accuracy
- AdaBoost: 91.13% Accuracy
- Logistic Regression: 83% Accuracy

The study shows that machine learning — especially Random Forest — is highly effective for detecting healthcare insurance fraud and can help reduce financial losses.

> **Keywords:** Insurance, Fraud Detection, Machine Learning, Healthcare Fraud, Classification Algorithms

---

## 🎯 Aim & Objectives

### Aim
To compare the performance of different machine learning algorithms and determine the best model for detecting fraud in healthcare insurance claims.

### Objectives
1. Obtain relevant healthcare insurance datasets
2. Preprocess and clean data for modelling
3. Train four supervised machine learning models
4. Evaluate models using standard performance metrics
5. Compare results and recommend the optimal algorithm

---

## 🛠️ Tech Stack & Tools

| Component | Details |
|---|---|
| **Language** | Python 3.x |
| **Libraries** | Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Imblearn (SMOTE) |
| **Environment** | Google Colab / Jupyter Notebook |
| **Dataset Source** | [Kaggle — Medical Insurance Fraud Dataset](https://www.kaggle.com/) |
| **Techniques** | Data Cleaning, Feature Engineering, SMOTE (for imbalance), Classification, Evaluation Metrics |

---

## 📂 Dataset
- Source: Kaggle Healthcare Insurance Claims Dataset
- Categories:
  - Beneficiary details
  - Inpatient records
  - Outpatient records
- Features: Demographics, procedure codes, diagnosis codes, billing amounts, provider details
- Target variable: `PotentialFraud` (Yes/No → encoded as 1/0)

---

## ⚙️ Methodology

1. **Data Collection & Integration**  
   Merged beneficiary, inpatient, and outpatient datasets into one unified file.

2. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical features
   - Removing duplicates and inconsistencies
   - Feature creation (e.g., length of stay, chronic conditions flag)

3. **Handling Class Imbalance**
   - Applied **SMOTE (Synthetic Minority Oversampling Technique)** to balance fraud vs non-fraud cases.

4. **Model Implementation**
   - Trained 4 supervised learning algorithms
   - Split data: 80% training, 20% testing

5. **Evaluation Metrics**
   - Accuracy
   - Precision
   - Recall
   - F1-Score
   - Confusion Matrix

---

## 📊 Results & Comparison

### 📈 Performance Summary
| Model | Accuracy | Precision | Recall | F1-Score |
|---|---|---|---|---|
| **Random Forest** | **95.3%** | **95.0%** | **95.31%** | **95.0%** |
| Decision Tree | 92.0% | 91.64% | 91.0% | 91.0% |
| AdaBoost | 91.13% | 91.0% | 91.0% | 91.12% |
| Logistic Regression | 83.0% | 82.74% | 82.80% | 82.74% |

✅ **Conclusion:**  
**Random Forest Classifier** outperforms all other models and is recommended for deployment in healthcare fraud detection systems.

---

## 📁 Project Structure
