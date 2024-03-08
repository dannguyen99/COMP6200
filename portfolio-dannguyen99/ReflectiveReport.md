# Reflective Report

Author - Nguyen Duc Dan
StudentID - 46864660

## Problem Solving

### A. Report the process of solving problems and learning to use notebooks

I was somewhat familiar with Jupyter notebook and Python beforehand, so the process from the start of the unit was comfortable for me. Through out the unit, it was helpful that the content was delivered clearly, and the Practical Works as well as the Portfolios were intuitively construct. Therefore, at the end of the unit, student can use notebook and Python to perform analysis confidently.


### B. How have you progressed from the start of the unit, what are you interested in doing with this in the future?

From the start to the end of the unit, many helpful contents have been delivered.

Personally, I have gain a view of data science, identify steps needed to perform an analysis, knowing the procedure of training/testing different Models, ...

In the future, these knowledge should be the fundamental block for me to better practice data science.

## Discussion Point

### 1. Why you choose the dataset you have used for your portfolio?

We choose the [Pokemon dataset from Kagle](https://www.kaggle.com/datasets/abcsds/pokemon). One of the reasons is the student personal preference over the Pokemon game series. 

However, on the other hand, the Pokemon dataset is suitable for the analysis work. It has both categorical and numerical features, which can be used to build classification models, or regression models. The features are also easy to understand and somewhat correlated, so that the analysis could be meaningful.



### 2. How do you identify the problem you target to solve in your portfolio?

After choosing the dataset, we need to identify the problem that needed to be solved. For my case, the problem should be relevant to the Pokemon world, in particular, tackle some tasks that could be done in the Pokemon games.

Another thing to be considered is, with given dataset, which analysis should we perform, or which models could be built with given dataset. With our choice of data, we can use it to build a regression model and a classification model. Therefore, we can identify the analysis problem as follow:
- Can we build a model to predict one Pokemon combat stat based on it's other attributes?
- Can we build a model to classify if a Pokemon is a Legendary or not?

### 3. The reason to choose your machine models in portfolio 4 and why these models are suitable for solving the problem you have raised.

We chose to build 2 models in the portfolio, that is:
- A Linear Regression model.
- A K-nearest Neighbors Classifier.

They were choosen base on the previous problems that we have identified. Furthermore, after data preprocessing and analysis, it can be seen that some meaningful result could be achieved using these models.
- With Linear Regression: Some numerical features are well correlated, therefore a LR model coud perform and give good results.
- With K-nearest Neigbors: Any classification models can be used in this case, but we choose KNN because it performed reasonably well compare to other classifier, and we can tune it's hyperparameter for best results.

### 4. Can you well explain the insights or conclusion you draw from your study? Is the result consistent with your intuitive expectation?

The result of the analysis are somewhat intuitve, whether you are familiar with the Pokemon game series or not.
- With the first problem, to predict Pokemon Defense stat base on it's other stats. From the result, it is suggest that the higher the Pokemon Speacial Defense, the higher its Defense. In other words, if a Pokemon dealing well with Special Attack from other Pokemon, it should also handle Physical Attacks well. We can say that the Pokemon is sturdy. 
- Another conclusion that could be draw from the first problem is that we can improve the model performance by giving it more inputs. By increasing the dimension of our training data, we could provide more information to Linear Regression Model and achieve better prediction. This also aggree with the intuitive expectation as the more we known about one Pokemon, the more we can predict it's defense ability.
- With the second problem, to identify if a Pokemon is Legendary base on it's combat stats, the conclusion is aligned with our initial expectation, that is Legendary Pokemon usually have higher stats than normal one. This is reasonable since Legendary Pokemon are usually rare and powerful Pokemon, so they should have higher stats compare to others.
- Another point after analysing the second problem is we can make our predictive model better by tunning the hyperparameters. With the case of our analysis, increasing K number of neighbors better the performance of the classifier in terms of accuracy. An intuitive way of thinking about this conclusion is: We need to see many Pokemon to be able to tell if one is Legendary or not.