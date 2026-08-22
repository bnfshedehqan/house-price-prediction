# 🏠 House Price Prediction

A beginner-friendly Machine Learning project for predicting house prices using the California Housing dataset.

This project is designed to practice the complete Machine Learning workflow, from data exploration and visualization to preprocessing, model training, and evaluation.

---

## 🎯 Project Overview

The goal of this project is to build a Machine Learning model that can predict the **median house value** of a district in California based on different demographic, geographic, and housing-related features.

The project focuses not only on building a predictive model, but also on understanding the steps involved in a typical Machine Learning project.

---

## 📊 Dataset

This project uses the **California Housing Dataset**.

The dataset contains information about different housing districts in California.

### Features

| Feature              | Description                            |
| -------------------- | -------------------------------------- |
| `longitude`          | Longitude of the housing district      |
| `latitude`           | Latitude of the housing district       |
| `housing_median_age` | Median age of houses in the district   |
| `total_rooms`        | Total number of rooms                  |
| `total_bedrooms`     | Total number of bedrooms               |
| `population`         | Population of the district             |
| `households`         | Number of households                   |
| `median_income`      | Median income of households            |
| `ocean_proximity`    | Proximity of the district to the ocean |
| `median_house_value` | Median house value                     |

### Target Variable

**median_house_value**

The target variable represents the median house value for each housing district.

---

## 🧠 Machine Learning Problem

This is a **Supervised Learning** problem.

More specifically, it is a **Regression** problem because the model predicts a continuous numerical value.

### Input

Housing, demographic, and geographic features.

### Output

Predicted median house value.

---

## 🛠️ Technologies & Libraries

The project is developed using:

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📁 Project Structure

```
house-price-prediction/
│
├── data/
│   └── housing.csv
│
├── house_price_prediction.ipynb
│
├── requirements.txt
│
├── .gitignore
│
└── README.md
```

The `.venv/` directory is used as the local Python virtual environment and is intentionally excluded from Git.

---

## 🔄 Machine Learning Workflow

The project follows an end-to-end Machine Learning workflow.

### 1. Data Loading

Load the dataset into a Pandas DataFrame.

### 2. Data Exploration

Understand the structure and basic characteristics of the dataset.

This includes:

* Number of rows and columns
* Column names
* Data types
* Statistical information
* Sample records

### 3. Data Quality Analysis

Check the dataset for:

* Missing values
* Duplicate records
* Incorrect data types
* Potential inconsistencies

### 4. Exploratory Data Analysis

Analyze relationships between features and the target variable.

This includes:

* Distribution analysis
* Feature relationships
* Correlation analysis
* Data visualization

### 5. Data Preprocessing

Prepare the dataset for Machine Learning models.

Possible preprocessing steps include:

* Handling missing values
* Encoding categorical variables
* Feature scaling
* Feature transformation

### 6. Feature Engineering

Create or transform features when necessary to improve the performance of the Machine Learning models.

### 7. Train/Test Split

Split the dataset into training and testing sets.

The training set is used to train the model, while the testing set is used to evaluate its performance on unseen data.

### 8. Model Training

Train different regression models and compare their performance.

Potential models include:

* Linear Regression
* Decision Tree Regression
* Random Forest Regression
* Other regression algorithms

### 9. Model Evaluation

Evaluate the models using appropriate regression metrics, such as:

* MAE (Mean Absolute Error)
* MSE (Mean Squared Error)
* RMSE (Root Mean Squared Error)
* R² Score

### 10. Model Comparison

Compare the trained models based on their evaluation results and identify the best-performing approach.

---

## 📈 Exploratory Data Analysis

The Exploratory Data Analysis phase is used to understand the dataset before building Machine Learning models.

Some of the questions explored during this phase include:

* How are house prices distributed?
* Which features have the strongest relationship with house prices?
* Are there missing values?
* Are there duplicate records?
* Are there potential outliers?
* How does median income relate to house prices?
* Does geographic location affect house prices?

---

## 🤖 Models

The following regression models will be explored during the project:

| Model                   | Status     |
| ----------------------- | ---------- |
| Linear Regression       | 🔄 Planned |
| Decision Tree Regressor | 🔄 Planned |
| Random Forest Regressor | 🔄 Planned |

Additional models may be added as the project develops.

---

## 📊 Evaluation Metrics

Because this is a regression problem, model performance will be evaluated using regression metrics.

### MAE

Mean Absolute Error measures the average absolute difference between the actual and predicted values.

### MSE

Mean Squared Error calculates the average squared difference between actual and predicted values.

### RMSE

Root Mean Squared Error is the square root of MSE and provides the error in the same unit as the target variable.

### R² Score

R² measures how well the model explains the variance in the target variable.

---

## 📌 Current Status

**Project Status: In Progress 🚧**

### Completed

* [x] GitHub repository created
* [x] Python virtual environment created
* [x] Project dependencies installed
* [x] `requirements.txt` created
* [x] `.gitignore` created
* [x] Jupyter Notebook created
* [x] Dataset added
* [x] Dataset loaded into Pandas
* [x] Initial dataset exploration completed
* [x] Exploratory Data Analysis
  
### In Progress

* [ ] Data visualization
* [ ] Data preprocessing
* [ ] Feature engineering
* [ ] Train/Test split
* [ ] Model training
* [ ] Model evaluation
* [ ] Model comparison
* [ ] Final predictions

---

## 🎓 Learning Objectives

The main purpose of this project is to build practical experience with Machine Learning.

Through this project, I aim to strengthen my understanding of:

* Python for Data Science
* Pandas
* NumPy
* Data Cleaning
* Exploratory Data Analysis
* Data Visualization
* Feature Engineering
* Supervised Learning
* Regression
* Model Training
* Model Evaluation
* Scikit-learn
* End-to-End Machine Learning workflows

---

## 🚀 Future Improvements

Possible future improvements include:

* Hyperparameter tuning
* Cross-validation
* Feature selection
* Advanced regression models
* Model comparison and optimization
* Error analysis
* Improving prediction performance
* Saving the final trained model
* Creating a simple prediction interface

---

## 📚 What I Am Learning

This project is part of my practical Machine Learning learning path.

The focus is on understanding **why** each step is performed rather than simply applying Machine Learning algorithms.

The project will gradually evolve from a basic regression model into a more complete Machine Learning project.

---

## 👤 Author

**Banafshe Dehqan**

GitHub: https://github.com/bnfshedehqan

---

## 📄 License

This project is intended for educational and learning purposes.
