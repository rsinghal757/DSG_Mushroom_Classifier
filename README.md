# Predicting mushroom samples as edible or poisonous.

The aim of this project was to classify mushroom samples into two classes: edible and poisonous, using characteristics like odor, gill size, color etc. A dataset taken from Audubon Society Field Guide to North American Mushrooms(1981) is used for the purpose.

R (version 3.4.2) was used to create a model to classify the mushroom samples as edible or poisonous.

## Libraries used

  1. caTools: caTools package is used to divide the data into training and testing sets in such a way that both have same ratio of different levels in dependent variable.
  2. rpart and rpart.plot: These packages are used to create tree based models and make their visualisations.
  3. randomForest: This package is used to train the model in this problem.
  4. caret: caret package is used to perform cross validation.

### Note:
The file mushroom_predictions.csv contains the predictions 'edible or poisonous' for the dataset mushroom_test.csv.
Also, the jupyter notebook, 'Rohit_Singhal_Mushroom.ipynb', contains the R code as well as the approach and explanation.
