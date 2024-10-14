House Price Prediction - Bengaluru
Project Overview
This project aims to predict house prices in Bangalore using the Kaggle dataset Bengaluru_House_Data. I utilized machine learning models like Linear Regression, Lasso, and Decision Tree and compared their performance. The project also includes detailed Exploratory Data Analysis (EDA) and feature engineering to improve prediction accuracy.

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
The dataset used is the "Bengaluru_House_Data" from Kaggle, which contains information about house prices in Bangalore, including features such as:

Location
Total Square Feet
Number of Bathrooms
Number of Bedrooms
Price per Square Foot
You can download the dataset here.

Installation
To run this project, you'll need Python 3.x and the following libraries:

Pandas
Numpy
Scikit-learn
Matplotlib
Seaborn
You can install these dependencies using:

bash
Copy code
pip install pandas numpy scikit-learn matplotlib seaborn
Project Structure
The project is structured as follows:

bash
Copy code
├── data/                  # Contains the dataset
├── notebooks/             # Jupyter notebooks with code and analysis
├── models/                # Contains saved models
├── results/               # Visualizations and comparison results
└── README.md              # Project documentation
Models Used
Linear Regression: A basic regression model that assumes a linear relationship between the target and features.
Lasso Regression: A variant of linear regression that uses L1 regularization to avoid overfitting.
Decision Tree: A non-linear model that captures more complex relationships between features and the target variable.
Results
After training and comparing the models, the Linear Regression model performed best, followed closely by Lasso and Decision Tree. EDA and feature engineering played a significant role in improving the accuracy of predictions.

Usage
You can explore the Jupyter notebooks in the notebooks/ directory to see the analysis and code. To run the project locally:

Clone the repository.
Download the dataset and place it in the data/ folder.
Run the Jupyter notebooks to see the EDA, feature engineering, and model comparison.
License
This project is open-source and available under the MIT License.
