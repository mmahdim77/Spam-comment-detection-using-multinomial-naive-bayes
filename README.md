# Spam comment detection using multinomial naive bayes
Spam detection software that can find spam among a large number of comments
## Getting Started

This project has a dataset of supervised comments that specify whether they are spam or not.

This dataset should be used to train a machine learning model that determines whether received comments are spam.

### Prerequisites

For this project, we use pandas (for data frames, defaultdict (for dictionaries), and PersianStemmer (for stemming Persian text) libraries.
Installation of these libraries is the first step.

To install these libraries using pip, type the following instructions in the Python shell:

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
Our training dataset with 160,000 supervised 'Digikala.com' comments is in bin/train.csv.

![train_dataframe](http://s7.picofile.com/file/8387450776/Train_dataframe.png)

Each comment entry consists of an id, a title, a comment, a rating, and a verification status.
Using machine learning solutions, we should detect spam comments by training on train datasets.

To solve this problem, we will use a Multinomial Naive Bayes algorithm.

Moreover, we have a test dataset of comments without a verification status column; we should add it!

![test_dataframe](http://s7.picofile.com/file/8387453742/test_dataframe.png)

It has 20000 comments.

## Multinomial Naive Bayes
* [Worked_Example](https://www.youtube.com/watch?v=OWGVQfuvNMk) - This shows how well and what is involved in this algorithm.
