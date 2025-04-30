# Calorie Burn Prediction Using Machine Learning and SHAP

This project predicts the number of calories burned during exercise and Top contributing features (in %) based on input features.
It compares multiple regression models and provides a GUI interface

##  Features
- Regression model comparison (XGBoost, Linear, Ridge, Lasso)
- SHAP explainability for model interpretation
- Interactive desktop GUI using Tkinter
- Feature importance visualization for user input

##  Technologies Used
- Python
- XGBoost, scikit-learn
- SHAP
- Tkinter (GUI)
- Pandas, Matplotlib, Seaborn

##  Machine Learning
- Model tuning via GridSearchCV
- Performance metrics: MAE, MSE, RMSE
- Feature scaling with MinMax normalization


##  GUI Preview
The Tkinter interface allows users to input:
- Gender
- Age
- Height
- Weight
- Duration
- Heart Rate
- Body Temperature

...and get:
- Calories burned (in kcal)
- Top contributing features (in %)
