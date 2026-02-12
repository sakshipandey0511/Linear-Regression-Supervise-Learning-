# Linear-Regression-Supervise-Learning-
This notebook applies simple linear regression for supervised learning on a Salary vs Years of Experience dataset. It loads the CSV, splits data into training and test sets, trains a scikit-learn Linear Regression model, and sets up basic visualization and evaluation of predictions.

# Project overview
This notebook demonstrates a simple supervised learning pipeline using linear regression to predict employee salary from years of experience. It is implemented in Python using scikit-learn within a Kaggle environment and operates on a CSV file named Salary_Data.csv.

# Dataset
    # Source: /kaggle/input/sakshi/Salary_Data.csv.
    #   ​Features: Years of Experience (independent variable).
    # ​Target: Salary (dependent variable).
    #​Environment and libraries: Runs in Kaggle’s Python 3 environment with preinstalled analytics libraries.
    # ​Core libraries: numpy for numerical operations, pandas for data handling, matplotlib.pyplot for plotting, sklearn.model_selection for splitting data, and sklearn.linear_model.LinearRegression for modeling.

# Workflow
1. Load the salary dataset from the Kaggle input directory.
2. ​Separate input feature matrix x (years of experience) and target vector y (salary).
3. ​Split data into training and test sets using train_test_split with a test size of one-third and a fixed random state.
4. ​Initialize and fit a LinearRegression model on the training data (x_train, y_train).
5. ​The fitted model is ready for prediction, visualization of the regression line, and evaluation on test data.

# How to run
1.Open the notebook in Kaggle or a compatible Jupyter environment.

2.​Ensure the Salary_Data.csv file is accessible at the specified path or update the path accordingly.

3.​Run cells sequentially from top to bottom to import libraries, load data, split datasets, and train the model.
