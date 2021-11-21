# Predicting Housing Market using Real Life Demand & Supply Factors.
Every commodity in this world is sold on the basis of it's demand and supply, so does Housing Market. Factors like Unemployment, GDP, Consumer Price Index, Mortgage Rates affect the Demand Side of housing market and thus, have various effects on the price. Whereas, factors like Existing Homes, Monthly supply of new homes, Abandoned Homes and Fix&Flip Homes affect the supply side of Housing Market. <br>
<br>
Therefore, I collected all the data of above mentioned factors for the past 20 years since 2000 and created an algorithm to check how this would affect Prices of Housing/Residential Market in the next few years. 
<br>
I have also taken into account various market crashes like 2008, and the Covid 2019.

*From the graphs and plots attached in this repository, you would be able to see that factors have been either directly proportional or inversely proportional to Residential prices.*

*And also, GDP Growth had the highest impact on Home Prices in the last 20 years, while 'Supply of New Homes' had the lowest impact on Home Prices.*

Novelty: <br>
1. All the Housing Market *prediction* algorithms on the internet do not take into account the *real life* factors on which the market is actually based upon. This algorithm gives out the exact results based on Regression Models, and taking into account real life factors.
2. One can use such algorithms to accurately predict the market for next 3-5 years (unless there's a crash), and hence can save up/invest accordingly.

Methodology:<br>
1. All the datasets are combined into one dataframe.
2. The dataframe now formed is now pre-processed and normalised.
3. All Regression Models are then compared and the one giving best accuracy is then created.
4. Results are noted, and individual plots are then created.
5. Correlation between the factors is checked. 
