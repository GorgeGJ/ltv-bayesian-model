# ltv-Bayesian-model

# 📊 Bayesian Customer Lifetime Value (LTV) Modeling with PyMC

This project demonstrates how to build a **Bayesian hierarchical model** to estimate customer lifetime value (LTV) using **PyMC** and **PyMC-Marketing**. We combine probabilistic modeling with cohort segmentation to predict future customer behavior by acquisition channel.

## 💼 Business Context

Customer behavior varies across acquisition channels:

- **Paid** users may spend more but churn faster  
- **Organic** users tend to stay longer but spend less  
- **Referral** users typically fall in the middle  

Understanding these differences through **hierarchical modeling** allows marketing and analytics teams to optimize:

- 📈 Campaign strategy
- 📊 Budget allocation
- 🎯 Retargeting efficiency

---

## 📘 Features

- **Simulated transaction data** across 3 acquisition channels
- **Empirical cohort decay curves**
- **Hierarchical BG/NBD model** for customer repeat behavior
- **Gamma-Gamma model** for average order value
- **Custom priors** to reflect business knowledge
- **Posterior diagnostics** and uncertainty quantification using ArviZ

---

## 🧪 Requirements

```bash
pip install pymc pymc-marketing pandas matplotlib seaborn numpy arviz
```
---

## 📂Project Structure
```LTV_Hierarchical_Model.ipynb``` — Full modeling notebook

```sample_transactions.csv``` — Simulated e-commerce data

```requirements.txt``` — Python dependencies
