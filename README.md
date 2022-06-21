# IMDb Rating Prediction for Blockbuster Movies

An exploration of several regression methods to predict the IMDb ratings Blockbuster films. 

### **Steps Taken** 
1. Predictor Analysis - Identifying the dependent variables that best enhanced the predictive power of the models used, including the use of a correlation matrix.
2. Target Encoding for Categorical Vars - As many actor/producer names are present, performing 1-hot encoding would result in several weak predictors. Instead, the average rating of all movies where a given name appeared was used in place of these variables.
3. Model Building - Several regression models (linear/polynomial/spline) were tested and experimented with in an attempt to identify a combination of predictors & coefficient degrees that would yield the highest R<sup>2</sup>.
4. Validation - 10-fold cross validation was used with approximately 300 observations in each to balance run time and efficiency.


<br>

Code contained here is used within the course 'MGSC 661 Multivariate Statistical Analysis' of the MMA Program at McGill University.

This project was done in collaboration with [Kelly Agnew](https://github.com/kelly-agnew), [Wang Jingyuan](https://github.com/anarlewang), [Aishwarya Choukekar](https://github.com/aishwaryachoukekar), [Saad Tariq](https://github.com/saadtariq22) and [Gayatri Krishnamoorthy](https://github.com/Gayatrik9)