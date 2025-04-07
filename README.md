# Time-Series-Sales-Forecasting
🔍 Project Overview
The dataset contains simulated time series data spanning 10 years (2010–2019), including features like date, store_id, product_id, and number_sold.

* train.csv: Covers 2010–2018

* test.csv: Covers 2019

* 7 unique stores

* 10 unique products

* No missing values

🎯 Goal: Predict the number_sold feature in the test set.
📊 Data source: https://www.kaggle.com/datasets/samuelcortinhas/time-series-practice-dataset

My Solution Includes Three Key Steps:

✅ Part 1 – Data Loading & Analysis
Started by loading the CSV files, followed by statistical analysis and visualizations to better understand the story behind the data.

✅ Part 2 – Dataset Creation
Transformed raw time series data into sequences of 30 features using a custom Python function. There are several ways to approach this, but I opted for a simple, manual method to fully grasp the concept.

✅ Part 3 – Modeling & Evaluation
Used a basic fully connected neural network built with TensorFlow. After preparing the test dataset, I predicted results and evaluated the model using MAE and MAPE metrics.
