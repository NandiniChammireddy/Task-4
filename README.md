#Objectives:
To build a linear regression model that predicts house prices.
To understand how features like Size, Location, and Number of Rooms affect pricing.
To evaluate model performance using metrics like RMSE and R² score.
##KeyFeatures of the Code:
#DataPreprocessing:
Handles missing values.
Standardizes numerical features (Size, Rooms).
Encodes categorical data (Location) using one-hot encoding.
#ExploratoryDataAnalysis:
Descriptive statistics.
Visuals like pairplot and boxplot for insight into data distribution and outliers.
#ModelBuilding:
Splits data into training and testing sets.
Builds a Linear Regression model using a pipeline.
Trains the model on features to predict Price.
#ModelEvaluation:
Calculates RMSE (error magnitude).
Computes R² Score (model accuracy).
Plots Actual vs Predicted Prices for visual comparison.
