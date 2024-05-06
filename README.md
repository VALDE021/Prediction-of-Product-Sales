# Prediction of Product Sales
Welcome to the Prediction of Product Sales project! This repository hosts a solution that predicts product sales using machine learning techniques. Whether you're a data enthusiast, a business owner, or just curious about predictive analytics, you're in the right place!

# About
This project aims to forecast product sales based on historical data. By leveraging machine learning algorithms, we predict future sales trends, helping businesses make informed decisions about inventory management, marketing strategies, and more.

# Features
- **Easy-to-Use:** Our solution is designed to be user-friendly, even if you're new to data science.
- **Predictive Power:** Leverages state-of-the-art machine learning techniques to provide accurate sales predictions.
- **Customizable:** Feel free to tweak parameters and experiment with different models to suit your specific needs.


## Project Outcome and Findings 
- Parts 1-8

## Sale Predictions on Products within Supermarkets and Grocery Stores

**Authored by:** Eric N. Valdez

### Business problem:

Discovering the the best out come of Product Sales through different stores. 


### Data:
Through several weeks this project will look at many different ways to see the data, to solve problems on sale products for diffferent 
store locations, it will help you see where improvemnets can be made for opportunities. You will be able to see insights from the beginning.


## Methods
- From the beginning we've been able to chart different graphs to help see where the sale issues are
- We've been able to take it further with Machine learning to see different ways are target is affected 
- Ways to predict product sales

## Results

### Here are examples of visualizations


#### Heat Map of Prediction of Product Sales
![Heat Map](https://github.com/VALDE021/Prediction-of-Product-Sales/assets/134979886/52a820e9-356a-44ba-ad93-4c15f48c0431)

> Our heat map allows us to look at how we see our Item Oulet Sales correlates between other features that can affect our problem 

#### Random Forest Regressor Pipeline

## Model

Random Forest Model allows us to classify and look at ther regression, it can be less sensitive to noise and outliers in the data

### Regression Metrics: Training Data 

- MAE = 296.836
- MSE = 182, 909.354
- RMSE = 427.679
- $R^2$ = 0.938
  
### Regression Metrics: Test Data

- MAE = 776.805
- MSE = 1,245,831.112
- RMSE = 1,116.168
- $R^2$ = 0.555

This type of modeling creates a set of decission trees and combines them to make more accurate and stable predictions, 
and helps in Sales forecasting

## Recommendations:

Overall my Random Forest Model came high in $R^2$ after it was tuned allowing us to see what could be forecasted, however .5 is still low, 
and getting it to close to the 100% mark is going to take some more tuning to see what method can overall work for the company.


## Limitations & Next Steps

The next steps are to continue working on the buisness issues and improve the predictions for better results for the business. 

### We have revisited our models to predict Supermarket Sales.
* In doing this I used to models Linear Regression to look at the top 3 coefficients using a Linear Regression model
> * The top 3 most impactful features:
>> 1.   Outlet_Identifier_OUT010
>> 2.   Outlet_Identifier_OUT013
>> 3.   Outlet_Identifier_OUT019

![Linear Regression](https://github.com/VALDE021/Prediction-of-Product-Sales/assets/134979886/e5dc62e1-aa32-4049-9511-8c51a29e5654)
* Looking at how the Outlet_Identifier react to the graph is way we can pinpoint where the improvments in other locations need to be addressed and how to predict the outcomes.

* Then looked at our top 5 important features, which you see in a Random Forest (RF) Tree Model.
> * The top 5 that my RF Tree Model showed was is:
>> 1.   Item_MRP
>> 2.   Outlet_Type Grocery Store
>> 3.   Item_Visibility
>> 4.   Item_Weight
>> 5.   Outlet_Type_Supermarket Type 3

![Tree Model: Random Forest](https://github.com/VALDE021/Prediction-of-Product-Sales/assets/134979886/e8a30f94-55d9-4fe1-8e51-3763f57839a0)

*  In this graph it shows how helpful each feature was in growing/sorting the tree-based model. The more helpful a feature was in separating the data, the more "important" it is. It allow us to take hard looks in different areas where sales may need to be improved are not at the top.

In looking at these graphs we can see another way to hit our predictions by looking at different avenues, in specific features to see where product sales are affected and where we need to go from there.

### For further information
For any additional questions, please contact:

Eric N. Valdez (Data Scientist)
VALDE021@gmail.com
