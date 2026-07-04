# 📊 A/B Testing: Landing Page Optimization

## 📌 Project Overview

This project analyzes an A/B experiment conducted on an ecommerce landing page to determine which version should be implemented based on statistical evidence.

The analysis evaluates whether the new landing page improves business performance by comparing:

* Average spending per converted user
* Conversion rate
* Traffic source effectiveness
* User type behavior

The goal is to transform statistical findings into actionable business recommendations.

---

## 🎯 Business Questions

The project answers the following questions:

* Does one landing page generate a higher average spending per converted user?
* Which landing page achieves a higher conversion rate?
* Is conversion associated with the traffic source?
* Does user type (new vs. returning) influence conversion?
* What recommendations can improve the marketing strategy?

---

## 🛠️ Technologies Used

* Python
* Pandas
* Matplotlib
* SciPy
* Statsmodels
* Jupyter Notebook

---

## 📂 Dataset

The dataset contains information from an A/B experiment where each row represents one user exposed to either landing page A or B.

Main variables include:

* Landing page version
* Traffic source
* User type
* Conversion outcome
* User spending

---

## 📈 Statistical Methods

The project includes:

* Exploratory Data Analysis (EDA)
* Data validation
* Levene's Test
* Welch's t-test
* Two-Proportion Z-Test
* Chi-Square Test of Independence
* Business-oriented visualizations

---

## 🔑 Key Findings

* Landing page **B** generated a significantly higher average spending among converted users.
* Landing page **B** also achieved a significantly higher conversion rate.
* Traffic source showed a statistically significant association with conversion.
* Email traffic produced the highest conversion rate.
* No statistically significant relationship was found between user type and conversion.

---

## 💼 Business Recommendations

* Implement landing page **B** as the default version.
* Increase investment in high-performing acquisition channels, particularly Email.
* Continue monitoring traffic source performance.
* User segmentation based solely on new vs. returning visitors is not supported by the current data.

---

## 📁 Repository Structure

```
├── README.md
├── A_B_Testing_Landing_Page.ipynb
└── landing_experiment.csv
```

Data Analytics Portfolio Project
