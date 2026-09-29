# Explainable Real-Time Phishing Detection Framework

### An Explainable AI/ML Approach for Phishing Detection and Threat Analysis

## 📌 Project Overview

This project presents an **AI/ML-based phishing detection framework** designed to identify and classify potentially malicious phishing URLs.

The framework explores multiple machine learning algorithms, including **Random Forest, XGBoost, Support Vector Machine (SVM), and Artificial Neural Network (ANN)**, for phishing URL classification.

To improve the interpretability of machine learning predictions, the framework incorporates **SHAP (SHapley Additive exPlanations)** to analyze the contribution of individual features to the final prediction.

The project also provides a web-based interface for phishing URL analysis and supports structured threat intelligence reporting.

> **Project Status:** ✅ Completed — Research Paper Under Preparation

---

## 🎯 Objectives

* Develop an AI/ML-based phishing URL detection system.
* Extract and analyze relevant URL and website characteristics.
* Compare multiple machine learning algorithms for phishing classification.
* Identify potentially malicious and legitimate URLs.
* Provide an interpretable prediction using Explainable AI.
* Analyze feature contributions using SHAP.
* Provide a user-friendly web interface for phishing analysis.
* Generate structured threat intelligence information for detected threats.

---

## 🧠 Proposed Framework

```text
User / URL Input
       ↓
URL Preprocessing
       ↓
Feature Extraction
       ↓
Feature Engineering
       ↓
Machine Learning Models
       ↓
┌─────────────────────────────┐
│ Random Forest               │
│ XGBoost                     │
│ Support Vector Machine      │
│ Artificial Neural Network   │
└─────────────────────────────┘
       ↓
Phishing / Legitimate Prediction
       ↓
SHAP-Based Explainability
       ↓
Feature Contribution Analysis
       ↓
Threat Analysis & Reporting
       ↓
Web-Based Result Interface
```

---

## 🔍 Key Features

### 1. Phishing URL Detection

The system analyzes URL-related characteristics and uses machine learning models to classify URLs as potentially **phishing or legitimate**.

### 2. Machine Learning Model Comparison

Multiple supervised learning algorithms are explored and evaluated:

* Random Forest
* XGBoost
* Support Vector Machine (SVM)
* Artificial Neural Network (ANN)

The models are evaluated using appropriate classification metrics to understand their detection performance.

### 3. Explainable AI

The framework integrates **SHAP (SHapley Additive exPlanations)** to improve the transparency of machine learning predictions.

SHAP analysis helps identify:

* Important features influencing predictions
* Features contributing toward phishing classification
* Features contributing toward legitimate classification
* Relative feature contributions to individual predictions

### 4. Web-Based Interface

A web-based interface allows users to provide a URL and obtain the corresponding phishing detection result.

The interface is designed to present the prediction in an understandable manner rather than exposing only the underlying machine learning output.

### 5. Threat Intelligence Reporting

The framework supports structured threat information generation for detected phishing threats, enabling the results to be represented in a format suitable for cybersecurity analysis and further investigation.

---

## 🧪 Machine Learning Models

### Random Forest

Random Forest is an ensemble learning algorithm that combines multiple decision trees to perform classification.

### XGBoost

XGBoost is a gradient boosting algorithm used to learn complex relationships within the extracted phishing-related features.

### Support Vector Machine

SVM is a supervised machine learning algorithm that identifies a decision boundary for separating different classes.

### Artificial Neural Network

ANN is used to model complex nonlinear relationships within the extracted feature space.

---

## 🔬 Explainable AI Using SHAP

**SHAP** is incorporated to provide an interpretable view of machine learning predictions.

Instead of only providing:

```text
Prediction → Phishing
```

the system can analyze the features that contributed to the prediction.

Conceptually:

```text
URL
 ↓
Feature Extraction
 ↓
ML Model
 ↓
Prediction
 ↓
SHAP Analysis
 ↓
Feature Contributions
 ↓
Explainable Result
```

This improves the transparency of the phishing detection process and supports further analysis of model behavior.

---

## 📊 Model Performance

The implemented models were evaluated using standard machine learning classification metrics.

The evaluation includes metrics such as:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC

The experimental results showed that **XGBoost achieved 96.8% accuracy and 0.984 ROC-AUC** in the evaluated setup.

Detailed experimental results and analysis are documented as part of the research work.

---

## 🛠️ Technologies Used

### Programming

* Python

### Machine Learning

* Scikit-learn
* Random Forest
* XGBoost
* Support Vector Machine
* Artificial Neural Network

### Explainable AI

* SHAP

### Web Application

* Python-based web framework
* HTML
* CSS
* Web-based prediction interface

### Cybersecurity

* Phishing Detection
* URL Analysis
* Threat Intelligence
* Security Classification

---

## 📁 Project Structure

```text
Explainable-Real-Time-Phishing-Detection/
│
├── README.md
├── data/
│
├── preprocessing/
│
├── models/
│
├── notebooks/
│
├── explainability/
│
├── web_app/
│
├── results/
│
├── screenshots/
│
└── requirements.txt
```

The repository structure may be updated as the implementation and publication work progresses.

---

## 🔄 System Workflow

```text
        URL Input
            ↓
     Data Preprocessing
            ↓
      Feature Extraction
            ↓
      Feature Engineering
            ↓
    ┌───────────────────┐
    │ Machine Learning  │
    │     Models        │
    └───────────────────┘
            ↓
    Phishing Classification
            ↓
       SHAP Analysis
            ↓
   Feature Contribution
            ↓
   Threat Intelligence
            ↓
      Final Result
```

---

## 🔬 Research Areas

This project combines the following research areas:

* Artificial Intelligence
* Machine Learning
* Explainable AI
* Cybersecurity
* Phishing Detection
* Threat Intelligence
* Feature Engineering
* Intelligent Security Systems
* Web Security

---

## 📈 Applications

The proposed framework can support applications such as:

* Phishing URL screening
* Cybersecurity analysis
* Security awareness systems
* Suspicious URL investigation
* Explainable threat detection
* Automated security analysis

---

## 🚧 Publication Status

The implementation of the project has been completed.

The current research work focuses on preparing and refining the **research paper for publication**, including:

* Experimental analysis
* Result interpretation
* Model comparison
* SHAP explainability analysis
* Research paper preparation
* Publication submission

---

## 👩‍💻 Author

**Karthiyayini S**

M.E. Computer Science and Engineering
Sri Ramakrishna Institute of Technology

### Connect With Me

* LinkedIn: https://www.linkedin.com/in/karthiyayini-s-021a27250
* GitHub: https://github.com/Karthiyayini-02

---

## 📌 Project Note

This repository presents an academic research project developed for phishing detection and explainable machine learning analysis.

The implementation and experimental results are part of ongoing research publication activities. The repository may be updated with additional documentation, visualizations, implementation details, and publication information.

