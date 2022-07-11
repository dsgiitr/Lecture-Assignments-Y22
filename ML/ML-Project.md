# Project
After a series of lectures on supervised learning, it's time to apply your knowledge on a full-fledged ML Pipeline Project. Your project involves a detailed analysis on a dataset.

You can choose from these datasets:
- [Factors affecting Campus Placements](https://www.kaggle.com/datasets/benroshan/factors-affecting-campus-placement)
- [Credit Card Dataset](https://www.kaggle.com/datasets/rikdifos/credit-card-approval-prediction)
- [Titanic Passenger Data](https://www.kaggle.com/c/titanic/)
- [Dry Beans Dataset](https://archive.ics.uci.edu/ml/datasets/Dry+Bean+Dataset)
- [Factors influencing Life Expectancy](https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who)

It does not matter what performance you get on the dataset, the thing that matters the most is your approach. So, keep it original.

# ML Pipeline
A machine learning project goes through various steps before it's completed. Designing a pipeline is a critical part of any Data Science project. Here are some steps:

- [Describe the problem](#Problem-Description)
- [Analyze the Data](#Data-Analysis)
- [Feature Engineering](#Feature-Engineering)
- [Model the Data](#Modelling)
- <b>Predict!!</b>

## Problem Description
- Describe the problem you wish to tackle with your dataset. For example, it could be predicting y given x features or classifying one out of c categories.
- The description should be properly addressing your views on the impact of that problem, your techniques which you plan, and how the solution to that problem could help in the real world.

## Data Analysis
### Step 1: Exploration
- Print the first few rows(head) of the dataset.
- Find out about the dataset using the ```pandas.DataFrame.info()``` method. 
- Column-wise statistical summary of the dataset. Use the ```pandas.DataFrame.describe()``` method.
### Step 2: Cleaning
- Identify any missing, duplicate, inconsistent entries in the dataset.
- Come up with a strategy to handle these cases.
### Step 3: Plotting
- Plotting the data can provide with great visual insight into the data, which can help you understand and model it better.
- Try to plot your data using different types of plots, e.g., scatterplots, correlation matrices, lineplots, boxplots, barcharts, heatmaps, etc.

There are other things you can do as well, remember to <b>use the internet</b> well.

## Feature Engineering
### Step 1: Imputing and Encoding
Impute all the missing values and encode the categorical features identified during data analysis.

<b>Instructions:</b>
- Use ```sklearn``` instead of```pandas``` for this.
- Think about: 
    - Why ```sklearn``` and not ```pandas```?
    - Why is this step important in feature engineering?

### Step 2: Outliers
- Identify the outliers in the datasets.
- Come up with a strategy to remove these outliers.
- Think about why it is necessary to remove these outliers.

### Step 3: Skewness
- Detect skewness, if there, in your data.
- Come up with a strategy to neutralize this skewness.
- Think about why you did what you did.

### Step 4: Feature Selection
- Select features with the most information using ```ANOVA```.
- Think about why feature selection is important. Does training a model with features that don't tell contribute anything to the model's prediction have any disadvantage?

<b>Note:</b> These steps and there pointers are merely suggestions, remember to <i>use the internet</i> and use methods that are relevant to you.

## Modelling
### Step 1: No free lunch
- There is no single Machine Learning model that performs the best on all datasets, just like there's no free lunch.
- To find out the model that performs the best on your dataset, you'll have to try and test various models and then compare them.
- Just use the models you have studied, and train them using ```sklearn.model.fit()```

### Step 2: Hyperparameter Tuning
- Use ```sklearn.model_selection.GridSearchCV``` to find the best model with the best hyperparameters.

### Step 3: Model Analysis
- Generate scores, using different ML metrices you have studied, for all the models you have trained your data on.
- Analyze the performance on the Validation set.
- Generate scores, using different ML metrices you have studied, for all the models you have trained your data on.
- Perform Cross-Validation.

# References
- [Modelling with Outliers](https://www.kaggle.com/code/jitabhra/modeling-with-outliers)
- [Survival Prediction using various ML Models](https://www.kaggle.com/code/caesarmario/survival-prediction-w-various-ml-models)

<b>Note</b>: You can refer to these, but remember to, once again, <i>use the internet</i> to find out methods that best suit your use case.