# Car-Price-Predictor

## This project aims to predict car prices based on various features using machine learning techniques. The notebook follows a ## structured approach:

# 1.Data Cleaning & Preprocessing:
	
  * Loads data from quikr_car.csv.
  * Identifies and handles missing values in kms_driven and fuel_type.
  * Cleans and converts categorical and numerical columns:
		* Converts year from string to integer.
		* Removes non-numeric values from Price and kms_driven.
		* Extracts relevant details from the name column (keeping the first three words).

# 2.Feature Engineering:
	
  * Drops unnecessary columns.
  * Converts categorical variables (fuel_type, name) into numerical representations.

# 3.Model Building:
	
  * Splits data into training and testing sets.
  * Uses machine learning models such as Linear Regression, Decision Tree, and Random Forest.
  * Trains the models on the cleaned dataset.

# 4.Evaluation:
	
  * Assesses model performance using metrics like R² score and Mean Squared Error (MSE).
  * Compares different models to find the best-performing one.

# Key Insights
	
  * Data Quality Issues: The dataset contained inconsistent values (e.g., "Ask for Price") that had to be 	cleaned.
  * Year of Manufacture Impact: Older cars generally have lower prices, but exceptions exist based on brand value 	and         condition.
  * Fuel Type Influence: Diesel cars tend to have higher resale value compared to petrol cars.
  * Random Forest Performs Best: Tree-based models tend to handle non-linearity and categorical variables better 	than           linear models.

# Conclusion
	
  * The model effectively predicts car prices, but accuracy could be further improved with more data and feature 	tuning.
  * Additional factors like brand reputation, accident history, and location could enhance prediction quality.
  * Deploying the model as a web app or API would allow users to input car details and get instant price 	estimates.
