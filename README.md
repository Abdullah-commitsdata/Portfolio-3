# Portfolio-3 Used Car Pricing Predictive Modelling 
Python | Machine Learning | Kaggle Competition | Business Analytics

This repository contains my solutions for the Portfolio 3 assignment for the course COMP8001 – Applied Predictive Analytics. The assignment involves analyzing a used car price prediction dataset to predict car prices using various regression models, and evaluating the strengths and weaknesses of these models.

Contents:
Used Car Predictive Analytics Model.ipynb: The Jupyter notebook containing the questions, solutions, code, and analysis for Portfolio 4.
Train.csv & Test.csv: The datasets used for this analysis.

Competition Objective:

The core objectives of this competition is to challenge participants in the following areas:

Data Cleaning: Meticulously examine and refine the provided dataset to ensure its accuracy and suitability for modelling.
Feature Engineering: Creatively construct new features from the existing data that will enhance the model's ability to learn patterns and make predictions.
Model Building: Develop a robust predictive model capable of generating accurate forecasts based on the prepared dataset.
Forecasting: Utilize the constructed model to generate forecasts for a separate test dataset.
Leaderboard Ranking: The competition winner will be determined by achieving the highest ranking on the leaderboard.

Description:
The objective of this contest is to forecast the prices of listed cars on the basis of car features.

Participants will need to conduct exploratory data analysis, clean the dataset, deal with missing values, engage in feature engineering, construct predictive models, and deliver their forecasts.

The training dataset contains 7,000 entries with 39 variables, while the test set includes 3,000 observations of 38 variables. The target variable is the price.

Dataset Description:
Files
train.csv - the training set
test.csv - the test set
Description of Variables:
1) vin: Type String. Vehicle Identification Number is a unique encoded string for every vehicle. Read more at https://www.autocheck.com/vehiclehistory/vin-basics 2) back_legroom: Type String. Legroom in the rear seat. 3) body_type: Type String. Body Type of the vehicle. Like Convertible, Hatchback, Sedan, etc. 4) city: Type String. city where the car is listed. Eg: Houston, San Antonio, etc. 5) city_fuel_economy 6) daysonmarket: Type Integer. Days since the vehicle was first listed on the website. 7) dealer_zip: Type Integer. Zipcode of the dealer 8) engine_displacement: Type Float. engine displacement is the measure of the cylinder 9) engine_type: Type String. The engine configuration. Eg: I4, V6, etc. 10) exterior_color: Type String. Exterior color of the vehicle, usually a fancy one same as the brochure. 11) franchise_dealer: Type Boolean. Whether the dealer is a franchise dealer. 12) front_legroom: Type String. The legroom in inches for the passenger seat 13) fuel_tank_volume: Type String. Fuel tank's filling capacity in gallons 14) fuel_type: Type String. Dominant type of fuel ingested by the vehicle. 15) height: Type String. Height of the vehicle in inches 16) highway_fuel_economy: Type Float. Fuel economy in highway traffic in km per litre 17) horsepower: Type Float. Horsepower is the power produced by an engine. 18) interior_color: Type String. Interior color of the vehicle, usually a fancy one same as the brochure. 19) is_new: Type Boolean. If True means the vehicle was launched less than 2 years ago. 20) latitude: Type Float. Latitude from the geolocation of the dealership. 21) length: Type String. Length of the vehicle in inches 22) listed_date: Type String. The date the vehicle was listed on the website. Does not make daysonmarket obsolete. The prices is dayson_market days after the listed date. 23) listing_color: Type String. Dominant color group from the exterior color. 24) longitude: Type Float. Longitude from the geolocation of the dealership. 25) make_name: Type String. Name of the manufacturer 26) maximum_seating: Type String. Maximum no of seats 27) mileage: Miles driven till lising date 28) model_name: Type String. Name of the model 29) power: Type String. Maximum power and RPM 30) savings_amount: Type Integer. Amount saved in USD 31) seller_rating: Type Float 32) torque: Type String. Maximum Torque and RPM 33) transmission: Type String. transmission type (A - Automatic, M- manual, CVT- continuous variable transmission, Dual Clutch) 34) transmission_display: Type String. No of gears and Transmission type 35) wheel_system: Type String. Type of wheel drive(AWD , FWD, 4WD, RWD, 4X2) 36) wheelbase: Type String. Horizontal distance between the centers of the front and rear wheels 37) width: Type String. Width of the vehicle in inches 38) year: year in which car was released into the market 39) price: Listed price

Tasks & Actions: 

Task 1: Problem Understanding & Exploratory Analysis
Actions:
Defined the business problem of predicting used car sale prices using historical vehicle data.
Researched market factors affecting used car pricing including brand, mileage, transmission, fuel type, and engine performance.
Analysed competition evaluation metric (RMSE) and its impact on forecasting accuracy.
Performed exploratory data analysis (EDA) to identify pricing trends, outliers, correlations, and variable distributions.
Visualised key relationships between car features and target sale prices using Python libraries.

Task 2: Data Cleaning & Feature Engineering
Actions:
Cleaned raw vehicle datasets by handling missing values, duplicates, and inconsistent formats.
Converted text-based vehicle specifications into structured numerical variables for modelling.
Performed feature engineering on engine, mileage, torque, and power-related attributes.
Applied categorical encoding techniques including one-hot encoding for model compatibility.
Identified and treated outliers to improve prediction reliability.
Built structured datasets suitable for regression and machine learning workflows.
Developed relational data structures and feature sets for improved forecasting performance.

Task 3: Machine Learning Modelling & Forecasting
Actions:
Built multiple regression models including Linear Regression, Ridge Regression, and XGBoost.
Trained and validated models using cross-validation techniques and train-test splits.
Tuned hyperparameters to optimise forecasting accuracy and minimise RMSE.
Compared model performance using evaluation metrics and validation results.
Selected the best-performing model for final prediction generation.
Generated forecasting outputs and submitted predictions to Kaggle competition leaderboard.

Task 4: Insights, Reporting & Business Recommendations
Actions:
Analysed feature importance to identify major drivers of used car prices.
Interpreted model outputs to explain pricing behaviour and market trends.
Created visual reports and charts to communicate findings clearly to stakeholders.
Documented the full analytics workflow using Jupyter Notebook and Markdown explanations.
Presented recommendations for improving pricing decisions using predictive analytics.

Technical Skills Used:
Python,
Pandas,
NumPy,
Scikit-learn,
XGBoost,
Data Cleaning,
Feature Engineering,
Exploratory Data Analysis (EDA),
Machine Learning,
Regression Modelling,
Cross Validation,
Forecasting,
Data Visualisation,
Jupyter Notebook,
Kaggle
