# A Clustering-Based Analysis of Synthetic Socioeconomic Profiles


## 📄 Abstract
This research paper explores the latent socioeconomic structures within employment data using **Unsupervised Machine Learning**. Traditional economic analyses often treat "Employment Status" as a binary variable (Employed vs. Unemployed). This study challenges that view by identifying distinct financial "personas" that exist across these boundaries.

By applying **K-Means Clustering** and **Principal Component Analysis (PCA)** to a synthetic dataset, we identified three distinct socioeconomic clusters that reveal the financial diversity of students and the working class.



## 🧪 Methodology
The study follows a rigorous Data Science lifecycle:
1.  **Data Preprocessing:** Standardization of financial metrics (Income, Debt, Savings).
2.  **Dimensionality Reduction:** Utilized **PCA** to visualize high-dimensional financial attributes in 2D space.
3.  **Clustering Algorithm:** Implemented **K-Means** with an optimal $k=3$, determined via the Elbow Method.

## 📊 Key Findings
* **Cluster 0 (Moderate Income):** Represents the average working class with stable but limited financial growth.
* **Cluster 1 (High Income/Wealth Accumulators):** Characterized by high savings-to-debt ratios.
* **Cluster 2 (Low Income/High Risk):** Individuals with high debt vulnerability.
* **The "Student" Anomaly:** A critical finding of this paper is that "Students" do not fall into a single low-income cluster. Instead, they are distributed across all three clusters, suggesting that "Student" is a demographic status, not a financial one.

## 🛠️ Tools Used
* **Language:** Python
* **Libraries:** Scikit-learn (Clustering & PCA), Pandas, Matplotlib.
* **Typesetting:** IEEE Conference Format (LaTeX/Word).



# Personal Finance & Employment Predictive Pipeline
**Collaborative Team:** Rahma Hamed, Ali Alfadhli, Shahd Derbass

## 📌 Project Overview
A comprehensive Machine Learning pipeline designed to analyze synthetic financial data. Our team structured the project around the three core pillars of ML: **Classification** (predicting status), **Clustering** (finding patterns), and **Regression** (forecasting income).

## 🏆 My Individual Contributions (Rahma Hamed)
I served as the **Lead Data Architect** for the project (P2) and led the **Unsupervised Learning (Clustering)** module in P3.

## 🛠️ Technical Implementation

### 1. Preprocessing & Architecture (My Lead Role)
* **Data Cleaning:** Designed the cleaning strategy for the raw financial dataset, handling missing values and inconsistencies.
* **Feature Engineering:** Implemented **Discretization** for Age and Income, converting continuous variables into categorical bins to improve model stability.
* **Encoding:** Applied mapping strategies to convert text labels (e.g., "Unemployed", "Student") into machine-readable numeric formats.

### 2. Clustering Analysis (My Lead Role)
* **Goal:** To identify hidden socioeconomic profiles within the population without using pre-defined labels.
* **Algorithm:** Implemented **K-Means Clustering** ($k=3$).
* **Discovery:** My analysis revealed that "Employment Status" is not a binary financial indicator. 
    * *Cluster 0:* Moderate-Income / Mixed Employment.
    * *Cluster 1:* High-Income / High Savings (The "Wealth Accumulators").
    * *Cluster 2:* Low-Income / High Debt Risk.
* **Significance:** I expanded this specific clustering analysis into a formal **Technical Paper** (available in my research portfolio), proving that "Students" exist across diverse financial clusters rather than being a single low-income group.



### 3. Classification & Regression (Team Collaboration)
* **Classification:** The team compared kNN, Naive Bayes, and Decision Trees to predict employment status.
* **Regression:** We implemented Linear Regression to forecast income, achieving an **R² of 0.77**, though residual analysis suggested non-linear complexities.

## 📊 Project Outcome
This pipeline demonstrates the transition from raw data cleaning (P2) to advanced pattern recognition (P3), highlighting how unsupervised learning can reveal financial truths that supervised classification might miss.
