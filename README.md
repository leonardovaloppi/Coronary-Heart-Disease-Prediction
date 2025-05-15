![CHD Banner](https://raw.githubusercontent.com/leonardovaloppi/Coronary-Heart-Disease-Prediction/refs/heads/main/CHD_banner.jpg)

# 10 Year Cardiovascular Disease Prediction 🩺 

A data analysis project focused on understanding and predicting the presence of cardiovascular disease using logistic regression and exploratory data techniques.

**Link to the project [here](https://colab.research.google.com/drive/1EuN6bUFna7S_y7RwJPIrtd5-aL0Jf3pB?usp=sharing)** 🔗

---

## Project Goal & Context 🎯 

The goal of this project is to explore and model health data to **predict the presence of cardiovascular disease** using a logistic regression model.  
The dataset comes from a health survey and includes various clinical and lifestyle-related features such as blood pressure, cholesterol, smoking status, age, and more.  

Given the **high imbalance** between people with and without the disease, a particular emphasis is placed on improving **recall**, making sure we identify as many affected individuals as possible.

---

## Methodology 🧪 

The approach follows a full data science pipeline:

→ **Data Cleaning**: handled missing values, encoded categorical variables, addressed skewed distributions and outliers.

→ **EDA**: visual exploration of distributions, class imbalance, correlation matrices, and comparison by disease status.

→ **Feature Engineering**: tried removing noisy features and tested combinations to improve model signal.

→ **Modeling**: used **Logistic Regression**, with and without calibration, tested different thresholds, evaluated performance on test and train sets.

→ **Evaluation**: analyzed performance via **confusion matrix, ROC/AUC, precision-recall, threshold plots**, and **cross-validation**.

---

## Summary of Results 📊 

- The logistic regression model achieved **ROC AUC around 0.70**, with recall ranging between **0.65 - 0.75**, depending on the selected threshold and feature set.
- Removing noisy or redundant features slightly improved generalization, but results are still constrained by **data imbalance** and **non-normal distributions**.
- The best results were obtained when optimizing for recall rather than accuracy or precision, which aligns well with the **clinical relevance** of avoiding false negatives.

---

## Tools & Technologies 🛠 

| Tool/Library           | Purpose                     |
|------------------------|-----------------------------|
| **Python 3.11**        | Core programming language   |
| **Pandas, NumPy**      | Data manipulation           |
| **Matplotlib, Seaborn**| Data visualization          |
| **Scikit-learn**       | Modeling and evaluation     |
| **Google Colab**       | Development environment     |

## Access & Usage Instructions 📂 

**Step-by-step guide to use the notebook on Colab:**

1. Access the project in Google Colab through [this link](https://colab.research.google.com/drive/1EuN6bUFna7S_y7RwJPIrtd5-aL0Jf3pB?usp=sharing)
3. Upload the dataset file `CHD_dataset.csv` to the **Files** panel on the left.
4. Run all the notebook cells of **SECTION B** and **C** (this activates all the custom functions).
5. Run all the other notebook cells in order.
6. To make changes, go to `File > Save a copy in Drive`.

---

## About Leonardo Valoppi 

- [LinkedIn](https://www.linkedin.com/in/leonardo-valoppi/)
- [GitHub](https://github.com/leonardovaloppi)
- [Tableau Public](https://public.tableau.com/app/profile/leonardo.valoppi/vizzes)
