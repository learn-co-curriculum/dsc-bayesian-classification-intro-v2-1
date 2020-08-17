
# Bayesian Classification - Introduction

## Introduction

In an earlier section, you learned about Bayesian statistics with plenty of theory and application of Bayes theorem. You'll now take a look at using Bayes theorem to perform some classification tasks. Here, you'll see that the Bayes theorem can be applied to multiple variables simultaneously. 


## Bayes Classification 

Naive Bayes algorithms extend Bayes' formula to multiple variables by assuming that these features are independent of one another, which may not be met, (hence its naivety) it can nonetheless provide strong results in scenarios with clean and well normalized datasets. This then allows you to estimate an overall probability by multiplying the conditional probabilities for each of the independent features.

Bayes' formula extended to multiple features is:  

 <img src="https://render.githubusercontent.com/render/math?math=\Large P(y|x_1, x_2, ..., x_n) = \frac{P(y)\displaystyle\prod_{i}^{n}P(x_i|y)}{P(x_1, x_2, ..., x_n)}"> 



## Document Classification

An interesting application of Bayes' theorem is to use _bag of words_ for document classification. A bag of words representation takes a text document and converts it into a word frequency representation. In this section, you'll use bag of words and Naive Bayes to classify YouTube videos into appropriate topics. 

## Summary

Over the next few lessons you will learn about another fundamental classification algorithm which has many practical applications. It's time to jump into the wonderful Bayesian world again! This section will help you solidify your understanding of Bayesian stats. 

