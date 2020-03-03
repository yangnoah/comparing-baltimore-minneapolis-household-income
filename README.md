# comparing-baltimore-minneapolis-household-income-based-on-neighbourhood
An analysis of the how childhood location affects household income in adulthood in both Baltimore and Minneapolis

This analysis used data from the [Opportunity Atlas](https://www.opportunityatlas.org/)

## Analysis Steps: 

1. Adult household income data for children who grew up in Baltimore and Minneapolis was downloaded. Two data sets were analyzed - childrens' parents whose income was in the 25th percentile (low income) and childrens' parents whose income was in the 75th percentile (high income).
2. The raw data can be found here:

  [Minneapolis Household Low Income](https://github.com/yangnoah/comparing-baltimore-minneapolis-household-income/blob/master/Original%20Tract%20Data%20for%20Balitmore%20Region%20(Low%20Household%20Income).csv)
  
  [Baltimore Household Low Income](https://github.com/yangnoah/comparing-baltimore-minneapolis-household-income/blob/master/Original%20Tract%20Data%20for%20Minneapolis%20Region%20(Low%20Household%20Income).csv)
  
  [Minneapolis Household High Income](https://github.com/yangnoah/comparing-baltimore-minneapolis-household-income/blob/master/Original%20Tract%20Data%20for%20Minneapolis%20Region%20(High%20Household%20Income).csv)
  
  [Baltimore Household High Income](https://github.com/yangnoah/comparing-baltimore-minneapolis-household-income/blob/master/Original%20Tract%20Data%20for%20Balitmore%20Region%20(High%20Household%20Income).csv)
  
3. The data was filtered so that only census tracts that fell inside the city were included in the analysis (filter in Excel, then copy and paste) 
4. VLOOKUP was used to to match low and high incomes for each census tract (both in Baltimore and Minneapolis) 
5. Data was graphed and not deemed interesting, so a comparion between Baltimore and Minneapolis (low income parents) was done
6. Census tracts were graphed in descending order so that a relative comparison could be made betweeen Baltimore and Minneapolis (if we looked at the best and worst communities (for adulthold income) in each city to grow up in, how do they compare?)

![alt text](https://github.com/yangnoah/comparing-baltimore-minneapolis-household-income/blob/master/Baltimore%20and%20Minneapolis.JPG)

## Findings
1. The best areas to grow up with a low parental income in Minneapolis lead to only slightly more income than the best areas in Baltimore. However, this difference gets larger and larger as you move down the rankings. This suggests that, in Baltimore, there are some areas where growing up with low income parents will not put you at a significant disadvantage compared to growing up with a similar household income in Baltimore. 
2. This suggests that there are concentrations of resources in Baltimore (transit, education, food pantries, etc) that cause certain neighbourhoods to be better for families who are lower income. Policies in Baltimore should look at spreading out these resources to ensure every family benefits. 

## Plotly Analysis
1. This analysis was redone with Python
2. The data used was the one from the [previous](https://github.com/yangnoah/comparing-baltimore-minneapolis-household-income/blob/master/Processed%20Data.csv)
3. Analysis was completed using plotly express and graphed as shown below: 

![alt text](https://github.com/yangnoah/comparing-baltimore-minneapolis-household-income/blob/master/plotly1.JPG)
![alt text](https://github.com/yangnoah/comparing-baltimore-minneapolis-household-income/blob/master/poloty2.JPG)
