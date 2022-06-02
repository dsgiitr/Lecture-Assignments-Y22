# ML-1 Assignment
Made by: Pranjal Gulati and Aryan Khanuja

## Problem 1:
### Task 1
You task here is to go through [this link](https://www.kaggle.com/datasets/andonians/random-linear-regression) and perform simple linear regression using sklearn.
Then you must submit your work here as well as on the dataset above in kaggle website. Share the link of your notebook on kaggle along with your notebook on github.
 
### Task 2
Apply polynomial regression on [this link](https://www.kaggle.com/datasets/fplandes/covid19-granular-demographics-and-times-series).
Submit your notebook to github as well as kaggle. Share kaggle link.

### Task 3
Go through [this notebook](https://www.kaggle.com/code/shrutimechlearn/step-by-step-assumptions-linear-regression/notebook). 
No need to code :P . Just see why the assumptions to linear regression are important as discussed in the lecture.


## Problem 2:
Pendigits is a handwritten digits dataset. The train set can be accessed [here](http://archive.ics.uci.edu/ml/machine-learning-databases/pendigits/pendigits.tra) and the test set can be accessed [here](http://archive.ics.uci.edu/ml/machine-learning-databases/pendigits/pendigits.tes). The dataset is available as a text file (can be opened in Notepad). 

### Task 1
Your first task is to parse this text based data into a `pandas` dataframe. 

Also, to impress Ajit sir, plot one digit each of label `4`, `0`, `8` using `matplotlib`.


### Task 2
Next, train a logistic classifier on these digits and find the accuracy on the test set. For this, you can use any Python library available 🤟.


### Task 3
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


### Task 4
As in all neural network training, you need to find the optimal values of your hyperparameters.

Plot a graph of test accuracy vs `k` for a lot of values of `k` and decide the best `k`.


### Task 5
Good job until now! But, to decide the hyperparameters using the test accuracy is not the best way. Why?



## Brownie problem
This is a self learning, self paced task.
</br>
Solving this is not compulsory.
You are required to scape data from this [amazon](https://www.amazon.in/s?k=smartphones&rh=p_36%3A900000-1000000&crid=2HWQM77E4E53F&qid=1654178719&rnid=1318502031&sprefix=smartphones+%2Caps%2C210) link.
Scrape relevant features what you think is necessary and predict price of a particular smartphone if we input the features of the smartphone along with the brand. You can use bs4 or any scraper you want.


## How to Submit?
Submit a well-formatted Jupyter Notebook. Use Markdown cells to separate each question and for any explanation that you wish to provide.

Create your notebook inside `ML-1-Submissions/` and name it as `<your>-<name>.ipynb`
