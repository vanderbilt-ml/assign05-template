## CS5265 Foundations of Machine Learning

### Week 5 Assignment: Machine Learning Algorithms

**Deadline: Sunday 6/12 11:59PM (CDT)**


### I. Purpose:  

1. Apply the most widely-used ML algorithms to solve ML problems

2. Learn to improve model performance through tuning and optimization

### II. Grading and Submission 

1. The assignment will be evaluated in a total of 60 points

2. The assignment is in the form of a GitHub repository

3.  Work must be completed by the deadline stated above

### III. Tasks: 

#### Part 1 

Task 1 [20 points] Using the starter code and dataset (the data dictionary is also available) provided in this repo to predict whether an employee will leave their current position at the end of the time period or not (i.e., for your model, make sure to **set Leave as the True label**), implement the following models with a common pipeline and perform basic model tuning

- Logistic regression
- Random forest
- Gradient boosting model

Task 2 [10 points] Calculate the financial value of your models based on the following costs and benefits
- Again, Leave being the True class and Stay being False 
- Cost of replacing an employee is $120,000 (RC)
- Cost of intervention $2,000 used on each employee predicted to leave (IC) 
- Intervention success rate is 20% (SR)
	

| |Actual Leave|Actual Stay|
|---|---|---|
|Predicted Leave|TP|FP|
|Predicted Stay|FN|TN|

- Compare models on value, what is the best model according to your value metric?

#### Part 2

Fill in the name of your personal project here:

Complete the following issues created in your personal project repository:

[20 points] Explore 3 different models in your ML pipeline for your personal project

[10 points] Compare your models based on business value metrics or closest proxy

