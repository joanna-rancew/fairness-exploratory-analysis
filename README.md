# Fairness analysis
Exploratory of the notion of fairness on the basis of the paper Verma, Sahil, and Julia Rubin. "Fairness definitions explained." Proceedings of the international workshop on software fairness. 2018.

**1.	Introduction**

The goal of the project was to delve into the subject of fairness and to compare different definitions of fairness on the basis of the paper Verma, Sahil, and Julia Rubin. "Fairness definitions explained." Proceedings of the international workshop on software fairness. 2018.

**2.	Dataset and technological stack**
Project was developed in Python, using libraries: seaborn, sklearn, pandas, numpy and matplotlib. The analyzed dataset "Student Performance Dataset” from kaggle.com consists of 33 features including gender, age, size of family and grades.

**3.	Project phases:**
-	Consultation of expectations and project requirements with Chiara Criscuolo and Tommaso Dolci
-	Review of the scientific articles and introduction to the notion of fairness in Data Science
-	Data exploration, data cleaning and feature engineering
-	Designing a fairness evaluation process
-	Designing and training model for classification task
-	Implementing a fairness evaluation process in the code
-	Self-review of the project and comparison of the results with assumptions from the paper
-	Error correction
-	Project review by Chiara Criscuolo and Tommaso Dolci
-	Implementing feedback
-	Summary and project presentation 
 
**4.	Classification task**
The classification task in the project included two separate binary classifications:
-	whether the student failed any exam or passed all of the exams
-	whether the student has high combined average or not
In the project “sex” and “address” were treated as protected features for fairness evaluation.

**5.	Results of the project**
During the project development, the following fairness definitions (metrics) were analyzed:
●	Group fairness
●	Conditional statistical parity
●	Predictive parity
●	False positive error rate balance (a.k.a. predictive equality)
●	False negative error rate balance (a.k.a. equal opportunity)
●	Equalized odds
●	Conditional use accuracy equality
●	Overall accuracy equality
●	Treatment equality
●	Causal discrimination
●	Fairness through unawareness
●	Fairness through awareness
●	Causal Reasoning 


