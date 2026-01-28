# A Clustering-Based Analysis of Synthetic Socioeconomic Profiles
**Author:** Rahma Atef Hamed (Individual Research)

## Research Summary
This study investigates latent socioeconomic structures using Unsupervised Learning. Instead of treating employment as a simple binary (Yes/No), this research identifies distinct financial profiles within populations.

##  Methodology
* **Dimensionality Reduction:** Applied **Principal Component Analysis (PCA)** to visualize high-dimensional financial data in a 2D space.
* **Unsupervised Learning:** Implemented **K-Means Clustering** to segment the population into three distinct clusters ($k=3$).
* **Insight:** Discovered that "Student" status is a diverse financial category that exists across both high and low-income clusters, challenging traditional binary employment assumptions.

##  Key Results
* Successfully identified a "High-Income Employed" cluster vs. a "Moderate-Income" cluster.
* Proved that financial well-being is more accurately represented through clustering demographics and debt-ratios rather than employment status alone.



# Personal-Finance-ML-Pipeline

# Personal Finance & Employment Predictive Pipeline
**Collaborative Team:** Rahma Hamed, Ali Alfadhli, Shahd Derbass

##  Project Overview
A comprehensive ML pipeline to predict employment status and income variation using synthetic financial datasets. 

##  My Individual Responsibilities (Rahma Hamed)
* **Lead for Preprocessing (P2):** Developed the data cleaning architecture, handled discretization of Age and Income, and implemented the encoding strategy for categorical features.
* **Regression Analysis (P3):** Built and tuned the **Linear Regression** model.
* **Achievement:** My regression model achieved an **R² of 0.77**, successfully explaining 77% of income variation based on savings and debt ratios.
* **Model Evaluation:** Conducted comparative testing between kNN, Naive Bayes, and Decision Trees, identifying Naive Bayes as the most robust classifier for this specific feature set.

##  Technical Takeaway
While Linear Regression showed high predictive power, my analysis of the residuals indicated non-linear relationships that suggest the need for more complex polynomial features in future iterations.
