# Yulu Shared Electric Cycles — Hypothesis Testing Case Study

**Domain:** Mobility / Shared Economy  
**Tools:** Python, Pandas, SciPy, Matplotlib, Seaborn  
**Focus:** EDA + Formal Hypothesis Testing

---

## 📌 Problem Statement

Yulu has observed a dip in revenue and wants to understand which factors significantly affect demand for its shared electric cycles in the Indian market, and how strongly those factors explain demand.

---

## 🎯 Analyses Performed

1. Exploratory Data Analysis
2. Relationship of count (total rentals) with workingday, season, weather
3. Formal Hypothesis Tests:
   - 2-sample t-test → Does working day affect rental count?
   - One-way ANOVA → Does season / weather affect rental count?
   - Chi-square test of independence → Is weather dependent on season?
4. Converted statistical findings into actionable business recommendations

---

## 🛠️ Tech Stack

- Python, Pandas, NumPy
- SciPy (ttest_ind, f_oneway, chi2_contingency)
- Matplotlib, Seaborn

---

## 💡 Key Findings

- Working day has a statistically significant effect on rental demand
- Season and weather both significantly influence the number of rentals
- Weather and season are not independent (Chi-square)

---

## 📓 Notebook & Full Report

- **Jupyter Notebook**: [./notebooks/](./notebooks/)
- **PDF Report**: [./reports/](./reports/)

---

## 🚀 Skills Demonstrated

- End-to-end statistical hypothesis testing workflow
- Choosing the correct test for the question
- Interpreting p-values in business context
- Translating statistical significance into operational actions

---

**Author:** Amit Narendra Adikane  
**GitHub:** [Amit14594](https://github.com/amitadikane)  
**LinkedIn:** [amit-adikane](https://www.linkedin.com/in/amit-adikane-4060a91b1/)
