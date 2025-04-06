# Used Car Price Prediction

## 🚀 Project Overview
This project aims to develop predictive models to accurately determine the resale value of used cars based on various attributes. Leveraging advanced machine learning techniques, the project assists both sellers in setting competitive prices and buyers in making informed decisions.

## 📊 Data Description
The data for this project, sourced from the CarDekho website, includes comprehensive details about used cars, influencing their market value. The dataset is structured into training, testing, and validation sets to facilitate a thorough analysis and robust model training.

## 🧠 Models Used and Performance Analysis

### Random Forest Regressor
- **Performance**: Top performer with the best generalization.
- **Metrics**:
  - **R-Square Score**: 0.9413 (explains ~94% of the variance)
  - **MSE & RMSE**: Lowest among the models

### Decision Tree Regressor
- **Performance**: Offers ease of interpretation with robust performance.
- **Metrics**:
  - **R-Square Score**: 0.8926 (explains ~89% of the variance)
  - **MSE & RMSE**: Better than many traditional regressors but not as good as Random Forest.

### XGBoost
- **Performance**: High accuracy with good handling of diverse features.
- **Metrics**:
  - **R-Square Score**: 0.9277 (explains ~93% of the variance)

### Support Vector Regression (SVR)
- **Performance**: Underperforms significantly in this context.
- **Metrics**:
  - **R-Square Score**: -0.0636 (worse than a baseline model)
  - **MSE & RMSE**: Highest among the tested models
  
# **Selection of Best Model**
 
## **Random Forest Regressor > Decision Tree Regressor > XGBoost > Linear Regression - Ridge - Lasso > SVR**

# **Training Data Evaluation**

![Train Data Accuracies](https://raw.githubusercontent.com/sAwAiRa-iQbal/Used-Car-Price-Prediction-Project/main/TrainDataAccuracies.png)

# **Test Data Evaluation**

![Test Data Evaluation](https://raw.githubusercontent.com/sAwAiRa-iQbal/Used-Car-Price-Prediction-Project/main/testDataEvaluation.png)

## **Save Best Model_ Random Forest Regressor 94%**


## 🛠 Technologies Used
- **Python**: Primary programming language.
- **Pandas & NumPy**: For data manipulation.
- **Matplotlib & Seaborn & Plotly**: For data visualization.
- **Scikit-Learn**: For machine learning model development.


