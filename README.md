# 🚀 Intelligent Predictive Maintenance & Machine Failure Risk Management

> A Machine Learning and Deep Learning solution for predicting machine failures and prioritizing maintenance actions using the AI4I 2020 Predictive Maintenance Dataset.

---

## 📌 Project Overview

This project develops a predictive maintenance system that identifies machines at risk of failure using operational sensor measurements.

The solution combines:

- Data Auditing & Exploratory Analysis
- Machine Learning Models
- Artificial Neural Networks (ANN)
- Threshold Optimization
- Business Cost Analysis
- Failure Risk Categorization

### 🎯 Project Goal

Predict machine failures before they occur and support maintenance teams with data-driven risk prioritization.

---

## 📊 Dataset Summary

**Dataset:** AI4I 2020 Predictive Maintenance Dataset

| Metric | Value |
|----------|----------|
| Records | 10,000 |
| Features | 14 |
| Target | Machine Failure |
| Failure Records | 339 (3.39%) |
| Non-Failure Records | 9,661 (96.61%) |

---

## 🎯 Project Objectives

- ✅ Perform Data Auditing & EDA
- ✅ Build Machine Learning Models
- ✅ Handle Class Imbalance
- ✅ Optimize Classification Thresholds
- ✅ Conduct Controlled ANN Experiments
- ✅ Estimate Business Impact
- ✅ Classify Machine Failure Risk
- ✅ Support Maintenance Decision Making

---

## 🛠 Technologies Used

| Category | Tools |
|-----------|-----------|
| Programming | Python |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Deep Learning | TensorFlow, Keras |
| Development | Jupyter Notebook |

---

## 🔄 Project Workflow

### Phase 1: Business Understanding & Data Preparation
- Data Audit
- Data Cleaning
- Class Distribution Analysis
- Outlier Detection
- Correlation Analysis
- Feature Selection

### Phase 2: Model Development
Models Developed:

1. Logistic Regression
2. Random Forest
3. Artificial Neural Network (ANN)

### Phase 3: Model Evaluation
- Performance Comparison
- Threshold Optimization
- Business Cost Analysis

### Phase 4: Research Experiment
- Learning Rate Comparison
- Repeated ANN Runs
- Performance Stability Analysis

### Phase 5: Business Interpretation
- Risk Classification
- Maintenance Recommendations
- Final Test Evaluation

---

## 🏆 Model Comparison

| Metric | Logistic Regression | Random Forest | ANN |
|----------|----------:|----------:|----------:|
| Accuracy | 83.47% | 97.80% | 95.73% |
| Precision | 13.65% | 82.14% | 43.30% |
| Recall | 72.55% | 45.10% | **82.35%** |
| ROC-AUC | 87.50% | 96.92% | 96.83% |
| PR-AUC | 38.29% | 66.88% | **73.84%** |

✅ **Selected Model: Artificial Neural Network (ANN)**

---

## 🧠 Final ANN Configuration

| Parameter | Value |
|------------|---------|
| Hidden Layers | 64, 32 |
| Activation | ReLU |
| Output Activation | Sigmoid |
| Optimizer | Adam |
| Learning Rate | 0.001 |
| Threshold | 0.70 |
| Best Epoch | 30 |

---

## 📈 Final Test Results

| Metric | Result |
|----------|----------:|
| Accuracy | 95.73% |
| Precision | 43.01% |
| Recall | 78.43% |
| F1-Score | 55.56% |
| ROC-AUC | 97.68% |
| PR-AUC | 71.86% |

### Test Confusion Matrix

| Actual / Predicted | No Failure | Failure |
|----------|----------:|----------:|
| No Failure | 1396 | 53 |
| Failure | 11 | 40 |

✅ Correctly identified **40 of 51 machine failures**

---

## 🚨 Risk Categories

| Risk Level | Score Range | Action |
|-------------|-------------|-------------|
| 🟢 Low | < 0.30 | Routine Monitoring |
| 🟡 Medium | 0.30 - 0.70 | Increased Monitoring |
| 🔴 High | ≥ 0.70 | Priority Inspection |

---

## 💰 Business Cost Analysis

Assumed Costs:

- False Positive = ₹2,000
- False Negative = ₹25,000

Estimated ANN Test Cost:

### ₹3,81,000

> These costs are illustrative and do not represent actual maintenance expenses.

---

## 📂 Project Structure

```text
Intelligent-Predictive-Maintenance/
│
├── Predictive_Maintenance.ipynb
├── AI4I_2020_Predictive_Maintenance_Dataset.csv
├── model_comparison.csv
├── experiment_results.csv
├── README.md
├── requirements.txt
└── Predictive_Maintenance_Report.pdf
```

---

## ⚠️ Limitations

- Synthetic dataset
- Highly imbalanced target class
- Hypothetical maintenance costs
- No real-time sensor integration
- Performance may differ in production environments

---

## ✅ Conclusion

The Artificial Neural Network (ANN) achieved the strongest balance between failure detection performance and business cost.

With a threshold of **0.70**, the model successfully prioritizes high-risk machines while reducing unnecessary inspections, making it suitable as a predictive maintenance decision-support tool.

Future work should include real industrial data, live sensor integration, and continuous performance monitoring.

---

## 📌 Project Summary

**Project:** Intelligent Predictive Maintenance & Machine Failure Risk Management  
**Dataset:** AI4I 2020 Predictive Maintenance Dataset  
**Primary Model:** Artificial Neural Network (ANN)  
**Frameworks:** Scikit-learn, TensorFlow, Keras  
**Focus:** Predictive Maintenance & Failure Risk Management