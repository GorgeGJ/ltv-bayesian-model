# Bayesian LTV Modeling with PyMC

Welcome to the project demo for **Customer Lifetime Value (LTV) modeling using PyMC**.

---

## 🔍 Overview

This project implements a **Bayesian BG/NBD + Gamma-Gamma model** using PyMC to estimate customer lifetime value. It includes:

- BG/NBD modeling for purchase frequency
- Gamma-Gamma modeling for average order value
- LTV estimation per customer
- Optional segmentation by acquisition channel or geography
- Visual diagnostics of posterior distributions

---

## 📈 Business Use Cases

- 📊 Segment customers by expected LTV
- 💰 Inform paid marketing bid strategies
- 🔁 Forecast future repeat revenue
- 🌍 Compare customer behavior across regions
- 🎯 Personalize lifecycle and retention campaigns

---

## 🚀 Getting Started

1. Clone or download this repo  
2. Install required packages:

```bash
pip install pymc pymc-marketing arviz pandas matplotlib seaborn
```

3. Launch the notebook:

```bash
jupyter notebook LTV_PYMC_Demo.ipynb
```

---

## 📂 Files

- `LTV_PYMC_Demo.ipynb`: Full modeling walkthrough
- `README.md`: Project overview
- `index.md`: This GitHub Pages content

---

## 🔗 Resources

- [PyMC](https://www.pymc.io/)
- [PyMC-Marketing](https://github.com/pymc-labs/pymc-marketing)
- [ArviZ](https://www.arviz.org/)

---

Built with ❤️ using Bayesian methods to bring clarity to customer behavior.
