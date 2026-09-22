# Cognifyz Restaurant Analysis

## 📌 Project Overview

This project analyzes restaurant data to understand **restaurant ratings, cuisines, pricing, and other factors** affecting restaurant ratings.

This project was completed as part of the **Cognifyz Data Science Internship**.

## 📊 Dataset

* **Rows:** 9,551
* **Columns:** 21
* **Target:** `Aggregate rating`
* **Features:** City, Cuisines, Average Cost for two, Price range, Votes, Latitude, Longitude, etc.

## 🔧 Data Preprocessing

* Loaded and explored the dataset
* Handled missing values
* Removed unnecessary columns
* Removed `Rating color` and `Rating text` to avoid data leakage
* Encoded categorical features
* Selected relevant features
* Split the data into training and testing sets
* Applied feature scaling where required

## 📈 Exploratory Data Analysis

The analysis includes:

* Restaurant distribution by city
* Rating distribution
* Zero-rating restaurants
* Popular cuisines
* Price range analysis
* Average cost for two
* Votes and ratings
* Geographic analysis

## 🤖 Machine Learning

The following regression models were implemented:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor

### Model Performance

| Model             |   MAE |  RMSE | R² Score |
| ----------------- | ----: | ----: | -------: |
| Linear Regression | 1.036 | 1.244 |    0.320 |
| Decision Tree     | 0.276 | 0.433 |    0.918 |
| Random Forest     | 0.191 | 0.293 |    0.962 |

The models were evaluated using **MAE, RMSE, and R² Score**.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

## 📁 Project Structure

```text
Cognifyz_Project/
│
├── Dataset.csv
├── notebook.ipynb
└── README.md
```

## 🎯 Conclusion

This project demonstrates a complete **Data Science and Machine Learning workflow**, including data exploration, preprocessing, visualization, feature engineering, model training, and model evaluation for predicting restaurant ratings.
