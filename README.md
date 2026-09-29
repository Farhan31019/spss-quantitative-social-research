# Applied Multivariate & Categorical Statistical Analysis (IBM SPSS)

A comprehensive empirical quantitative analysis evaluating continuous and categorical social science metrics using IBM SPSS. All analytical workflows, hypothesis tests, diagnostic assumption checks, and interpretations adhere strictly to APA guidelines.

---

## 📌 Project Overview
The research focuses on two independent datasets ($N = 200$ each) addressing academic performance drivers and organizational turnover dynamics:
1. **Academic Performance Analytics:** Evaluating the effects of attendance, weekly study hours, and stress levels on exam scores and scholarship awards.
2. **Employee Retention & Job Satisfaction:** Structural analysis of 12-item workplace satisfaction dimensions, salary distributions, and organizational turnover intention.

---

## 📊 Summary of Key Empirical Findings

| Analysis Type | Tested Variables | Key Test Statistic & $p$-Value | Substantive Conclusion |
| :--- | :--- | :--- | :--- |
| **Multiple Linear Regression** | Final Exam Score vs. Study Hours, Attendance, Stress | $R^2 = .243, F(3, 196) = 20.95, p < .001$ | Study hours ($\beta = .345$) and attendance positively drive scores; stress ($\beta = -.195$) significantly reduces performance. |
| **Salary Determinants** | Monthly Salary vs. Experience, Performance, Age | $R^2 = .652, F(3, 196) = 122.3, p < .001$ | Experience is the sole significant driver ($B = 2,048$ BDT/year, $p < .001$); performance rating is not significantly rewarded. |
| **One-Way ANOVA** | Final Exam Score by Department | $F(3, 196) = 8.85, p < .001, \eta^2 = .119$ | Engineering ($M = 71.22$) and Science ($M = 69.99$) significantly outperform Arts ($M = 61.11$, Tukey $p \le .001$). |
| **Repeated Measures ANOVA** | Quarterly Engagement (Q1 to Q4) | $F(1.92, 382.63) = 164.81, p < .001, \eta_p^2 = .453$ | Significant monotonic increase across all quarters (Q1 $54.40 \rightarrow$ Q4 $61.90$) with Greenhouse-Geisser correction. |
| **Factor Analysis (EFA)** | 12 Job Satisfaction Items (JS1–JS12) | $\text{KMO} = .828, \text{Bartlett's } p < .001$ | Extracted 3 clean components (62.9% variance explained): Work Environment, Compensation, and Career Growth. |
| **Scale Reliability** | Job Satisfaction Dimensions | Overall $\alpha = .813$ | Work Env ($\alpha = .900$), Compensation ($\alpha = .852$), Career Growth ($\alpha = .849$) confirm high internal consistency. |
| **Binary Logistic Regression** | Turnover Intention ($0 = \text{No}, 1 = \text{Yes}$) | Model $\chi^2(3) = 22.63, p < .001, \text{Nagelkerke } R^2 = .161$ | Job satisfaction is the sole significant mitigator ($\text{Exp}(B) = 0.261, p < .001$); reduces turnover odds by ~74%. |

---

## 🛠️ Statistical Techniques Covered
* **Parametric & Non-Parametric Group Comparisons:** Independent-samples $t$-test, One-Sample $t$-test, Mann-Whitney $U$, Paired $t$-test, Wilcoxon Signed-Rank, One-Way ANOVA, and Kruskal-Wallis $H$.
* **Psychometrics & Diagnostics:** Shapiro-Wilk normality testing, variance inflation factor (VIF) collinearity checks, Mauchly’s sphericity test, Varimax orthogonal rotation, and Cronbach's alpha.
* **Predictive Modeling:** Simple & Multiple OLS Regression, Binary Logistic Regression with Odds Ratios ($\text{Exp}(B)$).

---

## 📂 Repository Contents

### 📄 Research Reports (PDF & Word)
* `SPSS_Assignment1_Categorical_Results_APA.pdf`: Empirical report covering frequencies, chi-square cross-tabulations, non-parametric tests, and binary logistic regression.
* `SPSS_Assignment2_Continuous_Results_APA.pdf`: Empirical report covering descriptive statistics, t-tests, ANOVA, repeated measures, linear regression, and exploratory factor analysis (EFA).

### 💾 Datasets (.sav)
* `Student_Academic_Performance.sav`: Dataset 1 ($N = 200$) containing academic indicators (exam scores, study hours, attendance, stress, scholarships).
* `Employee_Job_Satisfaction.sav`: Dataset 2 ($N = 200$) containing organizational metrics (salary, tenure, performance, 12-item satisfaction scale, turnover intention).

### 📊 Raw Output Files (.spv)
* `Assignment1_Output.spv`: Raw SPSS output log and tables for categorical analyses.
* `Assignment2_Output.spv`: Raw SPSS output log and tables for continuous and multivariate models.

---

## 👤 Author
* **Md. Farhan**
* Department of Political Science, Jagannath University, Dhaka
* [LinkedIn Profile](https://www.linkedin.com/in/md-farhan-pol/)
