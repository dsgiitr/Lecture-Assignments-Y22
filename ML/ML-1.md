# ML-1 Assignment
Made by: Pranjal Gulati and Aryan Khanuja

Pendigits is a handwritten digits dataset. The train set can be accessed [here](http://archive.ics.uci.edu/ml/machine-learning-databases/pendigits/pendigits.tra) and the test set can be accessed [here](http://archive.ics.uci.edu/ml/machine-learning-databases/pendigits/pendigits.tes). The dataset is available as a text file (can be opened in Notepad). 

## Task 1
Your first task is to parse this text based data into a `pandas` dataframe. 

Also, to impress Ajit sir, plot one digit each of label `4`, `0`, `8` using `matplotlib`.


## Task 2
Next, train a logistic classifier on these digits and find the accuracy on the test set. For this, you can use any Python library available 🤟.


## Task 3
Next, you need to use the KNN classifier on this dataset. Use `k = 1`. 

For this, you need to implement your solution as a Python class with the following format:
```python
class KNN:
    def __init__(self, k, ...):
        # initialize data parameters
        ...
        
    def load(self, dataset):
        # store dataset
        ...
        
    def distance(self, p1, p2):
        # calculate L2 distance
        ...
        
    def predict(self, test_point):
        # predict the class of the test_point
        ...
```
Also, make sure to find the accuracy on the test set.


## Task 4
As in all neural network training, you need to find the optimal values of your hyperparameters.

Plot a graph of test accuracy vs `k` for a lot of values of `k` and decide the best `k`.


## Task 5
Good job until now! But, to decide the hyperparameters using the test accuracy is not the best way. Why?


## How to Submit?
Submit a well-formatted Jupyter Notebook. Use Markdown cells to separate each question and for any explanation that you wish to provide.

Create your notebook inside `ML-1-Submissions/` and name it as `<your>-<name>.ipynb`
