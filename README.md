# Optimizing Telemarketing

## Context

Numerous Machine Learning algorithms have been used to detemine the success of telemarketing calls for selling long-term deposits.

Data used in this project is originally obtained from a Portuguese banking institution (from 2008 to 2012). The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed. 

Work done in this project is inspired by [Moro et al., 2014](https://www.sciencedirect.com/science/article/pii/S016792361400061X) S. Moro, P. Cortez and P. Rita. A Data-Driven Approach to Predict the Success of Bank Telemarketing. Decision Support Systems, Elsevier, 62:22-31, June 2014.

## Introduction
In the original paper, four Machine Learning models (Decesion Trees, Logistic Regression, Neural Networks, and Support Vector Machines) were used. And all of these models were compared based on the AUC and ALIFT metrics. Neural Networks have had the highest results followed by Decesion Trees.

## Data

Datasets used in this repository are retrieved from [Bank Marketing](https://www.kaggle.com/bletchley/bank-marketing) dataset on Kaggle. 

- Data is **unbalanced** since 12.38% of the records are related with success.
- After feature engineering the data, 22 features out of 150 have been selected to be used in the models.
