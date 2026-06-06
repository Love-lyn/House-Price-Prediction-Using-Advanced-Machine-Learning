# House Price Prediction Using Advanced Machine Learning

## Project Overview

This project was completed as part of Week 5 of the AnalystLab Africa Data Science Internship Program. The objective was to build, compare, and optimize multiple machine learning models for predicting house prices.

## Dataset

House Price Prediction Dataset

The dataset contains housing-related features such as:

* Area
* Bedrooms
* Bathrooms
* Stories
* Parking
* Air Conditioning
* Furnishing Status
* Price (Target Variable)

## Project Workflow

### Data Preparation

* Loaded and explored the dataset
* Handled missing values
* Removed duplicates
* Encoded categorical variables
* Applied feature scaling
* Split data into training and testing sets

### Models Implemented

1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor
4. Gradient Boosting Regressor
5. Tuned Random Forest Regressor (GridSearchCV)

### Evaluation Metrics

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

## Results

| Model               | R² Score |
| ------------------- | -------: |
| Linear Regression   |   0.6529 |
| Decision Tree       |   0.4771 |
| Random Forest       |   0.6119 |
| Gradient Boosting   |   0.6660 |
| Tuned Random Forest |   0.6004 |

### Best Performing Model

Gradient Boosting Regressor

* R² Score: 0.6660
* MAE: 959,749
* RMSE: 1,299,386

## Key Insights

* Gradient Boosting achieved the highest predictive performance.
* Linear Regression performed competitively despite being the baseline model.
* Decision Tree showed the weakest performance.
* Hyperparameter tuning did not improve Random Forest performance in this project.
* Ensemble learning techniques generally outperformed single-tree models.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

## Repository Structure

├── House_Price_Prediction.ipynb
├── Performance_Report.pdf
├── README.md

## Author

Lovelyn Akindileni

Data Science Intern – AnalystLab Africa
