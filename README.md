# Spam-detection
Program for detecting spam comments and verifying not spam comments from a bunch of them

## Getting Started

This project has a dataset of supervised comments that specified which comment was spam or not.

We want to learn from this dataset and determine if a new comment we receive is spam or not using Machine Learning.

### Prerequisites

In this project, we use pandas (for data frames, defaultdict (for dictionary), and PersianStemmer (for stemming Persian text) libraries.
First, install these libraries.

For installing these libraries using pip, type these instructions in the python shell:

```
pip install pandas
```

```
pip install defaultdict
```
```
pip install PersianStemmer
```
## problem description
We have a training dataset of Digikala.com comments in bin/train.csv with 160,000 supervised entries.

![train_dataframe](http://s7.picofile.com/file/8387450776/Train_dataframe.png)

Each comment entry consists of id, title, comment, rate, and verification status.
We should detect spam comments by training on train datasets using machine learning solutions.

We will use the "Multinuminal Naive Bayes" algorithm for solving this problem.

And we have a test dataset of comments which doesn't have a verification status column; We should implement it!

![test_dataframe](http://s7.picofile.com/file/8387453742/test_dataframe.png)

It has 20000 comments.

## Multinuminal naive Bayes
* [Worked_Example](https://www.youtube.com/watch?v=OWGVQfuvNMk) - an excellent example of how this algorithm works and is implemented.
