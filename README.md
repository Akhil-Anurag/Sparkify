# Sparkify
  This is the capstone project for Udacity

## Table of Content
1. Project Motivation and Overview
2. Toolkit, Data Used
3. Methodology
4. Result
5. Next Steps

### Project Motivation and Overview

  Sparkify is a music streaming service just as Spotify and Pandora. With the help of data generated through the user activity on the app with other demographic information 
  , we will try to identify customers who are likely to cancel their usage of the services and send them marketing campaigns to stop them from churning.
  We will manipulate large and realistic datasets with Spark to engineer relevant features for predicting churn.
  
    
### Toolkit and Data Used

  This project uses PySpark, Pandas, Matplotlib and Seaborn.
  Data used is a mini sample of actual data generated through the service log
  
### Methodology

  - ETL
  - Define customer churn and EDA
  - Feature Engg
  - Model pipeline set up
  - Evaluation - Train and Validation 
  - Hypertuning Selected Model  
  - Result - Train and Test 
  - Analyzing the results     

### Result

  - According to the results of the model, it is the frequency of Thumbs Down that has the greatest impact. Churn users have more Thumbs Down. Naturally, users will leave if they are not satisfied.

    I post a blog about the detail, you can find it [here](https://medium.com/@akhilanurag03/sparkify-a-use-case-on-churn-prediction-c9ba14d23df8).

### Next Steps
  - The full dataset is 12GB, of which we have analyzed a mini subset in the workspace environment. Optionally, we can choose to deploy a Spark cluster on the cloud using AWS or IBM Cloud to analyze a larger amount of data.
  
