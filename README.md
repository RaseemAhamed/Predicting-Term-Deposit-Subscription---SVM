# Predicting-Term-Deposit-Subscription---SVM

### Abstract
Marketing campaigns are characterized by focusing on the customer needs and their overall satisfaction. Nevertheless, there are different variables that determine whether a 
marketing campaign will be successful or not. There are certain variables that we need to take into consideration when making a marketing campaign.A Term deposit is a deposit that a bank or a financial institution offers with a fixed rate (often better than just opening a deposit account) in which your money will be returned back at a specific maturity time.

### Problem Statement:
Predict if a customer subscribes to a term deposits or not, when contacted by a marketing agent, by understanding the different features and performing predictive analytics

### Dataset Information:
The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to assess if the product (bank term deposit) would be ('yes') or not ('no') subscribed.The dataset consists of several predictor variables and one target variable, Outcome.Predictor variables includes the age, job, marital status, and so on

### Variable Description:
1.age- Age of the client
2.job- Type of job (categorical: 'admin.','blue-collar', 'entrepreneur', 
'housemaid', 'management', 'retired','self-employed', 'services', 
'student', 'technician', 'unemployed', 'unknown')
3.marital- Marital status (categorical: 
'divorced','married','single','unknown'; note: 'divorced' means 
divorced or widowed)
4.education- (categorical: 'basic.4y', 'basic.6y' ,'basic.9y', 'high.school', 
'illiterate', 'professional.course', 'university.degree','unknown')
5.default has credit in default? (categorical: 'no','yes','unknown')
6.housing has a housing loan? (categorical: 'no','yes','unknown')
7.loan has a personal loan? (categorical: 'no','yes','unknown')
8.contact contact communication type (categorical: 'cellular','telephone')
9.month last contact month of year (categorical: 'jan', 'feb', 'mar', ..., 
'nov', 'dec')
10.day_of_week last contact day of the week (categorical: 
'mon','tue','wed','thu','fri')
11.duration last contact duration, in seconds
12.campaign number of contacts performed during this campaign and for 
this client (numeric, includes last contact)
13.pdays number of days that passed by after the client was last 
contacted from a previous campaign (numeric; 999 means 
client was not previously contacted)
14.previous number of contacts performed before this campaign and for 
this client
15.poutcome outcome of the previous marketing campaign (categorical: 
'failure','nonexistent','success')
16.emp.var.rate employment variation rate - quarterly indicator (numeric)
17.cons.price.idx consumer price index - monthly indicator
18.cons.conf.idx consumer confidence index - monthly indicator
19.euribor3m euribor 3 month rate - daily indicator
20.nr.employed number of employees - quarterly indicator 
21.y has the client subscribed a term deposit? (binary: 'yes','no').

### Scope:
● Sentiment analysis in a variety of forms

● Data Pre-processing

● Training data using SVM

● Hyperparameter Tuning

### Conclusion:
By checking with Hyper Parameter Tuning the best kernel is Radial Basis Function with an accuracy of 0.9032532168001942 (90%)
