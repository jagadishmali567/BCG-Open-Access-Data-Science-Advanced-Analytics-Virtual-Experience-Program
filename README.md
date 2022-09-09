# BCG Open-Access Data Science Advanced Analytics Virtual Experience Program

      Program has 4 modules
            
            1: Business Understanding & Hypothesis Framing
            2: Exploratory Data Analysis
            3: Feature Engineering & Modelling
            4: Findings & Recommendations

![one day bcg logo green ](https://user-images.githubusercontent.com/27211670/183700820-2248f4ee-655f-40dc-8628-8495072a3979.png)

## Task 1 - Business Understanding & Hypothesis Framing
Understanding the business context and problem statement.

#### The background information on this Task 1

PowerCo is a major gas and electricity utility that supplies to corporate, SME (Small & Medium Enterprise), and residential customers. The power-liberalization of the energy market in Europe has led to significant customer churn, especially in the SME segment. They have partnered with BCG to help diagnose the source of churning SME customers.

A fair hypothesis is that price changes affect customer churn. Therefore, it is helpful to know which customers are more (or less) likely to churn at their current price, for which a good predictive model could be useful.

Moreover, for those customers that are at risk of churning, a discount might incentivize them to stay with our client. The head of the SME division is considering a 20% discount that is considered large enough to dissuade almost anyone from churning (especially those for whom price is the primary concern).

The Associate Director (AD) held an initial team meeting to discuss various hypotheses, including churn due to price sensitivity. After discussion with your team, you have been asked to go deeper on the hypothesis that the churn is driven by the customers’ price sensitivities. 

Your AD wants an email with your thoughts on how the team should go about testing this hypothesis.

The client plans to use the predictive model on the 1st working day of every month to indicate to which customers the 20% discount should be offered.

##### Tasks to do
Your first task today is to understand what is going on with the client and to think about how you would approach this problem and test the specific hypothesis.

You must formulate the hypothesis as a data science problem and lay out the major steps needed to test this hypothesis. Communicate your thoughts and findings in an email to your AD, focusing on the data that you would need from the client and the analytical models you would use to test such a hypothesis.

##### How to solve this task:

♦ Remember what the key factors are for a customer deciding to stay with or switch providers

♦ Think of data sources and fields that could be used to explore the contribution of various factors to a customer’s possible action

♦ Ideally, what would a data frame of your choice look like – what should each column and row represent?

♦ What kind of exploratory analyses on the relevant fields can give more insights about the customer's churn behavior? 


## Task 2 - Exploratory Data Analysis
Understanding the business through data

#### The background information on this Task 2

The BCG project team thinks that building a churn model to understand whether price sensitivity is the largest driver of churn has potential. The client has sent over some data and the AD wants you to perform some exploratory data analysis.

##### The data that was sent over includes:

      • Historical customer data: Customer data such as usage, sign up date, forecasted usage etc
      • Historical pricing data: variable and fixed pricing data etc
      • Churn indicator: whether each customer has churned or not
      
##### Tasks to do
**Sub-Task 1:**

Perform some exploratory data analysis. Look into the data types, data statistics, specific parameters, and variable distributions. This first subtask is for you to gain a holistic understanding of the dataset.

**Sub-Task 2:**

Verify the hypothesis of price sensitivity being to some extent correlated with churn. It is up to you to define price sensitivity and calculate it.

**Sub-Task 3:**

Prepare a half-page summary or slide of key findings and add some suggestions for data augmentation – which other sources of data should the client provide you with and which open source datasets might be useful?

**Note:** Use the 2 datasets within the additional resources for this task and if you’re unsure on where to start with visualizing data, use the accompanying links. Be sure to also use the data description document to understand what the columns represent. The task description document outlines the higher-level motivation of the project.

**How to solve this task:**
  Think about ways you can define price sensitivity. Make sure to think of all possible ways and investigate them.


## Task 3 - Feature Engineering & Modelling
Uncovering signals within the data, predicting churn probability and evaluating model performance

#### The background information on this Task 3

The team now has a good understanding of the data and feels confident to use the data to further understand the business problem. The team now needs to brainstorm and build out features to uncover signals in the data that could inform the churn model.

Feature engineering is one of the keys to unlocking predictive insight through mathematical modeling. Based on the data that is available and was cleaned, identify what you think could be drivers of churn for our client and build those features to later use in your model.

First focus on building on top of the feature that your colleague has already investigated: **“the difference between off-peak prices in December and January the preceding year”**. After this, if you have time, feel free to get creative with making any other features that you feel are worthwhile.

Once you have a set of features, you must train a Random Forest classifier to predict customer churn and evaluate the performance of the model with suitable evaluation metrics. Be rigorous with your approach and give full justification for any decisions made by yourself as the intern data scientist. 

Recall that the hypotheses under consideration is that churn is driven by the customers’ price sensitivities and that it would be possible to predict customers likely to churn using a predictive model.

If you’re eager to go the extra mile for the client, when you have a trained predictive model, remember to investigate the client’s proposed discounting strategy, with the head of the SME division suggesting that offering customers at high propensity to churn a 20% discount might be effective.

Build your models and test them while keeping in mind you would need data to prove/disprove the hypotheses, as well as to test the effect of a 20% discount on customers at high propensity to churn.

##### Tasks to do
**Sub-Task 1**

Your colleague has done some work on engineering the features within the cleaned dataset and has calculated a feature which seems to have predictive power. 

This feature is “the difference between off-peak prices in December and January the preceding year”. 

**Sub-Task 2**

Now that you have a dataset of cleaned and engineered features, it is time to build a predictive model to see how well these features are able to predict a customer churning. It is your task to train a Random Forest classifier and to evaluate the results in an appropriate manner. We would also like you to document the advantages and disadvantages of using a Random Forest for this use case. It is up to you how to fulfill this task, but you may want to use the below points to guide your work:

Ensure you’re able to explain the performance of your model, where did the model underperform?
Why did you choose the evaluation metrics that you used? Please elaborate on your choices.
Document the advantages and disadvantages of using the Random Forest for this use case.
Do you think that the model performance is satisfactory? Give justification for your answer.
(Bonus) - Relate the model performance to the client's financial performance with the introduction of the discount proposition. How much money could a client save with the use of the model? What assumptions did you make to come to this conclusion?

**How to solve this task:**
**Sub-Task 1**

♦ Think of ways to evaluate a feature against a label.

♦ Think of ways to add new features which would complement the already existing ones.

♦ Think of feature granularity.

♦ Remove unnecessary features.
    
**Sub-Task 2**

♦ Is this problem best represented as classification or regression?

♦ What kind of model performance do you think is appropriate?

♦ Most importantly how would you measure such a performance?

♦ How would you tie business metrics such as profits or savings to the model performance?
    
    
## Task 4 - Findings & Recommendations
Presenting your results and giving recommended actions to the client

#### The background information on this Task 3

The client wants a quick update on the project progress.

The AD wants you to draft an abstract (executive summary) of your findings so far.

##### Tasks to do
Develop an abstract slide synthesizing all the findings from the project so far, keeping in mind that this will be for the key stakeholders meeting which the Head of the SME division, as well as other various stakeholders, will be attending.

**Note:** a steering committee meeting is a meeting where the BCG team presents key findings and recommendations (and/or project progress) to key client stakeholders.

Please use the template below and submit your summary slide in PDF format. 

A few things to think about for this abstract include:

What is the most important number or metric to share with the client?
What impact would the model have on the client’s bottom line?

**How to solve this task:**

♦ What do you think the client wants to hear? How much detail should you go into, especially with the technical details of your work?

♦ Always test what you write with the “so what?” test, i.e. sharing a fact, even an interesting one, only matters if the client can actually do something useful with it. E.g. 60% of your customers are from City A is pointless, but customers in City A should be prioritized for giving discount as they are among your most valuable ones, if true, is an actionable finding
