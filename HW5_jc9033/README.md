Assignment 2

Work in group of 2 with Junjie Cai (jc9033)

The three tests we choose: t-Test, Correlation and Logistic Regression. 


| **Statistical Analyses**	|  **IV(s)**  |  **IV type(s)** |  **DV(s)**  |  **DV type(s)**  |  **Control Var** | **Control Var type**  | **Question to be answered** | **_H0_** | **alpha** | **link to paper**| 
|:----------:|:----------|:------------|:-------------|:-------------|:------------|:------------- |:------------------|:----:|:-------:|:-------|
T-test	| 1, Did rats early exposure to isoflurane? | categorical | 1, Amount of time the rats spend to complete task| Continuous | 1, age <br>2, gender <br>3, weaned_age <br>4, housing_lab <br>5, Lighting_hours <br>6, food_supply| 1, continuous  2, categorical  3, continuous  4, categorical  5, continuous  6, continuous | Do the amount of time the isoflurane group spend to complete task significantly higher than control group| Time test group <= Time control group | 0.001 | [Early Exposure to Volatile Anesthetics Impairs Long-Term Associative Learning and Recognition Memory](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0105340) |
Correlation	| 1, Riders' hand position | Categorical | 1, Horses' neck position| Categorical | 1, Riders' rein length<br> 2, Riders' heel height | 1, categorical 2, categorical |	Number of horses with high, round, or hollow neck position when riders spent more time with low hands positions is significantly higher than the control group | Number of horses of test group <= Number of control group | 0.01 | [Human Direct Actions May Alter Animal Welfare, a Study on Horses (Equus caballus)](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0010257) |
Logistic Regression | 1, Waist-to-height ratio | Continuous | 1, Morbidity of hypertension | Continuous | N/A | N/A | Do the hypertension morbidity of people who has higher waist-to-height ratio(WHtR) significantly higher than the hypertension morbidity of people who has lower waist-to-height ratio(WHtR) | (Morbidity of WHtR≥0.5) <= (Morbidity WHtR <0.5) | 0.05 | [Waist-to-Height Ratio and Cardiovascular Risk Factors among Chinese Adults in Beijing](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0069298) |
  |||||||||
  
![main plot](journal.pone.0010257.g002.png)
Figure 2
FCA results based on horses' and riders' postures at work.
Riders' hands: high HHa, middle MHa, low LHa; Riders' heels: high HHe, middle MHe, low LHe; Reins length: short SR, medium MR, long LR, Horses' neck: high HN, horizontal HN, low LN, hollow HoN, flat FN, round RN.

![main plot](WHtR.png)
Figure 3
ROC curves of the anthropometric indices for hypertension, diabetes, and dyslipidemia in men and women 
