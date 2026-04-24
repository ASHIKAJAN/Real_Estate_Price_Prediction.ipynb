🏠 Real Estate Price Prediction using Machine Learning
📌 Project Overview
This project focuses on analyzing real estate data to understand the key factors influencing property prices and building a machine learning model to predict property prices accurately. The model helps buyers, sellers, and investors make better data-driven decisions.
________________________________________
🎯 Objective
•	Analyze real estate dataset to identify patterns and trends
•	Determine the most important factors affecting property prices
•	Build and evaluate machine learning models for price prediction
________________________________________
📊 Dataset Information
•	Dataset Name: Real Estate Dataset
•	Number of Rows: 10,000+
•	Features include:
o	City
o	Property Type
o	Location Type
o	Area (sqft)
o	Bedrooms
o	Bathrooms
o	Amenities
•	Target Variable: Price_INR
________________________________________
⚙️ Technologies Used
•	Python
•	Google Colab
•	Pandas
•	NumPy
•	Matplotlib
•	Scikit-learn
________________________________________
🔍 Project Workflow
1. Data Preprocessing
•	Checked for missing values
•	Encoded categorical variables using Label Encoding
•	Prepared dataset for model training
2. Exploratory Data Analysis (EDA)
•	Analyzed price distribution
•	Studied relationships between:
o	Area vs Price
o	Bedrooms vs Price
o	City vs Price
•	Visualized data using graphs
3. Feature Engineering
•	Created new feature: Price per square foot
•	Removed unnecessary columns
4. Model Building
Implemented the following models:
•	Linear Regression
•	Decision Tree Regressor
•	Random Forest Regressor
5. Model Evaluation
Models were evaluated using:
•	Mean Absolute Error (MAE)
•	Mean Squared Error (MSE)
•	R² Score
________________________________________
📈 Results
•	Random Forest performed the best among all models
•	Area and location are the most important factors affecting price
•	Properties with more bedrooms and amenities have higher prices
________________________________________
💡 Key Insights
•	Larger properties tend to have higher prices
•	Urban locations have significantly higher property values
•	Availability of amenities increases property price
•	Newer properties are generally more expensive
________________________________________
🧠 Conclusion
The project successfully built a machine learning model capable of predicting property prices with good accuracy. The analysis shows that area, location, and property features are major contributors to price variation.
