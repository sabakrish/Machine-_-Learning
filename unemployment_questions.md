# 📘 Final Group Assignment — Machine Learning  
## 🧠 Dataset: Canada Unemployment (1976–Present)

---

# 🎯 Objective

You are acting as a **Government Data Science Advisory Team**.

Your goal is to:

> Analyze unemployment trends, build predictive models, and provide data-driven policy recommendations.

---

# 👥 Group Requirement

- Groups of **3 students**
- Each member must contribute to:
  - Data analysis
  - Modeling
  - Interpretation

---

# 📦 Deliverables

## 1. Jupyter Notebook (.ipynb)

Must include:

- Clean, structured code
- Visualizations
- Model training + evaluation
- Predictions

---

## 2. Final Report (PDF or Word)

Must include:

- Answers to all questions
- Graphs + explanations
- Model comparisons
- Policy recommendations

---

# ⚠️ Critical Requirements

- Use **at least 2 models**
- Must include:
  - Regression
  - Classification
- Must use **time-based splitting**
- Must include **feature engineering**
- Must explain **every decision made**

---

# 🧠 SECTION 1 — DATA UNDERSTANDING

## Q1 — Dataset Breakdown
- List all columns
- Explain what each column represents
- Identify numerical, categorical, time-based features

## Q2 — Data Cleaning
- Convert REF_DATE to datetime
- Handle missing values
- Clean column names
Explain :  Why is proper time formatting critical in this dataset?

## Q3 — Concept Understanding
Explain relationships between:
- Employment vs Labour force vs Unemployment  
- Participation rate vs Employment rate  
- Unemployment rate vs actual numbers  

---

# 📊 SECTION 2 — EXPLORATORY DATA ANALYSIS

## Q4 — Time Trend Analysis
- Plot unemployment over time
- Identify peaks and drops
Explain : What real-world events might explain these changes?

## Q5 — Regional Analysis
- Compare unemployment rate across provinces

- Identify Explain why.
    - Which province has the highest unemployment?
    - Which province is most stable?

## Q6 — Age Group Analysis
- Identify most/least affected groups

## Q7 — Gender Analysis
- Compare unemployment trends by sex
Explain : Are there consistent differences? Why might they exist?

---

# 📈 SECTION 3 — REGRESSION

## Q8 — Feature Engineering

- Create at least 3 new features, such as:

  - Year
  - Month
  - Lag feature (previous unemployment rate)
  - Rolling average

Explain:

  - Why lag features are powerful in time-series prediction?

## Q9 — Train Models
- LinearRegression
- Tree-based model

## Q10 — Time-Based Split
Explain why random split is wrong

## Q11 — Evaluation
- MAE
- R²
Explain best model and why?

## Q12 — Forecasting
Predict next 6–12 months
Explain : How reliable are these predictions?

---

# 🧠 SECTION 4 — CLASSIFICATION

## Q13 — Create Target
Define High vs Low unemployment
```
Unemployment rate >= X → High (1)
else → Low (0)

```
  - Choose threshold
  - Justify your choice

## Q14 — Train Models
- LogisticRegression
- One additional model (Decision Tree / KNN)

## Q15 — Evaluation
- Accuracy
- Confusion Matrix
Explain : 
  - What type of errors are being made?
  - Which error is more serious?

## Q16 — Probability
Explain predict_proba()

- What does probability mean in a policy or economic context?

---

# 🧠 SECTION 5 — ADVANCED ANALYSIS

## Q17 — Correlation
What influences unemployment?

## Q18 — Feature Importance
Using a tree-based model:

  - Identify most important features
  - Explain their impact

---

# 💼 SECTION 6 — POLICY INSIGHTS

## Q19 — Key Findings
Summarize 
  - trends
  - High-risk 
  - groups

## Q20 — Recommendations
You are advising the government.

Recommend:

Youth employment strategies

Regional economic interventions

Labour force participation improvements

## Q21 — Risk Analysis

What happens if unemployment increases significantly?

Consider impact on:
  - Economy
  - Society
  - Government
---

# ⚖️ SECTION 7 — MODEL COMPARISON

## Q22 — Comparison Table

| Model | Type | Metric | Strength | Weakness |

## Q23 — Final Decision

If you had to deploy ONE model, which would you choose and why?
---


## Q24 — Seasonality
Does unemployment follow seasonal patterns?

## Q25 — Model Improvement

- Try improving model performance
- Explain what changed and why
---

# 🧠 FINAL REFLECTION

## Q26 — Learning Outcome
- What did this dataset teach you about real-world Machine Learning and economics?
---


