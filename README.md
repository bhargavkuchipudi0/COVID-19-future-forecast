# COVID-19 Future Forcast for Next 10 Days

## Description
    Untill the COVID-19 pandemic, the weather app was one of the most used apps on my phone. I used to check it several times a days. Most of us do because of the weather conditions here in Michigan. Generally the weather forcast work well. As I am in the process of learning AI (It is one of my academic courses), I have learned about Linear Regression, Support Vector Machines(SVR), and Bayesian ridge Regression. 

    In my previous project I have created a python automation script which is working pretty well. I thought of expanding the project by predicting the future forecast for the coming 10 days.

## Data Source
    The data souce I rely on is from European Centre for Disease Prevention and Control. The following link is the reference for the csv file https://covid.ourworldindata.org/data/ecdc/total_cases.csv

## Data Pre-Processing
    I have tried predicting the future values with the column 'world' in the data set. But, Unfortunatly the models are not able to predict the values as the data from the initial days doesnot have a proper relation. So, I tried eliminating few rows(days) and started worling on the data from JAN 21 2020. After that I got good results from the three models.

