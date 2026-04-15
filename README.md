# ML-LAB-7
# Logistic Regression - Advertising Data Analysis

## Project Overview
This project involves building a **Logistic Regression** model to predict whether or not a particular internet user clicked on an advertisement based on their user features. 

## Dataset
The dataset `advertising.csv` contains the following features:
* **Daily Time Spent on Site**: Consumer time on site in minutes.
* **Age**: Customer age in years.
* **Area Income**: Average income of the geographical area of the consumer.
* **Daily Internet Usage**: Average minutes a day the consumer is on the internet.
* **Ad Topic Line**: Headline of the advertisement.
* **City/Country**: Location information of the consumer.
* **Male**: Gender (Binary: 0 for female, 1 for male).
* **Clicked on Ad**: Target variable (Binary: 0 for no, 1 for yes).

## Workflow
1. **Exploratory Data Analysis (EDA)**: Used `Seaborn` and `Matplotlib` to visualize distributions and correlations (e.g., Age vs. Area Income).
2. **Data Cleaning**: Handled the data to ensure only relevant numerical features were used for the model.
3. **Model Training**: Split the data into training and testing sets ($33\%$ test size) and trained a `LogisticRegression` model.
4. **Evaluation**: Evaluated the model using a Confusion Matrix and a Classification Report.
