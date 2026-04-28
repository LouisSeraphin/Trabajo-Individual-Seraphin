Throughout the exploratory data analysis, several important patterns were identified regarding the factors associated with coronary heart disease (CHD).

First, the univariate analysis of numerical variables showed that most clinical variables were right-skewed, especially glucose, systolic blood pressure, total cholesterol, and cigarettes per day. This means that while most patients had moderate values, a smaller group presented very high levels, which may correspond to higher cardiovascular risk profiles. Boxplots also revealed several outliers, particularly for blood pressure, cholesterol, and glucose, which is common in medical datasets.

For low-cardinality numerical variables such as age and cigarettes per day, additional percentile analysis showed that smoking habits were highly concentrated around low values, with a smaller number of heavy smokers. Logarithmic transformation and winsorization helped reduce the effect of extreme values and improved the interpretation of the distributions.

The categorical variable analysis showed that most patients did not develop CHD within the next 10 years, which is expected since cardiovascular disease affects only part of the population. However, clear differences appeared when comparing categories.

Gender analysis showed that men had a higher prevalence of CHD than women. Age group analysis confirmed that CHD risk increases significantly with age, especially after 50 years old. This was one of the strongest patterns observed in the entire study.

Smoking group analysis also revealed a clear trend: non-smokers had the lowest CHD prevalence, while moderate and heavy smokers showed a much higher proportion of CHD cases. This strongly supports the hypothesis that smoking is a major cardiovascular risk factor.

Hypertension analysis showed one of the strongest relationships with the target variable. Patients diagnosed with hypertension (prevalentHyp = 1) had a much higher probability of developing CHD. The same pattern appeared when analyzing systolic blood pressure (sysBP), where CHD patients generally had higher blood pressure distributions.

Diabetes and glucose levels also showed a positive association with CHD. Patients with diabetes and elevated glucose levels were more represented among CHD cases, confirming that metabolic disorders increase cardiovascular risk.

Total cholesterol contributed to CHD risk as well, although the relationship was less pronounced than age or blood pressure. Higher cholesterol levels were more common among patients who developed CHD.

BMI showed a weaker effect than initially expected. Although overweight patients were present among CHD cases, BMI was not one of the strongest predictors compared to hypertension, age, or smoking.

The multivariate analysis reinforced these findings. The correlation heatmap showed that age, systolic blood pressure, glucose, and prevalent hypertension had the strongest positive relationships with TenYearCHD. Pairwise analysis also confirmed that patients with CHD tend to combine several risk factors at the same time rather than only one isolated factor.

The high-risk patient profile identified in the grouped analysis was typically an older male patient, smoker, with hypertension, higher glucose levels, and elevated cholesterol. This confirms that coronary heart disease is usually the result of multiple combined risk factors rather than a single variable.