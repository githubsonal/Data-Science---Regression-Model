# Data-Science : Regression Model

This repository contains Regression Model project.



The Problem :
Airbnb is a hospitality company that runs an online marketplace for renting and leasing short-term lodging, primarily homestays, or tourism experiences. 
The company does not own any of the real estate listings, nor does it host events; it acts as a broker, receiving commissions from each booking. 
It is interested in developing a pricing service for its users that will compute a recommended price based on the features of a listing.We have to develop a model for predicting nightly prices of Airbnb listings.

Dataset : train.csv

Models implemented : Regreesion

Stpes Performed :
  * Data Preprocessing : 
         - Check missing values (with heatmap and through calculating numbers)
         - Impute numeric and category varibles :
                numeric : fill missing values with mean
                category : most frequent value occurred 
         
         
 * Exploratory Data Analysis :
         - Checked distribution of rooms frequncy against price.
         - visualization for continuous and categorical variables data.
         - Bivariate Analysis :
                  - With help of heatmap checked for correlation between two variables of dataset.
                  - Checked behaviour of varibles such as number of accomodent,beds, Bathrooms against price to do analysis of abnormal records.
                  - Also for property type, business travel ready, cancellation policy.
                  
  * Feature Engineering : 
          - combined categorical varibles.
          - Used minmaxscalar to scale numeric feature.
          - Used lableencoder

* Modelling :
         - Implemented regression models. (Linear,Decision Tree, Random Forest,Lasso regression)
                
