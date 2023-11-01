# Order-Amount-Prediction
This project aims to build a Machine Learning model to predict the order amount that customers can place in the upcoming days based on their past order information and behavior.

# Objective
The objective of the summer internship project is:
To build a Machine Learning Model to predict the order amount, customers might make in the upcoming days.
You will be receiving an orders dataset that contains the past orders information and behavior of various buyers. Based on the previous orders patterns, the ML model needs to predict what will be the amount of orders the customer is going to place in the upcoming days. 

# Project Requirements
The project requires the following packages to be installed:

Pandas<br>
NumPy<br>
Scikit-learn<br>
Matplotlib<br>
Seaborn<br>

To install these packages, you can run the following command:
<br>

pip install -r requirements.txt

# Milestones
The project consists of several milestones, each focusing on a specific task. Here is a summary of the milestones:

Data Sanity : In this milestone, we perform data cleaning and preprocessing tasks such as handling missing values, formatting date columns, removing inconsistent records, and converting currency values to USD.

EDA (Exploratory Data Analysis) : This milestone involves analyzing the dataset to gain insights and understand the relationships between variables. We create visualizations such as histograms, pie charts, line plots, and box plots to explore different aspects of the data.

Feature Engineering and Selection : In this milestone, we perform feature engineering techniques such as encoding categorical variables, applying log transformations to continuous columns, and creating new features through grouping. We also analyze the correlation between variables using a heatmap and select relevant features for prediction.

ML Models and Evaluations : This milestone focuses on building and evaluating different machine learning models for order amount prediction. We try various models such as Linear Regression, Support Vector Machine, Decision Tree, Random Forest, AdaBoost, and XGBoost. We perform model evaluations using metrics like Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-Squared. We compare the accuracies of the models and select the best-performing one. We also perform hyperparameter tuning to further improve the model's accuracy.

Please refer to the individual Jupyter notebooks in the notebooks/ directory for detailed explanations and code implementation for each milestone.

# Conclusion
This project provides a framework for predicting order amounts using Machine Learning techniques. By following the milestones and implementing the necessary tasks, you can build and evaluate models for order amount prediction. Feel free to customize and expand upon the project to suit your specific requirements.

