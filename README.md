# Titanic Survival Prediction 🚢

## Project Overview

This project focuses on predicting whether a passenger survived the Titanic disaster using Machine Learning classification techniques.

The model is trained using the Titanic dataset from the Kaggle competition. The project involves data cleaning, exploratory data analysis (EDA), feature engineering, and building a Decision Tree Classifier.

## Dataset

- **Source:** [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic)
- **Training Dataset:** `train.csv`
- **Testing Dataset:** `test.csv`
- **Target Variable:** `Survived`
  - `0` = Did not survive
  - `1` = Survived

## Technologies & Libraries

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow

1. **Data Loading:** Imported the Titanic training and testing datasets using Pandas.
2. **Data Cleaning:** Handled missing values and removed unnecessary columns.
3. **Exploratory Data Analysis (EDA):** Analyzed passenger survival based on gender, age, passenger class, and other features.
4. **Feature Engineering:** Created meaningful features and converted categorical variables into numerical representations.
5. **Model Building:** Implemented a Decision Tree Classifier using Scikit-learn.
6. **Model Evaluation:** Evaluated the model using accuracy score.
7. **Kaggle Submission:** Generated predictions for the test dataset and submitted them to Kaggle.

## Model Performance

| Evaluation Metric | Score |
|---|---:|
| Local Test Accuracy | 77.78% |
| Kaggle Public Leaderboard Score | 0.71770 (71.77%) |

**Algorithm Used:** Decision Tree Classifier

## Repository Structure

```text
Titanic-Survival-Prediction/
├── data/
│   ├── train.csv
│   └── test.csv
├── Titanic_Survival_Prediction.ipynb
├── submission.csv
└── README.md
```

## Key Learnings

- Understanding the Machine Learning workflow.
- Handling missing values and categorical variables.
- Performing Exploratory Data Analysis.
- Feature engineering and data preprocessing.
- Implementing classification algorithms using Scikit-learn.
- Evaluating model performance.
- Making predictions and submitting results to Kaggle.

## Future Improvements

- Implement Logistic Regression and Random Forest.
- Perform hyperparameter tuning using GridSearchCV.
- Apply cross-validation.
- Improve feature engineering.
- Compare different classification algorithms.

## Kaggle Competition

[View Titanic Competition on Kaggle](https://www.kaggle.com/competitions/titanic)

---

**Author:** Ronak Hussain

**GitHub:** [ronakhussain](https://github.com/ronakhussain)

*This project is part of my Machine Learning learning journey.*
