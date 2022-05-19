# phase_2_project# How can you improve the value of your home?

## Business Problem

The question is: What can a homeowner improve to boost the value of their house?




# Data
To answer that question, I am going to look at housing sales data from King County, WA (the Seattle area) from 2014-15 when over 21k houses were sold. The county was generous enough to provide this data online.
Now there are many categories in the dataset but I am limiting it to the things that an existing homeowner can control like:


-The condition

-Grade 

-Sq. footage

-The number of bathrooms, bedrooms

-The month the deal closes in

-When/if you renovated.

# Regression Results

![image](https://user-images.githubusercontent.com/101752113/169361275-b4f58c97-59b3-48c9-9ee7-25ed1d84f651.png)

# Interpretation

The model can explain 56% of the variation in the price data. That may seem low but remember that this model does not include zip code, view data, and waterfront data because an existing homeowner cannot control the factors. 


# Recommendations

1. Improving the square footage by 5% leads to an increase in price of 2%.
2. Improving the grade by 1 unit will increase price by 39%.
3. Recently Renovated homes sell for 7% more.


# Next Steps

-Moving beyond the King County area: the Seattle area is very unique and the trends we see in the 2014-15 years may  not be representative for the country.
-Isolating by individual zipcodes and examining how they effect of the features on the price.


https://github.com/icapeli/phase_2_project
