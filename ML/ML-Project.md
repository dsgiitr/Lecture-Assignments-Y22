# PROJECT
After a series of lectures on supervised learning, it's time to apply your knowledge on a full fledged ML Pipeline Project. Your project involves a detailed analysis on a dataset.<br>
You have the liberty to choose the dataset you wish.<br>
Some sources of dataset:-<br>
[Kaggle Dataset](https://www.kaggle.com/datasets)<br>
[UCL ML Repo](http://mlr.cs.umass.edu/ml/)<br>
[OpenML](https://www.openml.org/)<br>
Before going forward with any dataset,get that dataset checked by us<br>
# ML Pipeline
A machine learning project goes through various steps before its completed<br>
To give you a feel of the complete pipeline, we give you the project in a sequential manner so that it clarifies your approach towards a ML Project
## Problem Description
Describe the problem you wish to tackle with your dataset. It could be predicting y given x features or classifying one out of c categories.<br>
The description should be proper addressing your views on the impact of that problem, your techniques which you plan and how the solution to that problem could help in the real world.
## Data Analysis
### Step 1
Do some basic data exploration before starting off<br>
— head of the dataset<br>
— the shape of the dataset<br>
— info of the dataset<br>
— summary of the dataset
### Step 2
Identify any missing value present in the dataset or categorical variables in the dataset.
### Step 3
Do a very extensive exploratory data analysis of your dataset giving scatterplots, correlation matrices, lineplots, boxplots, barcharts, Heatmaps<br>

**Give your inference on wherever you can of your analysis**<br>

## Feature Engineering
### Step 1
Impute all the missing values and encode the categorical features identified during data analysis<br>
**Use sklearn for this and not pandas**<br>
Can you state why did i say you this?<br>
Why is this step important in feature engineering?

### Step 2
What are Outliers?<br>
Identify the outliers in the datasets and remove them<br>
Now there are various methods for doing this<br> 
Use any of them

### Step 3
Find skewness in your dataset and provide the method of fixing it<br>
Why was this method used?
### Step 4
Do an extensive feature selection using ANOVA<br>

Note:- This step might be tough for you but it's important so make sure you ask doubts 
### Step 5
Do a train-test split of the dataset<br>
Why is this step important?

## Modeling
### Step 1
Try out all the supervised Machine Learning Algorithms you have learnt so far<br>

Try changing the hyperparameters of all of them to get a feel of how they actually work
### Step 2
Generate scores, using different ML metrices you have studied, for all the models you have trained your data on
### Step 3
Use sklearn's GridSearchCV to find the best model with the best hyperparameters<br>
Can you visualize the top 10 results of Grid-SearchCV using plots?

### Step 4
Visualise the ROC-AUC Curve

# References
Some references to get you clear regarding the steps<br>
Note: These are not complete so don't over-rely on them<br>
https://www.kaggle.com/code/jitabhra/modeling-with-outliers<br>
https://www.kaggle.com/code/caesarmario/survival-prediction-w-various-ml-models
