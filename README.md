# Health-Insurance-Cross-Sell-Prediction
Abstract
An insurance policy is an arrangement by which a company undertakes to provide a guarantee of compensation for specified loss, damage, illness, or death in return for the payment of a specified premium. There are multiple factors that play a major role in capturing customers for any insurance policy. Here we have information about demographics such as age, gender, region code, and vehicle damage, vehicle age, annual premium, policy sourcing channel. Based on the previous trend, this data analysis and prediction with machine learning models can help us understand what are the reasons for news popularity on social media and obtain the best classification model.

*Problem Statement
Our client is an Insurance company that has provided Health Insurance to its customers. Now they need the help in building a model to predict whether the policyholders (customers) from the past year will also be interested in Vehicle Insurance provided by the company.

An insurance policy is an arrangement by which a company undertakes to provide a guarantee of compensation for specified loss, damage, illness, or death in return for the payment of a specified premium. A premium is a sum of money that the customer needs to pay regularly to an insurance company for this guarantee.

Building a model to predict whether a customer would be interested in Vehicle Insurance is extremely helpful for the company because it can then accordingly plan its communication strategy to reach out to those customers and optimize its business model and revenue.

Data Description
We have a dataset which contains information about demographics (gender, age, region code type), Vehicles (Vehicle Age, Damage), Policy (Premium, sourcing channel) etc. related to a person who is interested in vehicle insurance. We have 381109 data points available.

Conclusion
Starting from loading our dataset, we firstly performed data cleaning and refactoring by outlier detection and normalization of data. Then we covered EDA, feature selection and algorithm selection, and hyperparameter tuning. The Accuracy score obtained for all models was in the range of 68% to 85% before tuning After tuning the models we were able to get an accuracy of approx 87%. But we selected our best model as the model with an accuracy score of 85% considering precision and recall as we have an unequal number of observations in each class in our dataset, so accuracy alone can be misleading.

















