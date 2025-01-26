# Housing Prices Prediction Project Using Machine Learning
# Overview
This project focuses on predicting house prices based on multiple features such as house area, number of bedrooms, bathrooms, proximity to the main road, and additional amenities. Using a dataset with multicollinearity challenges, the project explores building and evaluating regression models to deliver accurate predictions. The project not only helps refine regression modeling skills but also provides insights into the factors influencing real estate pricing.

# Dataset
The dataset, Housing.csv, includes 13 features and 545 samples. It is a compact yet complex dataset that requires careful preprocessing to overcome multicollinearity issues.

# Features
price: Price of the houses (target variable).
area: Area of the house (in square feet).
bedrooms: Number of bedrooms.
bathrooms: Number of bathrooms.
stories: Number of stories.
mainroad: Whether the house is connected to the main road (yes/no).
guestroom: Whether the house has a guestroom (yes/no).
basement: Whether the house has a basement (yes/no).
hotwaterheating: Whether the house has hot water heating (yes/no).
airconditioning: Whether the house has air conditioning (yes/no).

# Dataset Source
# Acknowledgements:
Harrison, D. and Rubinfeld, D.L. (1978). Hedonic prices and the demand for clean air. J. Environ. Economics and Management.
Belsley, D.A., Kuh, E., and Welsch, R.E. (1980). Regression Diagnostics. New York: Wiley.
Objective
Understand and preprocess the dataset to ensure it's ready for modeling.
Build and evaluate regression models to predict house prices:
Linear Regression.
Random Forest Regressor.
Compare model performance using key metrics such as R² Score and Root Mean Square Error (RMSE).

# Project Workflow
Data Preprocessing:

Converted categorical features (yes/no) to binary (1/0).
Checked for and handled missing values (none in this dataset).
Split the dataset into training (80%) and testing (20%) sets.

# Data Visualization:

Explored feature correlations with price using heatmaps.
Visualized model predictions against actual house prices.
Modeling:

Implemented Linear Regression for a baseline predictive model.
Used Random Forest Regressor to improve predictions by capturing nonlinear relationships.

# Model Evaluation:

Evaluated both models using:
R² Score: Proportion of variance explained by the model.
RMSE: Measure of prediction error.

# Results
Linear Regression:

R² Score: [Insert result after running code]
RMSE: [Insert result after running code]
Random Forest Regressor:

R² Score: [Insert result after running code]
RMSE: [Insert result after running code]
The Random Forest Regressor outperformed Linear Regression, demonstrating its ability to handle nonlinear relationships and feature interactions effectively.

# Dependencies
To run this project, ensure you have the following Python libraries installed:

pandas
numpy
matplotlib
seaborn
scikit-learn
How to Run the Project

# Clone the repository:
bash
Copy
Edit
git clone https://github.com/yourusername/housing-price-prediction.git

# Navigate to the project directory:
bash
Copy
Edit
cd housing-price-prediction
Upload the dataset (Housing.csv) to the project folder.
Open and run the code in a Jupyter Notebook or Google Colab.

# Visualizations
Sample Correlation Heatmap

Predictions vs True Prices

# Future Work
Explore advanced feature engineering techniques.
Experiment with additional regression models such as Gradient Boosting and XGBoost.
Perform hyperparameter tuning for the Random Forest model to improve accuracy.

# Contributors
Samuel Abiodun Ojeleke
M.Sc. Computer Science Candidate, Federal University Oye Ekiti.
Email: ojelekesamuel4@gmail.com
Linkedin: https://www.linkedin.com/in/samuel-ojeleke

# License
This project is released under the CC0: Public Domain license.

# Acknowledgements
Special thanks to:
Harrison, D. and Rubinfeld, D.L. for the dataset.
Scikit-learn and Matplotlib contributors for their amazing tools.
