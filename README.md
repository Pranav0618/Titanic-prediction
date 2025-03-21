# Titanic-prediction
Machine learning model to predict Titanic survival
# 🚢 Titanic Survival Prediction
Project Overview  
This project builds a **Machine Learning model** to predict whether a passenger survived the **Titanic disaster** based on features like age, gender, class, fare, etc.  

 Dataset  
- **train.csv** → Used for model training.  
- **test.csv** → Used for predictions.  

Data Preprocessing  
1. **Handling Missing Values** → Filled missing `Age` values with median, removed `Cabin` column.  
2. **Encoding Categorical Variables** → Converted `Sex` and `Embarked` to numerical values.  
3. **Feature Scaling** → Standardized `Age` and `Fare`.  

Model Selection  
Trained multiple models and selected the best based on performance:  
Logistic Regression  
Random Forest (Final Model)  
XGBoost  


git clone https://github.com/Pranav0618/Titanic-Prediction.git
cd Titanic-Prediction
