# Netflix Customer Churn & Engagement Analytics

## Project Overview
This repository contains an end-to-end data science project focused on predicting customer churn for a subscription-based streaming service. The project follows initial business understanding and exploratory data analysis to predictive modeling and business intelligence reporting.

## 1. Business Understanding

### The Business Context
In the highly competitive streaming market, keeping subscribers is the key to steady profits. For platforms like Netflix, the business model depends on getting the most value out of each customer over time. Because the market is crowded and competition is strong, getting a new customer is much more expensive than keeping an existing one. As a result, the main business problem is customer churn - the number of users who cancel their subscriptions. Losing a subscriber means losing not only a single monthly payment, but also all the money they would bring in the future.

### The Core Objective
The main aim of this project is to change from a reactive to a proactive strategy. Instead of acting only after a customer cancels, the company needs to predict which users are most likely to leave. By looking at past data to find these people early, the company can take effective and affordable actions - such as offering special deals, personalized movie suggestions, or loyalty discounts. This helps to keep them on the platform before they decide to quit.

### Theoretical Foundation: The Expected Value Framework
Dealing with churn is not just about finding trends in data, it requires connecting data with financial results. According to the Expected Value theory in business, decisions should be based on the financial costs and benefits of different results, rather than just trying to predict things perfectly. When predicting churn, making a mistake has very different financial consequences.

A "False Positive" happens when we mistakenly think a loyal customer might leave and give them a discount. This only causes a small drop in profit. On the other hand, a "False Negative" means we fail to notice a customer who really wants to cancel. This results in the complete loss of the user and their future payments. Therefore, the goal is not to be 100% accurate overall. Instead, the focus is on successfully finding the people who actually want to leave, while making sure the cost of saving them remains profitable for the company.