# 📘 Machine Learning Interview Prep Notebooks

This repository contains a structured set of Jupyter Notebooks designed to build **mathematical foundations** and **core ML understanding** step by step. Each notebook introduces concepts through theory, formulas, and hands-on Python code.

---

## ✅ Contents

### **NB-1: Math & Stats Fundamentals**
Covers the essential mathematical and statistical concepts behind ML:

- **Q1:** L1 vs L2 norms – definitions, differences, and geometric intuition  
- **Q2:** Dot product – similarity, projections, and angles between vectors  
- **Q3:** Variance & covariance – spread of data and relationships between variables  
- **Q4:** Bayes’ rule – updating beliefs with new evidence (spam filtering example)  
- **Q5:** Law of Large Numbers (LLN) & Central Limit Theorem (CLT) – why sampling and normal approximations work  
- **Q6:** Bias–variance tradeoff – decomposition of error, underfitting vs overfitting  

---

### **NB-2: Machine Learning Fundamentals**
Introduces and demonstrates core ML algorithms and evaluation methods:

- **Q1:** Supervised, Unsupervised, Reinforcement Learning – definitions & examples (k-NN, clustering demo)  
- **Q2:** Overfitting vs underfitting – polynomial regression visualization  
- **Q3:** Regression algorithms – Linear, Polynomial, Ridge (L2), Lasso (L1); coefficients and curves  
- **Q4:** Classification algorithms – k-NN, Decision Trees, Naive Bayes, SVM  
  - k-NN → queries & neighbors  
  - Decision Trees → boundaries + tree diagram + feature importances  
  - Naive Bayes → Gaussian likelihood contours (σ ellipses)  
  - SVM → hyperplanes, margins, support vectors  
- **Q5:** Cross-validation – k-fold, stratified, leave-one-out  
- **Q6:** Bias–variance in ML – training vs test error tradeoff  
- **Q7:** Confusion matrix & metrics – accuracy, precision, recall, F1  
  - Real-life scenarios where **precision** or **recall** matters  
  - Easy **memory trick** for formulas  
- **Q8:** ROC & AUC – with best (AUC ≈ 1.0), random (AUC ≈ 0.5), and worst (AUC < 0.5) examples  

---

## 🚀 Upcoming: **NB-3**
The third notebook will cover **advanced ML topics**, such as:
- Feature engineering & preprocessing  
- Ensemble methods (Bagging, Boosting, Random Forests)  
- Gradient descent & optimization basics  
- Introduction to neural networks  

---

## 💡 How to Use
1. Open notebooks in Jupyter or VS Code.  
2. Read the **theory sections** in Markdown.  
3. Run the **Python examples** to see concepts in action.  
4. Experiment: tweak parameters (e.g., `k` in k-NN, polynomial degree, regularization strength).  

---

## 📂 Repository Structure
```
├── 1_math_stats_fundamentals.ipynb   # NB-1: Math & Stats
├── 2_ml_fundamentals.ipynb           # NB-2: Core ML
├── 3_ml_advanced.ipynb (planned)     # NB-3: Advanced ML
└── README.md                         # Project overview
```

---

✨ With these notebooks, you’ll build a **solid foundation** for ML interviews — progressing from math to algorithms to evaluation.  
