# Used Car Price Prediction 🚗

## 🚀 Project Overview
This project aims to develop predictive models 🧠 to accurately determine the resale value of used cars based on various attributes. Leveraging advanced machine learning techniques, the project assists both sellers in setting competitive prices 💲 and buyers in making informed decisions 🧐.

## 🎥 Project Presentation

Check out the detailed project presentation here:
[View Project Presentation on Canva](https://www.canva.com/design/DAGXIGBHKCI/SNAwOxmoY6D9B0jlcIl8BA/view?utm_content=DAGXIGBHKCI&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=he809e0e73b)

## 📊 Data Description
The data for this project is sourced from the CarDekho website 🌐 and includes comprehensive details about used cars, influencing their market value. The dataset is structured into training, testing, and validation sets to facilitate a thorough analysis and robust model training.

## 🧠 Models Used and Performance Analysis

### Random Forest Regressor 🌲
**Random Forest Regressor** is ideal for this project due to its ability to handle non-linear data with a high dimensionality. It works well for large datasets and provides a good indicator of feature importance derived from the aggregated trees.

### Decision Tree Regressor 🌳
**Decision Tree Regressor** is used for its simplicity and effectiveness in capturing the nonlinear relationships within the data. It's particularly useful for interpretability, which is essential for understanding which features most affect car pricing.

### XGBoost 🚀
**XGBoost** stands out due to its speed and performance as it is an optimized distributed gradient boosting library. It is also effective in avoiding overfitting, making it a solid choice for any model aiming at achieving both high accuracy and generalization.

### Support Vector Regression (SVR) 🔍
**SVR** is used in scenarios where the margin of error is predefined. In the context of car price prediction, SVR can model the complex relationships between features but requires careful tuning of its parameters.

## **Selection of Best Model**
**Model Ranking: Random Forest Regressor > Decision Tree Regressor > XGBoost > Linear Regression - Ridge - Lasso > SVR**

## **Training Data Evaluation**
![Train Accuracy](https://raw.githubusercontent.com/sAwAiRa-iQbal/Used-Cars-Price-Prediction-ML-Project/main/TrainAcc.png)

## **Test Data Evaluation**
![Test Accuracy](https://raw.githubusercontent.com/sAwAiRa-iQbal/Used-Cars-Price-Prediction-ML-Project/main/TestAcc.png)

## **Save Best Model - Random Forest Regressor 94%** 🏆

## **Predicting Price by giving Car features**
![Car Price Predicted](https://raw.githubusercontent.com/sAwAiRa-iQbal/Used-Cars-Price-Prediction-ML-Project/main/CarPricePredicted.png)

## 🛠 Technologies Used
- **Python** 🐍: Primary programming language.
- **Pandas & NumPy** 📊: For data manipulation.
- **Matplotlib, Seaborn & Plotly** 📈: For data visualization.
- **Scikit-Learn** 🤖: For machine learning model development.

This README provides a comprehensive overview, enhancing understanding and accessibility for users who wish to explore the predictive capabilities of machine learning in automotive pricing.
