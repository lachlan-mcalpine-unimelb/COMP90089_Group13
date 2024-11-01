# Group 13 - Machine Learning for Health

## Repository Contents

This repository contains the following files:

- **Team Contract**: `Teamcontract(Group13).pdf`
- **Proposal**: `ML4Health_proposal_Group13.pdf`
- **Implementation Code**: `ML4Health_implementation_Group13.ipynb`

## Project Title

**Machine Learning Model-Based Early Detection of Acute Kidney Injury in Hypertensive Patients**

## Abstract

### Objectives
Acute kidney injury (AKI) is a prevalent and serious complication in hypertensive patients. Early detection and timely intervention may improve patient outcomes and reduce healthcare burdens. This study aims to develop and validate machine learning (ML) models for the early prediction of AKI in intensive care unit (ICU) patients with hypertension.

### Materials and Methods
Hypertensive patients were identified from the Medical Information Mart for Intensive Care (MIMIC-IV) database. Six machine learning models were developed using significant demographic and clinical information, with the optimal model selected based on the area under the receiver operating characteristic (AUROC) and calibration plot.

### Results
A total of 12,066 hypertensive patients were included in the study, with a median age of 67 years, and 5,251 (43.5%) patients diagnosed with AKI. A set of 24 clinical features was selected for model development. Both the eXtreme Gradient Boosting (XGBoost) and Logistic Regression (LR) models demonstrated strong predictive power, achieving AUROCs of 0.825 and 0.818, respectively. Additionally, the calibration plot revealed close alignment between predicted probabilities and observed outcomes.

### Conclusion
This study indicates that a machine learning-driven AKI prediction tool has acceptable performance for early AKI detection in hypertensive patients. However, a larger model that incorporates comprehensive features, multi-center collaboration, and clinical validation is necessary before wider societal implementation.

---

**Best regards,**  
_Group 13_
