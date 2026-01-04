**بسم الله الرحمن الرحيم**

While the original goal included building classification and regression models,
we didn't have the chance to finish it so it is just EDA and analysis for the data 
and some feature engineering.

##ML_Final_project

#DESCRIPTION

    1- Data ingestion & memory-savvy joins

        1- We downloaded the instacart market basket dataset from kaggle
           by the link method which kaggle provides then we loaded each dataset
           file to a variable.
        2- We used some instance variable and functions to understand
           the datasets like shape, head() and info().
        3- We then used merge() function from pandas to join these file
           but we except the train file to avoid data leakage.

    2- Exploratory Data Analysis + Cleaning & Imputation + Feature engineering (User-level features)
    
        1- We used matplotlib library for visualizing the data to detect and see missing values
           and also to see the fetures distibution.
        2- We used seaborn library to make the heatmap fiqure and also 
           to make boxplots for outlier detection and visualization and 
           to handle these outliers we used the IQR method.
        3- We used sklearn library to handle missing values and filling them with -1 which it looks the 
           best choice for later models to understand this value.
        4- We used groupby() function to split the data into groups and use 
           them for anlasysis and creatin new features.

#SOURCES

    youtube
    chatGPT
    ML course chapters