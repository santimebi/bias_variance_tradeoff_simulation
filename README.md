# Bias-Variance Trade-off in High Dimensions

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/santimebi/bias_variance_tradeoff_simulation/blob/main/Demo.ipynb)

Interactive simulation demonstrating how to diagnose **underfitting**, **overfitting**, and the optimal model complexity / training duration (**Early Stopping**) in multidimensional settings where 2D visualization is impossible.

---

## 🚀 Quick Start (Google Colab)

Click the badge above or use this direct link:
👉 **[Open Demo.ipynb in Google Colab](https://colab.research.google.com/github/santimebi/bias_variance_tradeoff_simulation/blob/main/Demo.ipynb)**

The notebook is fully self-contained and uses standard libraries (`numpy`, `matplotlib`, `scikit-learn`). No local datasets or manual setup are required.

---

## 📌 Demo Structure

1. **Part 1 (Theoretical Laboratory):** Synthetic simulated data ($N = 5,000, P = 60$) with known irreducible error $\sigma^2 = 9.0$.
2. **Part 2 (Real-World Application with Raw Data):** House prices (*California Housing*, $P = 44$), illustrating gradient noise caused by severe outliers.
3. **Part 3 (Outlier Treatment and Noise Dissipation):** Winsorization (1%–99%) and robust scaling to obtain a clean, stable learning curve.
