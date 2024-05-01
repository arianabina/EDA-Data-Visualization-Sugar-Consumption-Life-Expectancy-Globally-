# Sugar Consumption & Life Expectancy

Throughout much of human history, refined sugar consumption was virtually non-existent. However, since the introduction of sugar cane around 2,000 years ago, trends in sugar consumption have increased significantly.

This escalation in sugar consumption has sparked concerns regarding health implications, as sugar consummption is strongly linked to obesity, metabolic diseases, and cardiovascular disease according to medical research. Presently, numerous communities consume nearly 20 percent of their daily caloric intake in the form of sugar, which exceeds daily recommended limits by fourfold.

Therefore, this project seeks to elucidate the broader impact of sugar intake on public health in general-- and more specifically-- to investigate whether countries with higher per capita sugar consumption also experienced lower life expectancies in 2018.


# Data Dictionary

| Feature           | Type            | Dataset   | Description                                                          |
|-------------------|-----------------|-----------|----------------------------------------------------------------------|
|sugar_data_cleaned |float           | Gapminder | Sugar consumption of 166 countries in 2018, measured in grams per day per capita
|population_data_filtered |integer  |Gapminder| population of 166 countries in 2018   | 
|expectancy_data_filtered   |float|Gapminder| Life expectancy of individuals living in 166 different countries in the year 2018


# Executive Summary

The goal of this project is to discern if there is any correlation between high sugar consumption per capita and corresponding lower life expectancies in those countries. Three datasets are used in this study; Firstly, I use data showing per capita sugar consumption around the world in grams per day. Secondly, I use data on life expectancy per country. And lastly, I use data showing population by country. I merged these three datasets and eliminated any null values as well as any data outside the year 2018. Once I narrowed my data down, I was left with 166 countries to analyze. I chose to focus on the year 2018 because this was the most recent data on sugar consumption per capita that my dataset provided. However, to look at how sugar consumption trends have steadily been rising over the 20th century, I used the original dataset showing sugar consumption from 1961 to 2018. 

My exploratory analysis began with identifying outliers. Using a box and whisker plot, I found that three countries were consuming a significantly greater amount of sugar per capita than all of the other countries in my dataset. Those countries were Luxembourg, Fiji, and Montenegro. I then used a scatter plot to look at the relationship between life expectancies and sugar consumption. What I discovered actually did not support my original hypothesis, which was that countries exhibiting extremely high sugar consumption, such as Luxembourg, Fiji, and Montenegro, would also exhibit lower life expectancies than most countries. The data was actually quite mixed. For example, Luxembourg exhibited one of the highest life expectancies at around 83 years old, despite the fact that its constituents clearly consume excessive sugar in their diets. Conversely, countries with low levels of sugar consumption per capita did not necessarily exhibit higher life expectancies as predicted, but rather the data on this was mixed as well. 

In conclusion, it is unclear from my analysis whether or not there is a clear correlation between excessive sugar consumption and life expectancy. For further research and analysis, I would consider the fact that life expectancy is multifactorial and complex. I would take into consideration different factors that may impact health, such as genetics, access to healthcare, socioeconomic status, physical activity, environmental factors, and public health policies and interventions. 

However, I would still recommend that individuals try their best to limit excessive sugar consumption, as there is a clear general consensus within the medical community and literature showing that sugary diets strongly correlate to an increased risk of dying from cardiovascular disease and diabetes. 