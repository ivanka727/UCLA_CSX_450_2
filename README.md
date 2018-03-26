
## 1. The domain of the problem
We are analyzing iris flowers and we want to develop a model that will be able to tell us the class of a newly found iris. The dataset contains 3 classes of 50 instances each, where each class refers to a type of iris plant. Four features were measured from each sample: the length and the width of the sepals and petals, in centimetres. Two of the three species were collected in Gape Peninsula all from the same pasture, and picked on the same day and measured at the same time by the same person with the same apparatus. 
## 2. A problem statement in which you clearly define
We're doing predictive modeling to use the available data to predict a new class of Iris, we will use the supervised learning. The model inputs are Sepal.Length, Sepal.Width, Petal.Length and Petal.Width, and it will output 3 different class of Species, Setosa, Versicolor, Virginica.
## 3. Dataset Description
This dataset has 150 Iris flower with 3 different species, 150 rows and 5 columns, the size is 7.01 KB. The data types are numeric and factor. There are 4 features (Sepal.Length, Sepal.Width, Petal.Length and Petal.Widt, input to the model) and the sepcies are what we are looking for (the classification of the iris, Setosa, Versicolor, Virginica). We measured the minimum value, maximum value, median value, mean value, 1st qun and 3rd qun. See below. 

![my image](https://github.com/lssnadia/UCLA_CSX_450_2/blob/master/Screen%20Shot%202018-01-26%20at%2010.10.38%20PM.png)

All features Sepal.Length, Sepal.Width, Petal.Length and Petal.Width are normal distribution.

![my image](https://github.com/lssnadia/UCLA_CSX_450_2/blob/master/Screen%20Shot%202018-01-26%20at%2010.48.59%20PM.png)
![my image](https://github.com/lssnadia/UCLA_CSX_450_2/blob/master/Screen%20Shot%202018-01-26%20at%2010.49.25%20PM.png)
![my imgae](https://github.com/lssnadia/UCLA_CSX_450_2/blob/master/Screen%20Shot%202018-01-26%20at%2010.49.38%20PM.png)
![my image](https://github.com/lssnadia/UCLA_CSX_450_2/blob/master/Screen%20Shot%202018-01-26%20at%2010.50.14%20PM.png)

## 4. A proposed solution
We are going to create 3 different models and to use 3 different algorithm (LDA, KNN, and CART). Based on the result, we'll find out which model is the most accurate one. 
## 5. A benchmark model
As we're using supervised learning, we can divide data into 2 sets, training and validation. We will break the measurements into 80/20 percent. we use the 80 percent of the dataset to create the models and we test the models against the other 20%. 
## 6. A performance Metric
we need to test our models for benchmarks, so we use only 120 rows to come up with the models and then we test the models against the other 30 rows to see how accurate they are. We use ratio of the correct predictions of the model divided by total number of instances in the dataset.
