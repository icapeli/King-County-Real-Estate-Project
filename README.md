# How can you improve the value of your home?

## Business Problem

For many Americans, the most important and valuable asset they own is their home. Owning a home is not just the American dream. Owning a home is an avenue to prosperity. The American real estate market is the most important in the world. Academia, TV shows, and books all offer tips on how to make money in the real estate industry. **The goal of this project is to examine, using linear regression, how an existing homeowner can improve the value of their home. Using King County, WA sales data from 2014-15, I will determine which features are most valuable**.

This study will put a special focus on a few features: **the home's square footage, grade, and whether the home was renovated in the last 10 years(or as Recently Renovated as it will be defined from here on out)** because these are the features a homeowner can control. 




## Data
To answer that question, I am going to look at housing sales data from King County, WA (the Seattle area) from 2014-15 when over 21k houses were sold. The county was generous enough to provide this data online.
Here are the features that county provides info on:

![image](https://user-images.githubusercontent.com/101752113/169716517-e6936fcc-20e9-4b1b-a644-709c846b0c7e.png)

**However, I am limiting my analysis to these features**:


-The condition

-Grade 

-Sq. footage

-The number of bathrooms, bedrooms

-The month the deal closes in

-When/if you renovated.

## Regression Results
![image](https://user-images.githubusercontent.com/101752113/169852202-10768603-dee1-4788-b4da-ddc2e82ba8df.png)

##  Interpretation

The model can explain 57% of the variation in the price data. That may seem low but remember that this model does not include zip code, view data, and waterfront data because an existing homeowner cannot control the factors. 




## Results and Recommendation

![image](https://user-images.githubusercontent.com/101752113/169853345-161ec9a8-8456-4882-ac54-e9b78797bf17.png)

The average price in King County, WA is 540k. So, above are the changes in price for the average priced home with a 5% change in square footage. This leads to Recommendation #1:

**Improving the square footage effects price but perhaps not as strong as I thought. A homeowner's resources may be better spent elsewhere.**

Now let's look at the difference between homes with grades of 'Average', 'Good' and 'Very Good'. The graph below shows what happens when the average priced home in the area changes grades.



Wow, From Average to Good, there is an increase of 17% and 45% from Good to Very Good. This leads to Recommendation #2:


**Improving the grade of an Average house can have a monumental effect on sale price. So a homeowner should do so, if at all possible**

Now let's investigate the effects of a recent renovation:

![image](https://user-images.githubusercontent.com/101752113/169852575-616ffdd1-fae5-4d5e-8454-6b87d1ce7ee0.png)

Obviously, a recent renovation has a huge effect. This observation flows into Recommendation #3:

**Renovating the house sometime in the 10 years before you sell also has a 56.97%  positive effect on sale price. So a homeowner should do so, if at all possible**.

## Conclusion
This study, at the vey least, provides very useful information for any King County, WA homeowner on how they can improve the value of their home. While increasing square footage is not as important, improving the grade and a recent renovation will yield high sale prices for homeowners. Since home is where the heart is, homeowners may rest easier if they renovate and improve their homes' grade before they sell!


# Next Steps

Moving beyond the King County area: the Seattle area is very unique and the trends we see in the 2014-15 years may  not be representative for the country.
Isolating by individual zipcodes and examining how the features I studided  effect price in different zipcodes. For example, perhaps in wealthier neighborhoods, improvements in grade yield greater % changes in price then in less affluent areas.


https://github.com/icapeli/phase_2_project
