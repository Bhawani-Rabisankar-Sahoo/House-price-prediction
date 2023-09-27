# House-price-prediction
## Aim
Predicting the best possible price for a house based on  various parameters .
## Approach

## Data Cleaning

- First data  cleaning 

- It includes dealing with outliers and missing values 
## EDA

- Second part is Exploratory Data Analysis (EDA) .
-![Screenshot (30)](https://github.com/Bhawani-Rabisankar-Sahoo/House-price-prediction/assets/72175654/973bc54e-5f03-4beb-89be-de960d7a735d)

- Here we'll explore the data to get as much insights we can get from  it.
## Model Building

- Here we'll feed the cleaned data to the machine learnning model to predict the future scenario.
## Results 


![Screenshot (32)](https://github.com/Bhawani-Rabisankar-Sahoo/House-price-prediction/assets/72175654/b6304842-8fe3-421e-867a-e16197cbd072)

- So as we can see from the correlation matrix  that the 'median_house_value' has a -0.48 correlation with the houses that are inland and likewise it has a positive correlation of 0.28 with the houses that are near to the coast/ocean.

- If we  plot  a  scatter polt with longitude on the x-axis and latitude  on the y-axis with the hue  as 'median_house_value' with the price of the hoses increases as the colour changes  from blue to red.
- We can clearly see that the price of the houses are significantly higher in the coastal areas as we can see from the scatter plot the near  to Ocean houses are mostly red and the inland houses are mostly blue.
![Screenshot (31)](https://github.com/Bhawani-Rabisankar-Sahoo/House-price-prediction/assets/72175654/3d4a3c79-2795-4dac-bf16-627e1e56f67d)

## Model results

- I've trained a Random Forest Regressor model which successfully predicted the 'median_house_price' of the houses with score of **93.1%** .

