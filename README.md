# Airline Customer Value Analysis
## Background
Frequen-Flyer Program (FFP) is a loyalty program offered by an airline. For airline company, it's necessary to know better about their customer behavior, the purpose is they can provide better services and benefits to customers who have the potential to become loyal customers.
Company need to know it's customer behavior to boost their loyalty program.
### Goal
Improve airline frequent-flyer program and target the right customers to be offer program's benefits.
### Objective 
Create a cluster prediction model using unsupervised learning so that it makes easier for airline to make decisions.
## Data
The dataset contains 62.988 data rows and 23 features of customer behavior features who used company flying service.
## Tools
On this project I've used python as programming language; jupyterlab as notebook; pandas, numpy, sklearn and dython to preprocessing and machine learning section; combination of matplotlib and seaborn library to generated data visualization.
## Contents
### **Exploratory Data Analysis**
### **Data Cleaning and Preprocessing**
On this section, there are few processes such as handling missing and duplicated value, feature selection using RFMLC (Recency, Frequency, Monetary, Loyalty and C) methods, handling outliers using IQR (Q1=1%; Q3=99%), feature transformation to selected features using minmaxscaler, and splitting data on 70:30 proportion.
### **Data Modeling**
Using K-Means Clustering with cross-validation elbow method to inertia and silhoutte score. Also there is usage of Principal Component Analysis (PCA) to reduce dimensionality.
### **Customer Persoality Analysis for Marketing Retargeting**
Based on my model, there are 4 customer clusters:
1. Potential Customer:
Customers on this group have a mid range of frequency on using flying service, also they are new members with a mid range of total spend on flying service.
2. Low-Valued Customer:
Customers on this group have a lowest frequency with lowest total spend on using flying service.
3. High-Valued Customer:
Customers on this group have a highest frequency with highest total spend on using flying services.
4. Retain-Required Customer:
Customers on this group have a mid range of frequency and total spend on using flying services, but they are not new members.
### **Recommedation**
#### Actionable Isights
Promos that will be given in business recommendations are in the form of coupons and flight discounts. Loyalty points are in the form of giving additional points every time they fly according to the customer's class.
1. For Potential Customer group, they can be categorized as new customers, we can provide promos.
2. For Retain-Required Customer, which is categorized as a loyal customer, we can provide 'loyalty point + promo'
3. For High-Valued Customer, we can provide 'loyalty points + customer class upgrades(4,5,6) + promos' with certain benefits at each level to avoid the risk of churn on this group.
4. For Low-Valued Customer, they can be given the same promo like Potential-Customer group to increase their frequency of flights.
