# Smartwatch_dataanalysis_project

This repository contains Python code for analyzing Fitbit data. The analysis is divided into five steps, each focusing on different aspects of the dataset.

## Step 1: Data Summary Statistics

- Use Python to calculate basic summary statistics for key variables in the Fitbit dataset, such as total steps, calories burnt, and active minutes.
- Compute metrics including mean, median, standard deviation, minimum, and maximum for these variables.
- Create visualizations like histograms or box plots to illustrate the distribution of these variables.

## Step 2: Time Series Analysis

- Explore time-related patterns in the Fitbit data by creating time series plots.
- Calculate daily or weekly averages of variables like total steps, distance traveled, or active minutes.
- Utilize Python libraries such as Matplotlib or Seaborn to create line plots or bar charts to visualize how these metrics change over time.

## Step 3: Correlation and Regression Analysis

- Perform correlation analysis to identify relationships between variables, e.g., between the number of steps taken and calories burned.
- Use Python to conduct simple linear regression to predict one variable based on another (e.g., calorie burn based on active minutes or distance traveled).
- Visualize the results of regression analysis, including scatterplots with regression lines and residual plots.

## Step 4: Polynomial Regression for Steps vs. Calories

- Conduct polynomial regression analysis using Python to model the relationship between the number of steps (independent variable) and calories burned (dependent variable).
- Fit polynomial regression models of different degrees (e.g., quadratic, cubic) to capture potential non-linear relationships between these variables.
- Visualize the polynomial regression curves alongside actual data points to assess model fit.
- Evaluate goodness of fit using metrics like R-squared and mean squared error (MSE).

## Step 5: Logistic Regression for Activity Classification

- Convert the Fitbit data into a classification problem by creating a binary variable indicating whether a day was "active" or "sedentary" based on a threshold (e.g., 10,000 steps).
- Use logistic regression in Python to build a predictive model classifying days as active or sedentary based on features like total steps, active minutes, or distance traveled.
- Split data into training and testing sets to evaluate model accuracy, precision, recall, and F1-score.
- Visualize the logistic regression decision boundary and decision probabilities.

## Usage

1. Ensure you have Python and the necessary libraries (e.g., pandas, numpy, seaborn, matplotlib, scikit-learn) installed.
2. Place your Fitbit data file in the same directory as the Python scripts or update the file path in the code.
3. Run each step sequentially for comprehensive analysis.

## License

This project is licensed under the [MIT License](LICENSE).
