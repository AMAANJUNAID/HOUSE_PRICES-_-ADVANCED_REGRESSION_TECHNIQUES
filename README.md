# PRODIGY_ML_01

# House Prices - Advanced Regression Techniques 🏡
# Description 📜
This project predicts house prices using advanced regression techniques on a Kaggle dataset. It leverages machine learning models to estimate property values based on various features like living area, number of bedrooms, bathrooms, and total rooms above ground.

# How It Works 🚀
1. Data Preprocessing: Fills missing values for categorical features using the mode and for numerical features using the mean.

2. Feature Selection: Chooses key features (GrLivArea, BedroomAbvGr, FullBath, HalfBath, TotRmsAbvGrd) for prediction.

3. Model Training: Splits the data into training and validation sets, trains a linear regression model, and evaluates it.

4. Predictions: Makes predictions on validation and test sets, visualizes results, and saves the predictions to a CSV file.

# Features ✨
✅ Data Cleaning: Handles missing values for both categorical and numerical features.

✅  Model Training: Implements linear regression for predicting house prices.

✅ Visualization: Provides insightful visualizations of actual vs. predicted prices, residuals, and feature relationships.

✅ Example Prediction: Allows for example predictions based on input data.

✅ Submission Ready: Generates a CSV file ready for submission.

# How to Run 🖥️

1.Clone the Repository:

git clone https://github.com/YOUR_USERNAME/House-Prices-Regression.git
cd House-Prices-Regression

2. Install Dependencies: Make sure you have the required Python packages:

pip install pandas numpy matplotlib seaborn scikit-learn

3. Run the Python Script: Execute the script to preprocess data, train the model, make predictions, and visualize results:

python your_script.py

4. View Results: Check the generated visualizations and submission.csv file in the repository directory.

# Results 📊
✅ Model Evaluation: Evaluates model performance using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R²).

✅ Visualization: Visualizes the actual vs. predicted house prices, residuals, and feature relationships to provide insights into model performance and data distribution.
