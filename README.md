# Business Understanding

- For this project, we used the King County House Sales dataset calculations to advise future homeowners on how the quality of construction and housing materials / features affects the price of a home.

# Data Understanding

 - Importing Key Python libries for data analysis and visualization
 - Loading King County Housing data set using kc_house_data.csv file

## Data Preparation

- Creating a copy of the DataFrame for cleaning and preprocessing 

# Exploratory Data Analysis
![top_10_feats_price_prediction](https://github.com/user-attachments/assets/9642c911-a05f-4440-a527-e436c0e4f0b1)
![price_impact_constr_grade](https://github.com/user-attachments/assets/2f4e8eea-bb51-4be5-900d-59b766d91a8e)
![price_dist_home_size](https://github.com/user-attachments/assets/c90cc301-23b4-46fc-9bdd-5afbb97147c1)
![renov_impact_on_price](https://github.com/user-attachments/assets/1ea4e26f-b284-4208-ba34-87ddef9e8b22)

# Conclusion

Construction grade is the primary factor affecting home value. Moving from Grade 7 to Grade 8 typically adds $140,392 in home value (34.9% increase). Grade 8 homes seem to have the best value retention

Renovated homes sell for $236,762 (44.5%) higher on average. You could possibly consider a renovation potential in Grade 6-7 homes

There is a strong correlation between living space and price. Median price per sqft is $245, so possibly adding an additional 500 sqft to a home could increase the value by roughly $122,322

Random Forest was the best model with the highest R²: (0.697), Lowest MAE (128,796) and Lowest RMSE (198,720)

## Limitations

To increase the accuracy of predications some more parameters are needed
The data set is not current.

## Recommendations

Focusing on construction quality seems to have the highest impact on value

Consideration for a renovation potential on homes between Grades 6-7

Inceasing the size of living space could increase the value of a home since it directly correlates with price
## Next Steps 

Next steps would be to upgrade the overall analysis so it's current since the data set is from 2014 to 2015

Also maybe incorporating school ratings and crime status to the data set to give a better overall picture of the focus area

Partnering with contractors and lenders could be a good step in getting more insight for a potential homebuyer
