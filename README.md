Food Wastage Prediction - Donation Availability
This project aims to predict food donation availability to help reduce food wastage. By analyzing historical donation data, the goal is to build a model that can accurately forecast how much food donations (kgs) will be available.
Table of Contents
* Problem Statement
* Data Collection
* Data Preprocessing
* Feature Selection/Engineering
* Exploratory Data Analysis (EDA)
* Model Evaluation
* Dependencies

Problem Statement
Predicting food donation availability to avoid food wastage. This model will help in forecasting how much food donations are likely to be available, ensuring that they can be distributed before they are wasted.
Data Collection
The dataset used for this project contains historical data on food donations, including details like:
* Donation type
* Time and date of donation
* Quantity of food donated
* Location of donation
Data can be found in the data/ folder.
Data Preprocessing
Steps taken during preprocessing:
* Handling missing values
* Removing duplicates
* Encoding categorical features
Feature Selection/Engineering
* Identifying key features that affect food donation availability (e.g., time of year, type of food, weather conditions).
* Creating new features based on existing data, like time-based features (hour, day of week, etc.).
Exploratory Data Analysis (EDA)
* Visualizing trends in food donations over time.
* Analyzing correlations between different features.
* Identifying potential outliers or anomalies in the data.
Model Evaluation
* Train machine learning models such as Random Forest, XGBoost, and Linear Regression.
* Evaluate the model using performance metrics like accuracy and precision.
If Model Performance is Unsatisfactory
If the model's performance doesn't meet expectations, revisit the following steps:
* Data Preprocessing (step 3)
* Feature Selection/Engineering (step 4)
* EDA (step 5)
Repeat these steps until the desired model accuracy is achieved.  
Dependencies
* Python 3.8+
* pandas
* numpy
* matplotlib
* seaborn
