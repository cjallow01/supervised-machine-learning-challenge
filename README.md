# supervised-machine-learning-challenge

In this module's challenge, I built a machine learning model that attempts to predict whether a loan from LendingClub will become high risk or not.


**Background**

Lending services companies allow individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market.
You will be using this data to create machine learning models to classify the risk level of given loans. Specifically, you will be comparing the Logistic Regression model and Random Forest Classifier.


**Instruction**s

**Retrieve the Data**

The data is located in the Challenge Files Folder:
--lending_data.csv
Import the data using Pandas. Display the resulting dataframe to confirm the import was successful.

**Predict Model Performance**

You will be creating and comparing two models on this data: a Logistic Regression, and a Random Forests Classifier. Before you create, fit, and score the models, make a prediction as to which model you think will perform better. You do not need to be correct!
Write down your prediction in the designated cells in your Jupyter Notebook, and provide justification for your educated guess.

**Split the Data into Training and Testing Sets**

Create the features DataFrame, X, by removing the loan_status column. Create y, the labels set, by using the loan_status column. Split the data into training and testing datasets by using the train_test_split function.

**Create, Fit and Compare Models**

Create a Logistic Regression model, fit it to the training data that you created in the previous step. Then, determine the model's score by using the score function and the testing data from the previous step. Do the same for a Random Forest Classifier. You may choose any starting hyperparameters you like.
Review the scores of each model. Which model performed better? How does that compare to your prediction? Write down your results and thoughts in the designated markdown cell.


***My prediction as to Which model i think performed better*** 
Looking at the dataset, I believe that the logistic regression model will perform better for this dataset. With a lot of variables to consider, the Logistic model will win out over the Random Forest model.


***How does that compare to my prediction?***
Based on my research, Random Forest is recommended for simple classification problems.


***Results and thoughts in the designated markdown cell***
Logistic Regression model score = 0.9914878250103177
balanced_accuracy_score = 0.9823995861872097

![This is an image](https://myoctocat.com/assets/images/base-octocat.svg)

***Random Forest Classifier model score***
RandomForestClassifier = 0.991642591828312
balanced_accuracy_score = 0.9515284156142365


![This is an image](https://myoctocat.com/assets/images/base-octocat.svg)

***Conclusion***
I was suprised that Random Forest stayed more consistant and appears by my understand to be the better choice for this dataset in this supervised learning challenge
