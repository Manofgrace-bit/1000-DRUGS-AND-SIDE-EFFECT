
<img width="500" height="333" alt="image" src="https://github.com/user-attachments/assets/44b25cb2-8018-4d75-9caf-894bc6f0eb5e" />

# 1000-DRUGS-AND-SIDE-EFFECT

**INTRODUCTION**

This project analyzes a dataset of 1,000 pharmaceutical drugs to examine the relationships between drug types, dosage levels, treatment duration, patient improvement scores, and reported side effects. The objective is to generate data-driven insights that support better clinical decision-making,, improve patient outcomes, and highlight potential safety concerns associated with drug usage. Analytical techniques including descriptive statistics, pivot analysis and regression analysis were applied, with results visualized using Power BI dashboards for clarity and accessibility.
## RESEARCH-QUESTIONS
1. To what extent does treatment duration influence patient improvement scores?
2. How does drug dosage affect patient improvement across different medical conditions?
3. Does patient age influence improvement outcomes across different treatments?
4. Which combination of drug type and dosage yields the highest average improvement score?
## Methodology

The analysis followed these key steps:

1. **Data Cleaning and Preparation**

   * Standardizing drug names and categories
   * Ensuring numerical variables were correctly formatted

2. **Exploratory Data Analysis (EDA)**

   * Descriptive statistics
   * Frequency and distribution analysis
   * Initial visual exploration of key variables

3. **Statistical Analysis**

   * Regression analysis to assess relationships between dosage, treatment duration, and improvement scores
   * # Regression Analysis – Patient Improvement and Dosage
   * 
## Model Specification

A **simple linear regression model** was applied to test the relationship between dosage and patient improvement:

**Improvement Score = β₀ + β₁(Dosage) + ε**

Where:

* **Dependent Variable (Y):** Patient Improvement Score
* **Independent Variable (X):** Drug Dosage
* **β₀:** Intercept
* **β₁:** Effect of dosage on improvement score
* **ε:** Error term

---

## Regression Summary Statistics

* **Number of Observations:** 1,000
* **Multiple R:** ≈ 0.05
* **R-Squared:** ≈ 0.002–0.003
* **Adjusted R-Squared:** ≈ 0.001 or lower
* **Standard Error:** ≈ 1.42
* **Significance F (p-value):** > 0.05

---

## Interpretation of Results

* The **very low R-squared value** indicates that dosage explains **less than 1%** of the variation in patient improvement scores.
* The **non-significant p-value** shows that the relationship between dosage and improvement score is **not statistically significant**.
* This means that **changes in dosage alone do not reliably predict patient improvement**.

---
   * pivot analysis to compare patient outcomes across different drugs or categories

4. **Visualization and Reporting**

   * Power BI dashboards
   * Charts and tables to highlight key insights
   * Executive summaries for high-level interpretation
---

## Tools and Technologies

* **Microsoft Excel** – Data cleaning and preliminary analysis
* **Power BI** – Interactive dashboards and data visualization
* **Statistical Techniques** – Regression analysis, descriptive statistics

---

## Project Structure

```
├── Data/
│   └── Cleaned dataset (Excel)
├── Analysis/
│   └── Statistical outputs and summaries
├── Dashboards/
│   └── Power BI dashboard files
└── README.md
```
---

## Conclusion

This project provides a structured and visual approach to understanding drug behavior, side effects, and patient outcomes. By combining statistical analysis with interactive dashboards, it offers both technical depth and executive-level clarity, making it suitable for academic, analytical, and professional healthcare data analysis use cases.

---

## Author

**Abraham Abiodun Olaoluwa**

---
I am a data enthusiast passionate about transforming data into actionable insights. I enjoy uncovering patterns, building analytical solutions, and collaborating on impactful data-driven projects. Let's connect on via email abiodunabraham63@gmail.com, Linkedin www.linkedin.com/in/
abraham-abiodun-b8058819b

