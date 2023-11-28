# Survival-Analysis-of-Heart-Failure-data
A report outlining the analysis of data taken on 299 individuals who have been diagnosed with systolic dysfunction of the left ventricle and have a history of heart failure. The event of death or censoring is recorded as 1 and 0 respectively. The time until event is recorded as well as a set of covariates. The source of the data and original paper are given by the following links.

https://plos.figshare.com/articles/dataset/Survival_analysis_of_heart_failure_patients_A_case_study/5227684/1
https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0181001

Kaplan-Meier estimates were used to estimate the survival function when grouped by binary variables. A Cox proportional hazards model was fit and analysed. It was discovered that the ejection.fraction variable did not satisfy the proportional hazards assumption. K-means clustering was used to categorise the ejection.fraction variable. A Cox model was then fit stratifying on these categories of ejection.fraction.
