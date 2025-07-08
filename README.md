# 🌏 SDGs of Asia

### A Data-Driven Analysis of Sustainable Development in Asia using UN and UNICEF Data

---

## 📘 Project Overview

This project was developed as part of a collaborative academic effort under the guidance of the **United Nations (UN)** and **UNICEF**, using officially published data from both organizations. It explores the progress of Asian countries toward achieving the **Sustainable Development Goals (SDGs)** — a set of 17 interconnected goals designed by the UN to create a better, more sustainable future for all.

Through statistical analysis and visualizations, this project aims to understand Asia's current developmental trajectory and how well it is aligned with global SDG targets. The insights generated here are intended to support **policymakers, development researchers, and advocacy groups** in making data-informed decisions.

---

## 🎯 Objectives

The study investigates Asia's development through **three central research questions**:

1. **Clustering Development Levels**  
   Can Asian countries be meaningfully grouped based on their SDG scores? Do these clusters align with other indicators such as the Fragile States Index (FSI)?

2. **Income Disparity Analysis**  
   How does household income distribution in Asian countries compare to Western nations?

3. **Demographics & Health Dynamics**  
   Is there a correlation between **infant mortality rates** and **population growth** among Asian nations?

---

## 📊 Data Sources

All data used in this project was sourced from **reliable, non-profit, and authoritative sources**, including:

- **UN Sustainable Development Goals Index (2023)**  
  Measures each country's progress toward the 17 SDGs.

- **Fragile States Index (FSI) – The Fund for Peace (2023)**  
  Evaluates state vulnerability to collapse based on political, economic, and social indicators.

- **UNICEF – State of the World's Children Report (2023)**  
  Provides detailed statistics on child health, mortality, education, and household well-being globally.

---

## 🔍 Methodology

- **Clustering (K-Means)**  
  Countries were grouped based on SDG scores using K-means clustering. The elbow method was used to determine the optimal number of clusters.

- **Hypothesis Testing**  
  A two-sample hypothesis test with permutation simulations compared household income shares in Asia vs. the West.

- **Regression Analysis**  
  Separate regression models were fitted to explore the impact of infant mortality on population growth across differing mortality rate tiers.

---

## 📌 Key Findings

### ✅ Research Question 1
- Countries clustered into four development groups: *Poorly, Lower Middle, Upper Middle, and Highly Developed*.
- Strong alignment observed between FSI (stability) and SDG (development) scores.

### ✅ Research Question 2
- No statistically significant difference in household income distribution between Asia and Western countries (p-value > 0.05).
- Suggests economic parity in income share distribution, though limited by missing data.

### ✅ Research Question 3
- In high infant mortality countries, population growth is positively correlated.
- In low mortality countries, no strong correlation exists.
- Regression revealed two opposing trends that cancel out in the overall data.

---

## 📈 Visualizations

The project includes:
- Cluster-based histograms and scatter plots.
- Boxplots comparing income distribution.
- Regression lines split by infant mortality tiers.

These visuals aid in intuitive interpretation for policy and development planning.

---
