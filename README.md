# Correlation-and-Regression

## Correlation 

#### What is Correlation?
When we talk about correlation, we are essentially looking at the connection between two variables with numerical values.

Depending on whether the variables are positively or negatively related, we can learn if the relationship is growing or decreasing. A positive value indicates a growing relationship, whereas a negative or null value indicates a diminishing or no relationship, respectively.

It is important to note ***that correlation only provides insight into the relationship between variables and nothing else.***

To better understand this concept, we can use various visualisation techniques such as :
- correlation matrices
-  heat maps
-  and scatter plots.

In this exercise, I used a scatter plot visualisation to better understand the [Covariance Pearson Correlation](covariance_pearson_correlation.ipynb).

## Regression 

##### What is Regression? 

When I came across the concept of regression, it reminded me of the role of a mediator. I found it similar to how the mediator tries to find the best possible solution for all involved parties. 

In machine learning, regression is the supervised learning technique that finds the best relationship between variables and features to reduce errors between predicted and actual values.

In this notebook, we have :

- linear regression - where the model finds the ideal line for an independent variable.
- multiple linear regression - where the model finds the ideal plane for two or more independent variables 
- polynomial regression -  where the model finds the ideal line for non-linear relationships between the variable and feature.

### Why do we use Correlation & Regression together?
Simply because ***Correlation helps us analyse data*** by providing us with descriptive statistics, while ***Regression helps us build a model*** based on the correlation of those variables.
