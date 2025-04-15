# 📊 Bayesian Customer Lifetime Value Modeling with PyMC

This project demonstrates how to estimate Customer Lifetime Value (LTV) using a **Bayesian BG/NBD + Gamma-Gamma model** implemented in PyMC. The notebook includes:

- ✅ Flat Bayesian BG/NBD modeling (no hierarchy)
- 💰 Gamma-Gamma modeling for average order value
- 📈 LTV estimation for individual customers
- 🌍 Optional segmentation by channel or geography
- 📊 Posterior diagnostics and LTV visualizations

## 📂 Data
- The project uses simulated sample data for function testing purpose.

## 📂 Files
- `LTV_PYMC_Demo.ipynb`: Full modeling notebook
- `README.md`: This file
- `requirements.txt`: Dependent Libraries

## 🧪 How to Run

```bash
pip install pymc pymc-marketing arviz pandas matplotlib seaborn
jupyter notebook LTV_PYMC_Demo.ipynb
```

## 📈 Use Cases

- Compute predicted LTV
- Segment customers by predicted LTV
- Optimize paid marketing bids
- Compare behavior across channels
- Evaluate campaign or channel performance using lifetime value

## 🧠 Built With

- [PyMC](https://www.pymc.io/)
- [ArviZ](https://www.arviz.org/)
- [pymc-marketing](https://github.com/pymc-labs/pymc-marketing)

---

Built with ❤️ by applying Bayesian modeling to real customer behavior.
