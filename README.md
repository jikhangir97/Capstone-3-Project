# Dayona Car Dealership CLustering: Project Overview 
* Created a some clusters to help managers of car dealership decide to which customer groups to sell cars.
* Data gathered from Kaggle
* Optimized k-means clustering with elbow and silhoutte method to find best results 


## Code and Resources Used 
**Python Version:** 3.7  
**Packages:** pandas, numpy, sklearn, matplotlib, seaborn  


## Data Cleaning
After gathering the data, I needed to clean it up so that it was usable for our model. I made the following changes and created the following variables:

*	Removed "ID" column 
*	Filled up NaN values using ffill method 
*	Changed columns from categorical to numeric using mapping method  
*	Changed column name of Var_1 to 'Category'
*	Changed types of columns 

## EDA
I looked at the distributions of the data and the value counts for the various categorical variables.


## Model Building 

First, I transformed the data into between 0-1 using MinMaxScaler module of sklearn

I tried k-means clustering model with using elbow method and silhoutte method.

Made sure how many cluster I need in this model using elbow and silhoutte method.

I tried two different method to find perfect number of clusters:
*	**Elbow Method** – In cluster analysis, the elbow method is a heuristic used in determining the number of clusters in a data set.
*	**Silhoutte Method** – Because of the elbow method couldn't decide how many clusters, I thought using thos method would gives us result.
