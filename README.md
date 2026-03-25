# Mental-Health-Crisis-Response-Optimizer

A complete machine learning system that predicts mental health crisis
severity, recommends the right emergency responder, predicts treatment
outcomes, and identifies underserved communities across the US.

---

## The Problem

The US dispatches police to 98% of mental health 911 calls even when a
clinician would be safer and more effective. This leads to escalation,
unnecessary arrests, and preventable deaths. Meanwhile, millions of
people with mental health conditions never seek treatment due to
workplace stigma and lack of awareness.

---

## What This Project Builds

| Model | Task | Dataset |
|-------|------|---------|
| Crisis Severity Classifier | Low / Medium / High severity | 911 Calls |
| Responder Recommender | Clinician / Police / Co-response | 911 Calls |
| Treatment Outcome Predictor | Improved / No Change / Deteriorated | Clinical data |
| Treatment-Seeking Predictor | Will / Won't seek treatment | OSMI Survey |

Plus a **ZIP code resource priority analysis** showing which communities
need the most mental health crisis resources.

---

## Datasets

| File | Source | Rows |
|------|--------|------|
| calls_911.csv | Emergency 911 Calls (Kaggle — mchirico) | 5,000 |
| survey.csv | Mental Health in Tech Survey (Kaggle — OSMI) | 1,259 |
| mental_health_diagnosis_treatment_.csv | Kaggle — uom190346a | 500 |

---

## Results

| Model | Accuracy | F1 Score |
|-------|----------|----------|
| Crisis Severity | 64.6%  Accuracy |
| Treatment Outcome | 33.0% Accuracy |
| Treatment Seeking | 81.3% Accuracy |



---

## How to Run
```bash
git clone https://github.com/YOUR_USERNAME/mental-health-crisis-optimizer
pip install pandas numpy matplotlib seaborn scikit-learn xgboost shap
jupyter notebook Mental_Health_Crisis_Optimizer.ipynb
```

---

## Real-World Impact

- The US spends $14 billion annually dispatching wrong responders
  to mental health emergencies
- This model gives dispatchers a data-driven recommendation in real time
- ZIP priority scores give city health departments a targeting tool
  for deploying clinician resources

---

## Author

**Esther Momeke** — Medical Laboratory Scientist | Data Scientist
[LinkedIn](http://linkedin.com/in/moemekeesther)
"""
