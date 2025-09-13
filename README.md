These notebooks provide sentiment analysis of movie reviewers comments by first embedding a vocabulary in a vectorized representation, then reducing said vocabulary via various data wrangling techniques.

The main program will begin with these steps of forming a working vocabulary, then it will use xgboost to train a model to make predictions on a given test set.

To use the sentiment analysis code simply run mymaintest which will generate a json file corresponding to the parameters of an xgboost model
