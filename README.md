# Crop-Production-prediction
Predicting Crop Production Based on Agricultural Data

Technical Tags: 
1. Data Cleaning and proprocessing
2. Exploratory Data Analysis [EDA]
3. Data Visualization
4. Streamlit
5. Machine Learning(Using Randomn Forest Regression)

Problem Statement:
      Agriculture is a key contributor to the economy, and accurately predicting crop production is essential for improving planning and decision-making. 
      This project aims to develop a regression model that forecasts crop production (in tons) based on agricultural factors such as area harvested (in hectares), yield (in kg/ha), and the year, for various crops grown in a specific region.

Business Use Cases:
1.Food Security and Planning
2.Agricultural Policy Development
3.Supply Chain Optimization
4.Market Price Forecasting
5.Precision Farming
6.Agro-Technology Solutions


Data Cleaning: 
 1. Data was in excel type and each columns are provided in then form of row
 2. Using Pivot transformed rows into specific columns that we needed for model.
 3. Identified missing values and replaced it and removed outliers present in the data

EDA:
  Identiied the trend and found correlation of datas
  Identiied top 10 most and least cultivated crops among areas, so that we can come with the conclusion among areas which is suitable area for particular crops.
  Identiied top 10 most and least cultivated Areas

Machine Learning
  Used Random Forest regression is model used for model building
  R² Score: **0.9996**
  Mean Squared Error (MSE): 2178340.6068
  Mean Absolute Error (MAE): **454.5536**
  
  
