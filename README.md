# Titanic Survival Prediction 🛳️

This project predicts survival on the Titanic using machine learning models.
Submitted to [Kaggle's Titanic Competition](https://www.kaggle.com/competitions/titanic).
🔗 Download train/test data from Kaggle: [here](https://www.kaggle.com/competitions/titanic/data)


## 🔍 Model Overview
- Preprocessing: Missing value handling, encoding,Feature Engineering
- Models used: Logistic Regression, Decision Tree, Random Forest, XGBoost
- Hyperparameter tuning: GridSearchCV and RandomizedSearchCV
- Final Model: Random Forest (best accuracy on test data)

## 📊 Result
- Kaggle Public Leaderboard Score: **0.75358**
- Outperformed baseline gender model

## 📁 Files
- `titanicprac.ipynb`: Full pipeline in Jupyter
- `submission.csv`: File submitted to Kaggle
- `best_model_rf.pkl`: Trained model (optional)

## 💡 Next Steps
- Add more features like Title, Deck, FareBins
- Try ensemble or stacking methods
