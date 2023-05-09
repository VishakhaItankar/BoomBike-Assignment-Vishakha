# Project Name
> Bikesharing mode for Boombike


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#libraries-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
### Problem Statement:
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

### Business Goal:

You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

# Used Following steps for final model:

1) Reading and understanding the data

2) Visualising the data

3) Preparing the data for model training 

4) Splitting the Data into Training and Testing Sets

5) Building a linear model

6) Residual Analysis of the train data

7) Making Predictions and Evaluation using the Final Model

# Summary:

The summary of the model after data interpretation, visualisation, data-preparation, model building and training, residual analysis and evaluation of test model are as follows-

1) The R-squared value of the train set is 79.15% whereas the test set has a value of 77.00% which suggests that the model broadly explains the variance quite accurately on the test set and thus it can be concluded that it is a good model. 

2) Developed model's mean squared error is almost 0 on both the training and testing datasets which suggests that the variance is accurately predicted on the test set. The p-values and VIF were used to select the significant variables. RFE was also conducted for automated selection of variables.  

3) Following independent variables helped to conclude the model with good accuracy
- yr                      
- holiday                
- temp                    
- windspeed              
- season_summer          
- season_winter           
- mnth_sept               
- weekday_sun            
- weathersit_moderate 


## Libraries Used
- numpy
- pandas
- seaborn
- scipy
- sklearn
- statsmodels




## Contact
Created by [@vishakhaitankar] - feel free to contact me!

