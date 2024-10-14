House Price Prediction - Bengaluru


Project Overview
This project aims to predict house prices in Bangalore using the Kaggle dataset Bengaluru_House_Data. Machine learning models such as Linear Regression, Lasso Regression, and Decision Tree were applied and compared. Detailed Exploratory Data Analysis (EDA) and feature engineering were performed to improve the predictive power.
Table of Contents
Project Overview
Dataset
Installation
Project Structure
Models Used
Results
Usage
License
Dataset
The dataset used is Bengaluru_House_Data from Kaggle, which includes house price information in Bangalore. Key features include:

Location
Total Square Feet
Number of Bathrooms
Number of Bedrooms
Price per Square Foot
You can download the dataset here.

Installation
To run this project, ensure you have Python 3.x installed. Install the required libraries with:

bash
Copy code
pip install pandas numpy scikit-learn matplotlib seaborn
Project Structure
The project is organized as follows:

bash
Copy code
├── data/                  # Contains the dataset
├── notebooks/             # Jupyter notebooks with code and analysis
├── models/                # Saved machine learning models
├── results/               # Visualizations and comparison results
└── README.md              # Project documentation
Models Used
The following models were utilized and compared in terms of performance:

Linear Regression: A simple regression model that assumes a linear relationship between dependent and independent variables.
Lasso Regression: An extension of linear regression that applies L1 regularization to prevent overfitting.
Decision Tree: A non-linear model that captures more complex relationships within the data.
Results
Linear Regression outperformed the other models, providing the most accurate predictions.
Lasso Regression performed similarly but added regularization to mitigate overfitting.
Decision Tree captured non-linear relationships but slightly underperformed compared to linear models.
Key insights from EDA and feature engineering significantly improved the prediction accuracy.

Usage
To explore the project:

Clone this repository:
bash
Copy code
git clone https://github.com/sarrahhwaeell/house-price-prediction.git
Download the dataset from Kaggle and place it in the data/ directory.
Run the Jupyter notebooks in the notebooks/ folder to see the EDA, feature engineering, and model comparisons.
License
This project is licensed under the MIT License - see the LICENSE file for details
