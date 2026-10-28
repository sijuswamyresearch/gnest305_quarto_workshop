# GNEST305: 2-Day Interactive Quarto Live Workshop
**Course:** Semester S3 B.Tech Artificial Intelligence — *Introduction to Artificial Intelligence and Data Science* (`GNEST305`)

This repository contains a complete **multi-page Quarto website** configured with **`quarto-live` (`pyodide`)** so third-semester B.Tech students can interactively run, modify, and experiment with Python code directly inside their web browser without any local Python setup required by participants.

## Project Structure

* `_quarto.yml` — Multi-page website navigation, sidebar configuration, and Pyodide package declarations (`numpy`, `pandas`, `matplotlib`, `scipy`, `scikit-learn`).
* `index.qmd` — Workshop Overview, 2-Day Schedule (9 hours total), CO-PO Mapping, Assessment Structure, and Live Environment Check.
* `module4-datascience.qmd` — **Day 1, Session 1 (Module 4):** The 6-Step Data Science Process, Big Data vs. Data Science, Data Cleansing, Standardization, and EDA on Iris + Motor Telemetry.
* `module2-linear-algebra.qmd` — **Day 1, Session 2 (Module 2):** Covariance Matrices, Spectral Decomposition ($\Sigma = Q\Lambda Q^T$), Singular Value Decomposition ($X = USV^T$), and PCA from scratch on Iris + 4D Sensor Compression.
* `module3-prob-stats.qmd` — **Day 2, Session 3 (Module 3):** Random Variables, Maximum Likelihood Estimation (MLE), Bayes' Theorem / Gaussian Naive Bayes, Pearson Correlation ($r$), and Ordinary Least Squares (OLS) Regression.
* `module1-ml-ann.qmd` — **Day 2, Session 4 (Module 1):** Supervised vs. Unsupervised Learning, K-Means Clustering, Logistic Regression, Perceptron, Universal Approximation Theorem, and Deep Multi-Layer Perceptrons (both Regression and Classification demos).
* `practice-predictive-maintenance.qmd` — **Capstone Engineering Lab:** End-to-end Predictive Maintenance pipeline integrating all 4 modules.
* `styles.css` — Custom callout and badge styling.

