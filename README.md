# T5o15-PROJECT

## Abstract
The goal of this project was to use some of supervised machine learning models to predict income, I worked with data provided by Barry Becker from the 1994 Census, I trained three models and then I compared them and made a graph showing the prediction accuracy results for each model.
## Design
This project to explore whether if demographic characteristics have an effect on an individual's annual income, and can we predict whether if the income is `<=50K` or `>50K`?

To predict annual income we will need to use some machine learning methods, and because the dependent variable is bi-categorical, it would be appropriate if we use the following models: Logistic regression, Decision Trees, RandomForest.

## Data
This dataset is an extraction was done by Barry Becker from the 1994 Census database.

  Attribute Information:
 
 **Input variables:**
 
    1. `age`: continuous.
    
    2. `workclass`: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked.
    
    3. `education`: Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 
    1st-4th, 10th, Doctorate, 5th-6th, Preschool.
    
    4. `marital-status`: Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse
    
    5. `occupation`: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, 
    Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces.
    
    6. `relationship`: Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.
    
    7. `race`: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black.
 
    8. `sex`: Female, Male.
    
    9. `hours-per-week`: continuous.
    
    10. `native-country`: United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), 
    India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal,
    Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand,
    Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands.
   
     **Output variable**
  
    1. `income`: binary response: `<=50K` or `>50K`

  Dataset url:`https://archive.ics.uci.edu/ml/datasets/Census%2BIncome`
  
## Algorithms

*Preparing the Data*
1. Transforming Skewed Continuous Features
2. Normalizing Numerical Features
3. Encoding the categorical features
4.  split the data into training and test sets

*Models*
  
 1.Logistic Regression
 
 2.Decision Tree Classifier
 
 3.Random Forest Classifier
 
 3.Support Vector Classifier (SVC)
 
*Models Evaluation*
  
 Here is a table containg all the results:
 
 ![table](https://github.com/shahadl/T5o15-PROJECT/blob/main/images/1.PNG)

## Tools
* Tools for EDA:
1. jupyter notebook
2. numpy
3. pandas

* For modeling:
1. sklearn
2. statsmodels

* For visualization:
1. matplotlib

## Communication

This is a comparison between the prediction accuracy results of the models I've trained, but could they be better?
 ![table](https://github.com/shahadl/T5o15-PROJECT/blob/main/images/2.PNG)

<img src="dashboard.png" width=500>
