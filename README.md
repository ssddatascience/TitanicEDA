# TitanicEDA
# Project Description
Titanic Dataset – 
It is one of the most popular datasets used for understanding machine learning basics. It contains information of all the passengers aboard the RMS Titanic, which unfortunately was shipwrecked. This dataset can be used to predict whether a given passenger survived or not. 

To do the same we will use the Pandas,Seaborn and Matplotlib library.

## Data

We can download the dataset from https://www.kaggle.com/c/titanic/data.

## Storytelling:

Let us try to understand the dataset first. It has 12 columns.

Here we have 11 features using which we shall predict the target variable which is ‘Survived’.

The target variable is the one which we are trying to predict. Others are the features. Our first step would be to polish the features so that it can be used to input to a machine learning model which we can use to do our required task.

## What is EDA?

Exploratory Data Analysis (EDA) is a method used to analyze and summarize datasets. Majority of the EDA techniques involve the use of graphs.

## Methodology

The analysis of the titanic dataset will include several steps, including data cleaning and preprocessing, descriptive statistics, and data visualization. Some of the techniques that will be used in this project include:

Scatter plots
Histograms
Box plots
Correlation analysis

## Features: The titanic dataset has roughly the following types of features:

Categorical/Nominal: Variables that can be divided into multiple categories but having no order or priority. 

Eg. Embarked (C = Cherbourg; Q = Queenstown; S = Southampton)

Binary: A subtype of categorical features, where the variable has only two categories. 

Eg: Sex (Male/Female)

Ordinal: They are similar to categorical features but they have an order(i.e can be sorted). 

Eg. Pclass (1, 2, 3)

Continuous: They can take up any value between the minimum and maximum values in a column. 

Eg. Age, Fare

Count: They represent the count of a variable. 

Eg. SibSp, Parch

**Useless: They don’t contribute to the final outcome of an ML model. Here, PassengerId, Name, Cabin and Ticket might fall into this category.**

## Estimators Inspect the Titanic Dataset using Python

The TensorFlow Estimator API is a high-level interface that simplifies the process of training and evaluating machine learning models in TensorFlow. It provides pre-built model architectures and optimization algorithms, as well as tools for input preprocessing, evaluation, and serving.

To use the Estimator API, you first need to define the model architecture and the input and output functions. The model architecture is defined using feature columns, which specify the type and shape of the input data. The input function is responsible for reading and preprocessing the training or evaluation data, and the output function is responsible for defining the loss function and evaluation metrics.

Once the model and input/output functions are defined, you can use the Estimator API to train and evaluate the model. Training the model involves providing the input function to the train() method and specifying the number of training steps. Evaluation involves providing the input and output functions to the evaluate() method and specifying the number of evaluation steps.

The Estimator API also provides tools for making predictions on new data, such as the predict() method, which allows you to pass a test dataset to the model and get predictions for each example.
Overall, the TensorFlow Estimator API is a powerful and convenient tool for training and evaluating machine learning models in TensorFlow. It provides a simple, high-level interface that handles many of the low-level details of model training and evaluation, making it easier to focus on the core machine-learning tasks.

Python libraries make it very easy for us to handle the data and perform typical and complex tasks with a single line of code.

**Pandas** – This library helps to load the data frame in a 2D array format and has multiple functions to perform analysis tasks in one go.

**Matplotlib** – This library is used to draw visualizations.

**TensorFlow** – This is an open-source library that is used for Machine Learning and Artificial intelligence and provides a range of functions to achieve complex functionalities with single lines of code.

## Conclusion :  

The columns that can be dropped are: 
PassengerId, Name, Ticket, Cabin: They are strings, cannot be categorized and don’t contribute much to the outcome. 
Age, Fare: Instead, the respective range columns are retained.


The titanic data can be analyzed using many more graph techniques and also more column correlations.

Once the EDA is completed, the resultant dataset can be used for predictions.
