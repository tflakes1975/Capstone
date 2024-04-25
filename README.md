# The African American single parent

## Table of Contents
* [Power BI Dashboard](#Power BI-dashboard)
* [Motivation](#motivation)
* [Questions](#questions)
* [Normalizing the Data](#normaling-the-data)
* [Problems and Hurdles](#problems-and-hurdles)
* [Technologies Used](#technologies-used)
* [Sources](#sources)
* [Conclusion](#conclusion)

## Motivation
As an African American single mom, I wanted to explore factors that may impact instances of single parenting. 

I grew up in a two -parent household. My mother and father have been married for over 45 years. I often wonder why I did not get married and chose to be a single parent versus getting married. I looked at some of the differences in my situation and my parents and decided to explore them further.

## Questions

1. Is there a relationship between location in America and the rise of single parenting overall? What states have higher instances of marriage?

2. Is there a correlation between the rise of single parenting and income and/poverty limits overall? if so, how does that look for African American in comparison to the overall?

3. What is the relationship between marriage and education. Is there more chance that African Americans with higher education will get married. 

4. Is there a correlation between the rise of single parenting overall and homeownership and how does it compare to that of African American

## Normalizing the data
I used multiple data sets from the U.S census. The one by state was from 2020 and include multi demographic items that I needed to make correlations in python. I aggregated columns to get percent columns to prevent polarization of the data. I used this table and made four different tables to manage the correlations in an organized fashion. The other data sets that I pulled from the census data needed to be cleaned up as they had percentage signs and commas that prevented joins and other functions in python. Once the data was cleaned, I joined the necessary tables for the factors that I decided to explore. 


## Problems and Huddles
The first table that I had downloaded from the Census was very chaotic. I had a hard time separating the information that I had because the table was stacked on top of each other horizontally and I needed to the information vertically. There were duplicate rows in one of my datasets that I did not realize until I had downloaded them into Power BI to do the visuals. I had to investigate and go back and change all the tables that I joined on with this table. This also meant redoing correlations in python as well. There were so many numbers and correlation coefficients that I transposed some of the numbers. This was found and corrected. I had a total of 19 tables once everything was cleaned up. 

## Technologies used	
Excel,
Python, and
Power BI



## Sources
B19001B: Household Income in the ... - Census Bureau Table
B17010B: Poverty Status in the Past ... - Census Bureau Table
Historical Marital Status Tables (census.gov)
DP02: Selected Social ... - Census Bureau Table
B25011: Tenure by Household Type ... - Census Bureau Table
Historical Households Tables (census.gov)
Historical Families Tables (census.gov)
https://thehill.com/opinion/finance/543941-americas-single-parent-families/

## Conclusion
In conclusion when I evaluated all the factors of location, income, education, and homeownership, I determined that the there is a relationship between all of the factors. 

First, I found that there is a small relationship that suggest densely populated states have more single moms and of those same states, that have a bigger African American population; the single mom percents increase.

Next, as income per capita overall and for African Americans go up, single percent and married percent goes down and vice versa. This suggests that the more money one makes the less of a chance they will become a single mom, however it also means less chance that you will get married.

Finally, the relationship with education is very similar to that of income. As education goes up the percentage of single moms and marriage goes down. Homeownership does have a weak relationship for African American and single mom percents that suggest homeownership lessens the chances of being a single mom. 
