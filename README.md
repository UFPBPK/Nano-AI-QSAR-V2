# Nano-AI-QSAR-V2

# MTL nano biodistribution
### Multi-task machine learning for estimating nanoparticle distribution to tumors and tissues in mice

**Last Updated:** November 10, 2026  

---
## 📘 Overview

- This repository provides parameter-based, feature-based, and instance-based MTL for predicting NP distribution in tumor and tissues in mice. The manuscript is entitled "Multi-task machine learning for estimating nanoparticle distribution to tumors and tissues in mice". The manuscript is under review.

---

## 📂 Repository Structure

### **Parameter-based MTL**
- Data_parameter_based.csv: Data with ready format for parameter-based MTL development 
- Parameter_based_MTL.ipynb: Code for developing parameter-based MTL, including KRR, SVR, RF, XGBoost, LGBM.
- Parameter_based_DNN.ipynb : Code for developing parameter-based DNN.
---
### **Instance-based MTL**
- Data_instance_based.csv: Data with ready format for instance-based MTL development.
- Instance_based_MTL.ipynb: Code for developing instance-based MTL，including KRR, SVR, RF, XGBoost, LGBM.

---
### **Feature-based MTL**
- Data_feature_based.csv: Data with ready format for feature-based MTL development
- Feature_based_MTL.ipynb: Code for developing feature-based MTL, including KRR, SVR, RF, XGBoost, LGBM, and the stacking model (Applicability domain and feature importance analysis)
---

## 🌟 Key Features

- **Robust stacking framework** integrating multiple ML algorithms selected from the best-performing MTL strategy.

- **Simultaneous predictions** of NPs' distribution to tumor and tissues.
