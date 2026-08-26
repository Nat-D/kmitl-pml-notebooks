# Colab notebooks — Probabilistic Machine Learning (KMITL)

Companion notebooks for the **Probabilistic Machine Learning** course. Pure
`numpy` + `matplotlib` (no GPU) — run each cell top to bottom in Colab.

| Notebook | Lecture | What you build |
|---|---|---|
| [`pml-l8-basis-functions`](https://colab.research.google.com/github/Nat-D/kmitl-pml-notebooks/blob/main/pml-l8-basis-functions.ipynb) | L8 — Applications of Bayesian linear regression | raw dataset → design matrix Φ via basis functions → solve with matrix libs (least squares, ridge = a Gaussian prior, full Bayesian posterior with predictive uncertainty, online updates) |
| [`pml-l8-real-data-uncertainty`](https://colab.research.google.com/github/Nat-D/kmitl-pml-notebooks/blob/main/pml-l8-real-data-uncertainty.ipynb) | L8 — Applications (real data) | Bayesian regression on a **real** medical dataset (`diabetes`), and how to **use** the uncertainty: calibrated per-prediction intervals, coefficient error bars, flagging extrapolation, and deferring uncertain cases |

Open in Colab from the links above (or **File → Open notebook → GitHub**). No `pip install` needed.
