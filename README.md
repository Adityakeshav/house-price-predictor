# House Price Prediction Project
Overview
This project aims to predict house prices using the California Housing Dataset from the Scikit-learn library. The primary focus is to explore data, perform data cleaning, and build a machine learning model to predict house prices based on various features such as median income, house age, and population density.


Dataset
The dataset used for this project is California Housing Dataset which contains the following features:

MedInc: Median income in block
HouseAge: Median house age in block
AveRooms: Average rooms per household
AveBedrms: Average bedrooms per household
Population: Block population
AveOccup: Average household occupancy
Latitude: Block latitude
Longitude: Block longitude
Target (MedHouseVal): Median house value for California districts
Steps Involved
1. Data Understanding
Loaded the dataset using Scikit-learn's datasets module.
Reviewed the features to understand their impact on house prices.
2. Data Exploration (Exploratory Data Analysis - EDA)
Visualized the dataset to observe relationships and trends using Matplotlib and Seaborn.
Key visualizations: pairplot, correlation heatmap, histograms.
Identified potential outliers and relationships between features.
3. Data Preparation and Cleaning
Handled missing values by imputing or removing records.
Scaled the data using standardization to bring features to a similar scale.
Removed outliers or made necessary adjustments to make the dataset cleaner.
4. Data Splitting
Split the dataset into training and testing sets using an 80-20 ratio for better generalization of the model.
5. Feature Scaling
Applied normalization and standardization techniques to prepare the data for modeling.
6. Model Selection and Training
Implemented a Linear Regression model using Scikit-learn.
Trained the model on the training dataset and used cross-validation to ensure robustness.
7. Model Evaluation
Evaluated the model using performance metrics such as:
Mean Squared Error (MSE)
Mean Absolute Error (MAE)
R-squared (R²)
8. Prediction
Predicted house prices on the test dataset.
Compared the actual vs predicted values to assess model performance.
9. Data Visualization and Reporting
Visualized the predictions against actual values using plots.
Generated a report summarizing the findings and insights from the data.
Tools & Technologies
Python: Primary programming language
Libraries:
NumPy: Numerical computing
Pandas: Data manipulation
Matplotlib & Seaborn: Data visualization
Scikit-learn: Machine learning library

Jupyter Notebook: For interactive exploration and model building

jupyter notebook
Results
The Linear Regression model was able to predict house prices with an R² score of 0.7, indicating a good fit to the data. However, further improvements could be made by testing more complex models like Random Forest or Gradient Boosting.
# Future Work
Experiment with different algorithms such as Random Forest, Gradient Boosting, or XGBoost to improve prediction accuracy.
Perform hyperparameter tuning to enhance model performance.
Create a dashboard using Tableau to visualize key insights.
# Conclusion
The project successfully demonstrated the process of building a predictive model for house prices using linear regression. The EDA and data preparation steps were crucial in creating a cleaner dataset for modeling, and the evaluation metrics suggest reasonable model performance with potential for further refinement.
