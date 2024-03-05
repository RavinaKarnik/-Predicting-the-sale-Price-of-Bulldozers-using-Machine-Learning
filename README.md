# -Predicting-the-sale-Price-of-Bulldozers-using-Machine-Learning

![Bulldozer Thumbnail](https://github.com/RavinaKarnik/-Predicting-the-sale-Price-of-Bulldozers-using-Machine-Learning/assets/130289037/1c087ad9-48c0-4393-a4f6-268887eb7a31)


In this notebook,we're going to go through machine learning project with the goal of predicting the sale price of bulldozers.

## 1. Problem Definition
How well can we predict the future sale price of a bulldozer,given its characteristics and previous examples of how much similar bulldozers have been sold for?

## 2. Data
The data is downloaded from the Kaggle Bluebook for Bulldozers competition:https://www.kaggle.com/code/radhakrishnasp/bulldozer-price-prediction

### There are 3 main Datasets:

Train.csv - Historical bulldozer sales examples up to 2011 (close to 400,000 examples with 50+ different attributes, including SalePrice which is the target variable).
Valid.csv - Historical bulldozer sales examples from January 1 2012 to April 30 2012 (close to 12,000 examples with the same attributes as Train.csv).
Test.csv - Historical bulldozer sales examples from May 1 2012 to November 2012 (close to 12,000 examples but missing the SalePrice attribute, as this is what we'll be trying to predict).

## 3. Evaluation
The evaluation metric for this competition is the RMSLE (root mean squared log error) between the actual and predicted auction prices.

For more on the evaluation of this project check: https://www.kaggle.com/competitions/bluebook-for-bulldozers/overview

Note: The goal for most regression evaluation metrics is to minimize the error.For exapmle.our goal for this project will be to build a machine learning model which inimises RMSLE.

## 4. Features
Kaggle provides a data dictionary detailing all of the features of the dataset.You can view this data dictionary on Google Sheets.: https://www.kaggle.com/competitions/bluebook-for-bulldozers/data

## 5. Contributing :-
Contributions are welcome! If you have any ideas, suggestions, or improvements, please open an issue or submit a pull request.

## 6. Linkeddln Post link :-

## 7. Acknowledgements :-
The Dataset is dowloaded from kaggle website.
Special thanks to the contributors and developers of Excel and google colab and also related tools for enabling powerful data analysis and reporting capabilities.
