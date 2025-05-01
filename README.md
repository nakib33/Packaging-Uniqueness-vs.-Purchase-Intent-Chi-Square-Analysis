
# 🐶 Packaging Uniqueness vs. Purchase Intent: Chi-Square Analysis

## 📌 Project Overview
This project explores whether the perceived uniqueness of a new dog food packaging design influences customers' purchase intentions. By applying statistical analysis and data visualization techniques, we aim to uncover whether there's a significant relationship between packaging design and consumer behavior.

---

## 🧩 Problem Statement
A dog food company has released a new, visually appealing packaging design. While the marketing and design teams are confident about its uniqueness, the product manager is concerned that this design might not translate into increased sales and may instead introduce logistical challenges. 

Thus, the central question arises:
> **Does the uniqueness of the packaging significantly impact a customer’s likelihood to purchase the product?**

---

## 🎯 Objective
To determine if there's a statistically significant association between packaging uniqueness and purchase likelihood using the **Chi-Square Test of Independence**.

---

## 📂 Dataset Description
- **Source**: Company survey results (550 respondents)
- **Format**: Excel `.xlsx`
- **Key Columns**:
  - `Uniqueness`: Perceived uniqueness of the packaging (categorical, 5-point Likert scale)
  - `Purchase Likelihood`: Likelihood of purchase based on the packaging (categorical, 5-point Likert scale)

---

## ✨ Project Highlights
- 📊 Cleaned and explored 550 survey responses
- 📈 Visualized response distributions using:
  - Bar plots
  - Clustered bar charts
  - Annotated heatmaps
- 🧮 Built contingency tables and proportions tables
- 📐 Performed Chi-Square Test of Independence
- ✅ Interpreted the results with proper statistical rigor

---

## 💡 Why This Project?

### ✅ Benefits / Use Cases:
- Informs **data-driven design decisions** in marketing
- Provides insight into **customer perception vs. behavior**
- Can be generalized to any **A/B packaging testing**
- Helps align **design, marketing, and product strategy**

---

## 📊 Statistical Test Used
### 🔎 Chi-Square Test of Independence

- **Null Hypothesis (H₀)**: There is no association between packaging uniqueness and purchase likelihood.
- **Alternative Hypothesis (H₁)**: There is a significant association between packaging uniqueness and purchase likelihood.
- **Significance Level (α)**: 0.05

Our goal is to examine the claim that the uniqueness of the packaging affects the propensity of consumers to buy the product based on the packaging.Therefore, the null and alternative hypotheses can be formulated as follows:

- H0: Uniqueness is not associated with 'Purchase intent'
- H1: Uniqueness is associated with 'Purchase intent'
The significance level alpha is set to 0.05.

We can now run the test.

---

## ⚙️ How to Run
1. Open the project in [Google Colab](https://colab.research.google.com/)
2. Upload your Excel dataset when prompted.
3. Run all cells in order:
   - Data loading
   - EDA
   - Contingency table creation
   - Visualization
   - Statistical testing
4. Review the final statistical output and visualizations.

---

## 🔍 Key Findings

- **Chi-square Statistic**: 18.134
- **Degrees of Freedom**: 16
- **P-value**: **0.1641**

Since the p-value exceeds the α level of 0.05:

### ❌ **Fail to reject the null hypothesis**

There is **no statistically significant** relationship between packaging uniqueness and the likelihood of customers purchasing the product based on the current dataset.

---

## 📘 Final Word: Discussing the Output

Despite strong visual appeal and positive internal feedback about the packaging, the data does **not** support a significant influence on customer purchase behavior. The Chi-square test shows that observed variations in purchase intent across different uniqueness levels could be due to **random chance**.

---

## ✅ Conclusion

- The new packaging design, though perceived as unique, does **not have a statistically significant** effect on customers' intent to purchase.
- While design and aesthetics are important, they may not directly translate into sales performance.
- This reinforces the importance of testing customer-facing design changes with **empirical data** before rollout.
