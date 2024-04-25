# **Advanced Machine-Learning Course Repository**

Welcome to my GitHub repository dedicated to showing my work in the Advanced Machine Learning course (CSST 104) during the academic year 2023-2024. 

# **About Me**
**Name:** Marivient Alexia R. Yurag

**Age:** 21 years old

**Course:** Bachelor of Science in Computer Science - Section 3B

**Education:** Laguna State Polytechnic University - Sta. Cruz Campus

**Academic Year:** 2023 - 2024

**Instructor:** Mark P. Bernardino, MSCS

# **Overview**

This repository serves as a compilation of my tasks and assessments taken throughout the course. The focus is on practical applications using Python as the primary programming language and Google Colab as the integrated development environment (IDE). Through real-life examples, I explore various concepts such as linear regression, forecasting, time series analysis using the ARIMA Model, and predictive analysis, providing insights into their applications and implementation.

# **Structure:**
**Programming Language Used:** Python

**IDE:** Google Colaboratory

*Essential Python Libraries for data analysis, visualization, machine learning, and statistical modeling, enabling a wide range of analyses and forecasts:*

- **pandas:** Used for data manipulation and analysis, including reading and writing data, and handling missing values.

- **matplotlib.pyplot:** Used for creating visualizations and plots, such as line plots, histograms, and pie charts.

- **seaborn:** A data visualization library based on matplotlib, used for creating more aesthetically pleasing and informative statistical graphics.

- **scikit-learn (sklearn):** Used for machine learning tasks, including model selection, preprocessing, evaluation, and more.

- **statsmodels: ** A library for estimating and interpreting statistical models, including time series analysis, such as ARIMA models.

- **numpy:** Fundamental package for scientific computing with Python, providing support for large, multi-dimensional arrays and matrices, along with mathematical functions to operate on these arrays.

- **LabelEncoder from sklearn.preprocessing:** Used for encoding categorical features as integer values.

- **SimpleImputer from sklearn.impute:** Used for handling missing values by imputing them with median values.

# **Table of Contents:**
1.  <a href="Exercise 1/3B_YURAG_EXER1.ipynb">Data Analysis</a>

2. <a href="Exercise 2/3B_YURAG_EXER2.ipynb">Student Performance Analysis</a>

3. <a href="Exercise 3/3B_YURAG_EXER3.ipynb">Hardware Store Analysis</a>

4. <a href="Exercise 4/3B_YURAG_EXER4.ipynb">Simple Linear Regression</a>

4.1 <a href="Exercise 4/3B_YURAG_EXER4_Sample_Exer.ipynb">Simple Linear Regression - Sample Exercise</a>

5. <a href="Exercise 5/3B_YURAG_EXER5.ipynb">Multiple Linear Regression</a>

5.1 <a href="Exercise 5/3B_YURAG_EXER5_Sample_Exer.ipynb">Multiple Linear Regression - Sample Exercise</a>

6. <a href="Exercise 6/3B_YURAG_EXER6_Assessment.ipynb">Logistic Regression - Assessment</a>

6.1 <a href="Exercise 6/3B_YURAG_EXER6_Activity.ipynb">Logistic Regression - Activity</a>

7. <a href="Exercise 7/3B_YURAG_EXER7_Assessment.ipynb">Time Series Analysis with Arima Model - Assessment</a>

7.1 <a href="Exercise 7/3B_YURAG_EXER7_Sample_Exer.ipynb">Time Series Analysis with Arima Model - Activity</a>

8. <a href="Exercise 8/3B_YURAG_EXER8.ipynb">Pollution Data Time Series Analysis Using ARIMA Model- Assessment</a>

9. <a href="MIDTERM/3B_YURAG_MIDTERM.ipynb">Forecasting with ARIMA Model - MIDTERM</a>

# **1. Data Analysis**
This source code is a Python script for data analysis. It uses the Pandas library for data manipulation and matplotlib for data visualization. The source code loads a CSV file containing sales data, performs various analysis such as calculating total revenue for each product and average quantity sold per day, and generates an analysis report. Additionally, it creates a visual representation of product revenues. The report includes key insights such as the product generating the highest revenue and the average daily sales volume. Finally, it saves the report to a text file for further reference or sharing.

# **2. Student Performance Analysis**
This code focuses on exploratory data analysis (EDA) of student performance data. It begins by generating a synthetic dataset containing information such as student ID, gender, study hours, test scores, and attendance. After exporting this dataset to a CSV file, the script reads it back in and conducts EDA using matplotlib and seaborn. Visualizations include histograms illustrating the distributions of test scores and study hours, scatter plots showing the relationship between study hours and test scores, gender distribution, and trend analysis of test scores over time. Then, it generates a correlation heatmap to explore relationships between variables.

# **3. Hardware Store Analysis**
This code conducts exploratory data analysis (EDA) on a dataset containing information about products in a hardware store. It loads the dataset, computes basic statistics, and explores categorical variables' unique categories and counts. Visualizations include bar charts displaying product distribution across categories, histograms depicting the distribution of list prices and country names, and scatter plots illustrating relationships between prices, quantities, and categories. Additionally, it identifies insights such as the product with the highest price, and analyzes cost and price averages. The code generates an analysis report summarizing findings and insights, facilitating understanding and decision-making regarding the hardware store's operations.

# **4. Simple Linear Regression**
These two source codes show the implementation of simple linear regression using Python's scikit-learn library. The first code loads a dataset containing student grades, visualizes relationships between variables using scatter plots, and then fits a linear regression model to predict grades based on previous exam scores. It demonstrates how to create, train, and visualize the model's predictions. The second code generates random data points, creates a scatter plot, fits a linear regression model to the data, and predicts new values. Both scripts showcase the process of building and applying linear regression models for predictive analysis, highlighting their simplicity and effectiveness in modeling linear relationships between variables.

# **5. Multiple Linear Regression**
These two source codes demonstrate the implementation of multiple linear regression using Python's scikit-learn library. The first script generates random data points and then fits a linear regression model to predict the model. It demonstrates how to create and train the model's predictions. The second script generates a dataset of student's performance that fits a linear regression model to the data and predicts new values. Both scripts showcase the process of building and applying linear regression models for predictive analysis, highlighting their simplicity and effectiveness in modeling multiple linear relationships between variables.

# **6. Logistic Regression**
These source codes demonstrate the implementation of logistic regression for different predictive tasks.

The first script focuses on predicting survival on the Titanic based on various features such as class, gender, age, and fare. It preprocesses the data, splits it into training and test sets, fits a logistic regression model, and evaluates its performance using accuracy, confusion matrix, and classification report.

The second script predicts feedback on online food orders using demographic and socioeconomic features. It preprocesses the data, visualizes relationships between variables, fits a logistic regression model, evaluates its performance, and explores feature importance and prediction insights.

The third script predicts student performance in math based on other academic scores and demographic factors. It preprocesses the data, creates dummy variables for categorical features, scales the data, fits a logistic regression model, and evaluates its performance using accuracy, confusion matrix, and classification report.

# **7. Time Series Analysis with ARIMA Model**
The first source code focuses on time series analysis using the ARIMA (AutoRegressive Integrated Moving Average) model. It loads a dataset containing monthly sales of shampoo over three years, preprocesses the data, visualizes the sales trend over time, decomposes the time series into its components (trend, seasonality, and residual), performs stationarity testing using the Augmented Dickey-Fuller (ADF) test, fits an ARIMA model to the data, makes forecasts, and visualizes historical sales alongside forecasted values.

The second source code revolves around analyzing the Netflix user base. It loads a dataset containing user subscription information, preprocesses the data, performs exploratory data analysis (EDA) including descriptive statistics and visualizations, builds a linear regression model to predict monthly revenue based on user age, evaluates the model's performance using R-squared and RMSE metrics, and then applies logistic regression to predict user feedback on the platform, evaluating its performance using accuracy, precision, recall, F1-score, and confusion matrix. Then, it explores feature importance for both regression and classification models and provides insights based on visualizations.

These scripts shows practical applications of statistical and machine learning techniques for analyzing time series data and user behavior, providing valuable insights for business decision-making.

# **8. Pollution Data Time Series Analysis Using ARIMA Model**
This source code pertains to time series analysis of pollution data using the ARIMA (AutoRegressive Integrated Moving Average) model. It begins by loading pollution data for various countries and simulating trends over time. Next, it conducts stationarity testing, and autocorrelation analysis, and identifies model parameters (p, d, q) for the ARIMA model. After fitting the model, it evaluates its performance using mean squared error (MSE). Finally, it forecasts pollution levels for the next two years and constructs confidence intervals for the forecast. Visualizations including trend plots, ACF/PACF plots, and forecast plots aid in understanding and interpreting the analysis.

# 9. **Forecasting with ARIMA Model**
This source code focuses on forecasting app ratings using a Linear Regression model and conducting exploratory data analysis (EDA) on Google Play Store data. It begins by cleaning and preprocessing the dataset, including handling missing values, encoding categorical variables, and converting data types. The EDA section visualizes various aspects such as the distribution of app ratings, the proportion of free vs. paid applications, top categories, and relationships between categories and attributes like size and price. Additionally, it analyzes time series trends in average rating, total reviews, and total installs over time. The code concludes with building a Linear Regression model to predict app ratings based on features like reviews, size, installs, type, price, and content rating, followed by model evaluation and correlation analysis between reviews and ratings.

# **Contacts:**

**Facebook: **

Marivient Alexia R. Yurag 

[Facebook Account Link: https://www.facebook.com/MarivientYurag]

**Email Address: **

yuragmarivient@gmail.com

yuragmarivientalexia@icloud.com

