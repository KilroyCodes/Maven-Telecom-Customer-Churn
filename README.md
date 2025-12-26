# Maven Telecom Customer Churn
---
## Background
After studying the data in [Maven's Telecoms Customer Churn Challenge](https://mavenanalytics.io/challenges/maven-churn-challenge), I found myself diving deeper and deeper into understanding churn itself. 

In this repository, I go through:
* Churn Prediction (will this customer churn?) via XGBoost
* Which variables contribute most to churn prediction
* What is the probability our customers (as a whole or as a segment) have not yet churned at X months? via Kaplan-Meier curves
* Which variables are contributory or protective against churn, and are these findings statistically significant? via Cox Proportional Hazards Model (we do this with the whole customer base and also with contract-based strata)
* What is our customers' baseline expected tenure? and what would be the change to this if we engaged in any interventions?
