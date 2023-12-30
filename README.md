# AirBnb Investment Analysis

## Project Overview:

This project is for a hypothetical real estate investing firm who is considering purchasing apartments in Boston and renting them out on Airbnb. The goal is to analyze Airbnb rental prices in Hyde Park through a deep market analysis and develop a final regression model that does the best possible job of predicting the price of an Airbnb rental in the neighborhood. Additionally, this project finds the estimated monthly payment reported on for a property currently on sale in these neighborhoods (which includes mortgage, taxes, insurance and homeowner fees) and convert the current mortgage cost to 2016 values to fit the data. Finally, the project uses the final regression model to estimate the rent you can charge for an Airbnb in this neighborhood and calculates the expected monthly profit to determine if it's worth it to purchase and rent out and Airbnb property.

## Steps Taken: 
1. Cleaned data, created variables, and regress price on accommodates, accommodates_sq, bedrooms, bathrooms, property type, and location review scores, and missing review scores.
2. Created additional dummy variables to include other variables that may have an affect on price: location, review score, air conditioning, wireless internet, parking, pets, family friendly, and superhost.
3. Removed variables where the t-statistic is less than 1 (t<1): shared room, review score, and wireless internet.
4. Found the current estimated monthly payment of buying a property in these areas, and calculated the expected rental price using the variables of this property.
5. Constructed a 95% confidence interval of the expected rental price of the Airbnb.
6. Calculated the expected monthly profit if the property is rented for 20 days out of the 30 in a month, and the number of days you would need to rent the Airbnb each month in order to break even on the investment.
