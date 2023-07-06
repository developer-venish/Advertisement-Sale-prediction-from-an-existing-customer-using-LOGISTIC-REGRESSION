# Advertisement-Sale-prediction-from-an-existing-customer-using-LOGISTIC-REGRESSION
ML Python Project

------------------------------------------------------------------------------------
# Preview

![](https://github.com/developer-venish/Advertisement-Sale-prediction-from-an-existing-customer-using-LOGISTIC-REGRESSION/blob/main/Demo.png)

-----------------------------------------------------------------------------------

All the code in this project has been tested and run successfully in Google Colab. I encourage you to try running it in Colab for the best experience and to ensure smooth execution. 
Happy coding!

# Explanation :

The code provided performs the following steps:

1. Imports necessary libraries: `pandas` for loading the dataset and `Google Colab` for uploading files.
2. Uploads a dataset file using `files.upload()` function from Google Colab.
3. Loads the dataset into a pandas DataFrame using `pd.read_csv()` function.
4. Prints the dataset to display its contents.
5. Prints the shape of the dataset, which shows the number of rows and columns.
6. Prints the first 5 rows of the dataset using `dataset.head(5)`.
7. Segregates the dataset into input features (X) and output/target variable (Y) using `.iloc` indexing.
8. Splits the data into training and testing sets using `train_test_split()` function from scikit-learn. The testing set size is set to 25% of the total dataset.
9. Performs feature scaling on the input features using `StandardScaler()` from scikit-learn to standardize the data.
10. Creates an instance of the logistic regression model using `LogisticRegression()` from scikit-learn.
11. Fits the logistic regression model to the training data using `model.fit()`.
12. Prompts the user to enter a customer's age and salary for prediction.
13. Creates a new customer data point using the entered age and salary.
14. Uses the trained model to predict whether the customer will buy or not using `model.predict()`.
15. Prints the prediction result.
16. Outputs whether the customer will buy or not based on the prediction.

This code demonstrates a simple implementation of logistic regression for a binary classification problem, specifically for predicting whether a customer will buy or not based on their age and salary.

-----------------------------------------------------------------------------------

Logistic regression is a statistical algorithm used for binary classification problems, where the goal is to predict a binary outcome variable based on one or more input variables (also known as features or independent variables). It is called "logistic" regression because it uses the logistic function (also known as the sigmoid function) to model the relationship between the input variables and the probability of the binary outcome.

In logistic regression, the input variables are combined linearly using coefficients, and the result is passed through the logistic function, which maps the linear combination to a value between 0 and 1. This value represents the predicted probability of the positive class (often labeled as 1) in binary classification. If the predicted probability is above a certain threshold (typically 0.5), the positive class is predicted; otherwise, the negative class (often labeled as 0) is predicted.

The logistic regression model learns the optimal coefficients (weights) during the training process by minimizing a loss function, such as the log loss or binary cross-entropy. It can handle both numerical and categorical input variables and can be extended to handle multi-class classification problems through techniques like one-vs-rest or softmax regression.

Logistic regression is widely used in various domains, including machine learning, statistics, and social sciences. It is a simple and interpretable model that can provide insights into the relationship between the input variables and the binary outcome.

-----------------------------------------------------------------------------------

