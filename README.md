# 📊 Assessing the Reliability of Statistical Tests in Group Comparison

This project is an academic report developed as part of the "Case Studies I" course at TU Dortmund University during the winter term 2023/24. The study explores statistical methods for group comparison using Berlin Marathon data, focusing on average finish times across six female age groups.

## 📌 Project Objectives

- Compare mean finish times across age groups using ANOVA and t-tests.
- Evaluate statistical assumptions: normality, variance homogeneity, and independence.
- Apply post-hoc methods (Tukey’s HSD and Bonferroni correction) to control Family-Wise Error Rate (FWER).
- Analyze differences between pairwise testing methods and post-hoc adjustments.

## 🗃️ Dataset

The dataset includes 1000 records of female runners from the Berlin Marathon, with no missing values.

**Variables:**
- `agegroup`: Categorical (6 groups)
- `time`: Continuous (finish time in seconds)

## 📈 Methods Used

- **Statistical Tests:** One-Way ANOVA, Two-Sample t-Test
- **Normality Check:** Shapiro-Wilk Test, Q-Q Plot
- **Variance Homogeneity:** Levene’s Test
- **Post-Hoc Tests:** Tukey’s HSD, Bonferroni Correction
- **FWER Control** in multiple comparisons

## 🔍 Key Insights

- Finish times increase with age; age group 55 shows the highest average time.
- ANOVA confirmed significant differences in mean finish times across groups (p < 0.001).
- Post-hoc tests identified significant differences between several group pairs.
- Tukey and Bonferroni methods yielded consistent results, though Bonferroni was more conservative.

## 🛠️ Tools & Technologies

- Python 3.12.6
- Libraries: Pandas, Seaborn, Matplotlib, SciPy, Statsmodels
- IDE: VS Code

