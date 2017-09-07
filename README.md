# titanic-data-analysis

## Data Analysis and Prediction of Survivors on the Titanic Dataset

Overview

This study is an exercise to show how to use foundations of Data Science in order to import, study, visualize, 
and present the raw data in a method that is easy for any user to digest and understand.

This study uses passenger data from the ill-fated maiden voyage of the RMS Titanic (1912). 
The data (and explanation of the data) can be obtained from: https://www.kaggle.com/c/titanic/data

First, the raw comma separated values (.cvs) data will be loaded into a Python (NumPy) series.

Second, there will be some data exploration. This will be completed mostly by loading plots of 
different data slices in order to better understand the data with visualization. Visualizing the data 
makes generating a hypothesis easier.

Third, the data will be analyzed.

Lastly, a prediction model using two algorithms is used to predict how accurate the models work on the 
titanic dataset and a confusion matrix is plot to clearly see the obtained results. This model has been 
created to see the chances of surviving the Titanic disaster.

Note:
This is a Jupyter iPython Notebook. It allows code to be written, code output to be displayed, and also markup. 
It allows the analysis to be conducted and displayed. Comments that are intended for a general audience are 
presented in markup 'plain' text below each code segment. Comments that have to do with how the code works are 
above the code with a leading hashtag(#). However, due to the heavy display of Python code; it is not suitable 
for all audiences. For example, if I were presenting my analysis to upper management, board of directors, a 
general audience, etc. I would not use this Notebook. I'd have much of the output in a PowerPoint type presentation. 
However, I would have the Jupyter Notebook available as a supplement, in case anyone wanted to see the code. 
Or, more importantly, the amount of work it took to create the pretty graphics.

The data has been split into two groups:

training set (train.csv) test set (test.csv) 

The training set should be used to build your machine learning models.

For the training set, we provide the outcome (also known as the “ground truth”) for each passenger. 

The model will be based on “features” like passengers’ gender and class. One can also use feature engineering 
to create new features.

The test set should be used to see how well your model performs on unseen data. 

For the test set, we do not provide the ground truth for each passenger.
For each passenger in the test set, use the model you trained to predict whether or not they survived the 
sinking of the Titanic.
