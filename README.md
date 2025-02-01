# Titanic-Survival-Prediction
Using Decisicion Tree Classifier to predict Titanic Survival

# Titanic Survival Prediction

## Overview
This project implements a machine learning model to predict the survival of passengers on the Titanic using a Decision Tree Classifier. The model analyzes various passenger attributes to determine their likelihood of survival.

## Technologies Used
- **Python**: The programming language used for this project.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Scikit-learn**: For implementing machine learning algorithms.
- **Jupyter Notebook**: For interactive coding and visualizations.

## Dataset Overview
The dataset used in this project is the Titanic dataset, which contains the following features:
- **PassengerId**: Unique identifier for each passenger.
- **Survived**: Survival status (0 = No, 1 = Yes).
- **Pclass**: Ticket class (1st, 2nd, or 3rd).
- **Name**: Name of the passenger.
- **Sex**: Gender of the passenger.
- **Age**: Age of the passenger.
- **SibSp**: Number of siblings/spouses aboard.
- **Parch**: Number of parents/children aboard.
- **Ticket**: Ticket number.
- **Fare**: Fare paid for the ticket.
- **Cabin**: Cabin number.
- **Embarked**: Port of embarkation (C = Cherbourg; Q = Queenstown; S = Southampton).

## Analysis Steps
1. **Data Loading**: Load the dataset using Pandas.
2. **Data Exploration**: Analyze the dataset for missing values and perform initial descriptive statistics.
3. **Data Preprocessing**:
   - Fill missing age values with the mean.
   - Encode categorical variables (e.g., map `Sex` to numerical values).
   - Define independent (`X`) and dependent (`y`) variables.
4. **Train-Test Split**: Split the dataset into training and testing sets.
5. **Model Creation**: Create and train a Decision Tree Classifier on the training data.
6. **Model Evaluation**: Evaluate the model's performance using a confusion matrix and accuracy score.

## Results
The model's performance was evaluated on the test set, yielding the following results:
- **Confusion Matrix**:
[[130 27]
[ 37 74]]

- **Accuracy**: Approximately 76.12%.

## Conclusion
The Decision Tree Classifier was able to predict Titanic survival with a reasonable accuracy of 76.12%. This project highlights the importance of data preprocessing and feature engineering in building effective machine learning models. Future work could include experimenting with different algorithms, hyperparameter tuning, and further feature exploration to improve model performance.


