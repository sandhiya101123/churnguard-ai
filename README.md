# CHURNGUARD AI

Customer Churn Prediction & Retention Intelligence System — MainCrafts Technology.

## Contents
```
CHURNGUARD_AI/
├── CHURNGUARD_AI_Project_Report.pdf
├── README.md
├── MainCrafts_ChurnGuardAI.ipynb   # Executed source notebook (code + outputs)
├── Telco-Customer-Churn.csv                           # Dataset (IBM Telco Customer Churn)
├── churnguard_logistic_model.joblib                   # Saved trained model

                                    # Evidence screenshots
    ├── evidence_01_churn_distribution.png
    ├── evidence_02_churn_vs_contract.png
    ├── evidence_03_churn_vs_tenure.png
    ├── evidence_04_churn_vs_charges.png
    └── evidence_05_confusion_matrix.png
```

## Summary
- **Dataset:** IBM Telco Customer Churn — 7,043 records, 21 features.
- **Models tested:** Logistic Regression, Random Forest (default), Random Forest (balanced/tuned).
- **Selected model:** Logistic Regression — Accuracy 0.804, Precision 0.653, Recall 0.559, F1 0.602.
- **Key findings:** month-to-month contracts, low tenure, and high monthly charges are the strongest churn signals.
