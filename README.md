# Classifying Airline Passenger Satisfaction with CatBoost

This project focuses on predicting airline passenger satisfaction using the CatBoost algorithm. The goal is to classify passengers as either "Satisfied" or "Neutral/Dissatisfied" based on various features such as flight distance, service ratings, and travel class. The project includes data preprocessing, model tuning, and a comparison with other machine learning algorithms like Random Forest and Decision Trees.

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Methodology](#methodology)
4. [Results](#results)
5. [Installation](#installation)
6. [Usage](#usage)
7. [Contributing](#contributing)
8. [License](#license)

## Introduction
In the highly competitive airline industry, understanding and improving passenger satisfaction is crucial for maintaining a competitive edge. This project uses the CatBoost algorithm to classify passenger satisfaction levels and provides insights into the key factors influencing satisfaction. The project also compares CatBoost's performance with other popular algorithms like Random Forest and Decision Trees.

## Dataset
The dataset contains 19 features, including both numerical and categorical variables, such as:
- **Numerical Features**: Age, Flight Distance, Departure/Arrival Delay, Service Ratings (e.g., In-flight Wi-Fi, Seat Comfort).
- **Categorical Features**: Gender, Customer Type, Type of Travel, Class.
- **Target Variable**: Passenger Satisfaction (Satisfied or Neutral/Dissatisfied).

The dataset is provided in a CSV file (`airline_passenger_satisfaction.csv`).

## Methodology
1. **Data Preprocessing**: Handling missing values, encoding categorical features, and feature engineering.
2. **Model Training**: Using CatBoost to build a classification model.
3. **Hyperparameter Tuning**: Optimizing parameters like learning rate, iterations, and tree depth.
4. **Model Comparison**: Comparing CatBoost with Random Forest and Decision Trees.

## Results
- **Best Model**: The hyperparameter-tuned CatBoost model achieved a testing accuracy of **96%**.
- **Key Insights**: Features like In-flight Wi-Fi Service and Type of Travel were identified as the most influential predictors of passenger satisfaction.
- **Comparison**: CatBoost outperformed Random Forest and Decision Trees in terms of cross-validation accuracy.

For detailed results, refer to the project report or the Jupyter notebook provided in the repository.

## Installation
To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/airline-passenger-satisfaction.git
