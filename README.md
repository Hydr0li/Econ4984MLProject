# MachineLearningProject

For the project, I was planning to research what properties that affect the applicants to apply for the credit card, and I scraped datas of open sourced personal data including gender, whether own a car, whether own a house, number of children, income, education level, etc.. 

With Python, scraped data from Kaggle about the credit card applications data of What factors affect the application result, and do the data cleaning and visualization;
Designed an economic analysis machine learning algorithm for What factors affect application result, and used the collected data to train the algorithm and conducted the analysis.

## Description
Risk control method in the financial industry is a really important. We can use personal information and data from credit card applicants to predict the probability of future defaults and credit card borrowings. The bank is able to decide whether to issue a credit card to the applicant. Credit scores can objectively quantify the magnitude of risk.

Generally speaking, credit score cards are based on historical data. Once encountered huge economic fluctuations. Past models may lose their original predictive power. Logical model is a common method of credit scoring. Because Logistic is suitable for binary classification tasks and can calculate the coefficient of each feature. In order to facilitate understanding and operation, the scorecard will multiply the logistic regression coefficient by a certain value (such as 100) and round it up.

At present, with the development of machine learning algorithms. More predictive methods have been introduced in credit card scoring, such as Boosting, Random Forest and Support Vector Machines. However, these methods generally do not have good transparency. It may be difficult to provide customers and regulators with reasons for rejection or acceptance.

Building a machine learning model to predict whether an applicant is a "good" or "bad" customer, unlike other tasks, does not give a definition of "good" or "bad". You should use some techniques, such as year analysis, to construct labels. In addition, the problem of unbalanced data is also a big problem in this task
