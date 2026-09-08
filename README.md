# Predicting Hospital Readmission — with a Focus on Evaluation

An end-to-end machine learning project using the public
[Diabetes 130-US Hospitals dataset](https://archive.ics.uci.edu/dataset/296/diabetes+130-us+hospitals+for+years+1999-2008)
(~100K de-identified hospital encounters) to predict 30-day readmission.

The goal isn't just to train a model — it's to evaluate one the way a health system should before trusting it: discrimination (AUROC), calibration, subgroup performance across age, sex, and race, and fairness metrics. Model building is becoming easy; knowing whether a model is safe and useful is the actual work. This project practices that.

**Status:** In progress — started September 2026.

**Planned stack:** Python, pandas, scikit-learn, XGBoost, Fairlearn, matplotlib.

---
NEXT: download the dataset, load it into a first notebook, and look at what's in it.
