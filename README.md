# Vehicle_Insurance_prediction

In this guide, we will learn how to do training a machine learning model with DecisionTreeClassifier, RandomForestClassifier, KNeighborsClassifier and BaggingClassifier. First, we will do exploratory data analysis to understand the data. We will apply label encoding, K-Means algorithm and examine correlation map, what our dataset contains, whether there is a missing value or not.

Dataset we will be working on is health insurance cross sales forecast.

#Context

Our client is an Insurance company that has provided Health Insurance to its customers now they need your help in building a model to predict whether the policyholders (customers) from past year will also be interested in Vehicle Insurance provided by the company.

An insurance policy is an arrangement by which a company undertakes to provide a guarantee of compensation for specified loss, damage, illness, or death in return for the payment of a specified premium. A premium is a sum of money that the customer needs to pay regularly to an insurance company for this guarantee.

Building a model to predict whether a customer would be interested in Vehicle Insurance is extremely helpful for the company because it can then accordingly plan its communication strategy to reach out to those customers and optimise its business model and revenue.

#Data Description

id = Unique ID for the customer
Gender = Gender of the customer
Age = Age of the customer
Driving_License = 0 : Customer does not have DL, 1 : Customer already has DL
Region_Code = Unique code for the region of the customer
Previously_Insured = 1 : Customer already has Vehicle Insurance, 0 : Customer doesn’t have Vehicle Insurance
Vehicle_Age = Age of the Vehicle
Vehicle_Damage = 1 : Customer got his/her vehicle damaged in the past. 0 : Customer didn’t get his/her vehicle damaged in the past.
Annual_Premium = The amount customer needs to pay as premium in the year
PolicySalesChannel = Anonymized Code for the channel of outreaching to the customer ie. Different Agents, Over Mail, Over Phone, In Person, etc.
Vintage = Number of Days, Customer has been associated with the company
Response = 1 : Customer is interested, 0 : Customer is not interested
