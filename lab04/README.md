Titanic Survival Prediction 

Overview

This project demonstrates the application of two machine learning classifiers—k-Nearest Neighbors (k-NN) and Decision Tree—on the Titanic dataset to predict passenger survival. The dataset contains various features like passenger class, age, sex, and fare, which help build predictive models. The code also visualizes decision boundaries based on selected features.

Dataset

The dataset used is the famous Titanic dataset, which contains information on passengers, including their demographics, travel class, and survival status. This dataset is publicly available on GitHub.

Dataset URL: Titanic Dataset

Key Steps

Data Loading:
Load the Titanic dataset using Pandas.
Display the first few rows to understand the structure of the data.
Data Exploration:
Check for missing values in the dataset.
Visualize key features, such as Passenger Class, Age, and Sex distributions.
Data Preprocessing:
Handle missing values by filling them with the median or mode where applicable.
Drop unnecessary columns like 'Cabin' due to excessive missing data.
Encode categorical variables ('Sex' and 'Embarked') for model training.
Standardize numerical features ('Age' and 'Fare') using StandardScaler.
Model Training:
Define features (X) and target (y) for prediction.
Split the data into training (70%) and testing (30%) sets.
Train two machine learning models: k-NN and Decision Tree.
Model Evaluation:
Evaluate both models using accuracy, precision, recall, and F1 score.
Decision Boundary Visualization:
Plot decision boundaries for the models using 'Pclass' and 'Age' as features to visualize how the models separate survivors and non-survivors.
