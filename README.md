# Spam-detection
Program for detecting spam comments and verify not spam comments from a bunch of them

## Getting Started

In this project we have a dataset of supervised comments that specified wich comment is spam or not.

we want to learn from this dataset and determine if a new comment we recive is spam or not using Machine Learning.

### Prerequisites

In this project we use pandas (for dataframes, defaultdict(for dictionary) and PersianStemmer (for stemming persian text) libraries.
first install these libraries.

for installing these libraries using pip type these instructions in python shell:

```
pip install pandas
```

```
pip install defaultdict
```
```
pip install PersianStemmer
```
## problem describtion
We have a train dataset of Digikala.com comments in bin/train.csv with 160,000 supervised enteries

![train_dataframe](http://s7.picofile.com/file/8387450776/Train_dataframe.png)

Each comment entry consists of id, title, comment, rate and verification status.
We whant to detect spam comments by training on train dataset using machin learning.

we will use "Multinuminal Naive Bayes" algorithm for solving this problem.

And we have test dataset of comments which doesn't have verification status column; We should implement it!

![test_dataframe](http://s7.picofile.com/file/8387453742/test_dataframe.png)

it has 20000 comments

## Multinuminal naive bayes
* [Worked_Example](https://www.youtube.com/watch?v=OWGVQfuvNMk) - very good example of how this algorithm works and how implements

