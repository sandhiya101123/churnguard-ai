# CHURNGUARD AI

Customer Churn Prediction & Retention Intelligence System — MainCrafts Technology 2-Day Skill Certification.

## Contents
```
CHURNGUARD_AI/
├── README.md
├── MainCrafts_SkillSprint_ChurnGuardAI_Sandy.ipynb   # Executed source notebook (code + outputs)
├── CHURNGUARD_AI_Project_Report.pdf                   # Project report
├── Telco-Customer-Churn.csv                           # Dataset (IBM Telco Customer Churn)
├── churnguard_logistic_model.joblib                   # Saved trained model
└── images/                                             # Evidence screenshots
    ├── evidence_01_churn_distribution.png
    ├── evidence_02_churn_vs_contract.png
    ├── evidence_03_churn_vs_tenure.png
    ├── evidence_04_churn_vs_charges.png
    └── evidence_05_confusion_matrix.png
```

## How to run
1. Open `MainCrafts_SkillSprint_ChurnGuardAI_Sandy.ipynb` in Google Colab or Jupyter.
2. Upload `Telco-Customer-Churn.csv` to the same working directory (or Colab session).
3. Run all cells top to bottom.

## Summary
- **Dataset:** IBM Telco Customer Churn — 7,043 records, 21 features.
- **Models tested:** Logistic Regression, Random Forest (default), Random Forest (balanced/tuned).
- **Selected model:** Logistic Regression — Accuracy 0.804, Precision 0.653, Recall 0.559, F1 0.602.
- **Key findings:** month-to-month contracts, low tenure, and high monthly charges are the strongest churn signals.
