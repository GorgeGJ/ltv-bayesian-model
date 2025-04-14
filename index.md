# 📊 Bayesian Customer Lifetime Value (LTV) Modeling with PyMC

This project demonstrates how to build a **Bayesian hierarchical LTV model** using simulated e-commerce behavior and PyMC. It includes:

- 📦 **BG/NBD** for purchase frequency modeling
- 💰 **Gamma-Gamma** for average order value
- 📈 **Cohort decay analysis** by acquisition channel
- 🎯 Business application: understanding high-value segments for marketing optimization

## 🔍 Use Case

Each acquisition channel has different characteristics:
- Paid users churn faster but may spend more
- Organic users are retained longer
- Referral users lie in between

This notebook shows how to model LTV using these segments hierarchically.

## 🚀 Quick Start

```bash
pip install -r requirements.txt
jupyter notebook LTV_Hierarchical_Model.ipynb
```

## 📂 Files

- `LTV_Hierarchical_Model.ipynb`: full notebook
- `sample_transactions.csv`: simulated data
- `requirements.txt`: dependencies

## 🧠 Next Steps

- Swap in your real transaction data
- Extend with causal inference or ROI analysis
- Integrate predictions into paid media bidding

Built with ❤️ using PyMC.
