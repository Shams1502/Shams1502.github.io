---
name: FinalProject-Group27
tools: [Python, HTML, vega-lite, Altair]
image: assets/pngs/Interactiveplot1.png
description: Crime Data Analysis for the States
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# Stats of the States: State Crime Analysis
Group 27

Team Members : Shambhavi Sahay(ssahay4), Goura Karn(goura2), Vikramaditya Agarwala(va22)

# Introduction

In the United States, crime has always been a problem. Although the country has relatively high crime rates, they have dramatically declined over the previous 25 years. About 47.70 crimes are committed against every 100,000 people in the US. The American government has two categories for crime. Either a violent crime or a property crime is considered a criminal conduct. A violent crime is one that involves four criminal acts: assault, robbery, intentional or unintentional homicide, and rape. The property crime includes criminal acts like burglary, larceny and motor vehicle harm.

Some of the elements that are known to have an impact on the quantity and nature of crime in a given area include:
1. Urbanization level and population density
2. Demographics of the area
3. The influence of resident mobility, travel habits, and temporal factors on population stability
4. Cultural aspects, including educational, recreational, and religious qualities. - Economic conditions, including median income, poverty level, and capacity to work



# Visualization 1

We have created this interactive plot using the dataset that was made available by the Unified Crime Reporting Statistics and a partnership between the Federal Bureau of Investigation and the U.S. Department of Justice.

Link to dataset: https://think.cs.vt.edu/corgis/datasets/csv/state_crime/state_crime.csv 

<vegachart schema-url="{{ site.baseurl }}/assets/json/interactive1.json" style="width: 100%"></vegachart>



It has data from the year 1960 to the year 2019 about the state the crime took place in, population of the state at the time of the crime, rates of different property and violent crimes. 

(The number of reported offenses per 100,000 people is referred to as a rate.)

Here, we tried finding the relation between the rate of property crime and violent crime based on the population and state. We have also included a slider from where we can select the year for which the crime was reported.  From the graph it can be inferred that the rate of both property and violent crime decreased over the years. It can also be said that Maine, New Hampshire, North Dakota, West Virginia had the lowest crime rates over the years. In the year 1960, California had the highest rate of property crime while Illinois took the lead in violent crime rates. But over the years, both California and Illinois had become a safer place to live in. 

# Visualization 2

From this visualization we can see that although the total violent and property crime is higher for California, the rate at which these crimes are committed is the highest in District of Columbia. This can be because of the higher population of California. 

<vegachart schema-url="{{ site.baseurl }}/assets/json/Multiselect1.json" style="width: 100%"></vegachart>

<vegachart schema-url="{{ site.baseurl }}/assets/json/Multiselect2.json" style="width: 100%"></vegachart>

<vegachart schema-url="{{ site.baseurl }}/assets/json/Multiselect3.json" style="width: 100%"></vegachart>

<vegachart schema-url="{{ site.baseurl }}/assets/json/Multiselect4.json" style="width: 100%"></vegachart>


# Visualization 3 

With this visualization we tried categorizing all the states that had similar crime rates. From the visualization it can be inferred that California, New York and Illinois had similar crime rates i.e the rates were on the higher side whereas states like Kentucky, North Dakota and West Virginia have smaller crime rates and thus safer place to live in. 

<vegachart schema-url="{{ site.baseurl }}/assets/json/binned.json" style="width: 100%"></vegachart>



# References:

1. https://uiuc-ischool-dataviz.github.io/is445_bcubcg_fall2022/nbv.html?notebook_name=%2Fis445_bcubcg_fall2022%2Fweek13%2FinClass_week13.ipynb
2. https://uiuc-ischool-dataviz.github.io/is445_bcubcg_fall2022/nbv.html?notebook_name=%2Fis445_bcubcg_fall2022%2Fweek11%2FinClass_week11.ipynb
3. https://altair-viz.github.io/user_guide/encoding.html#encoding-data-types
4. https://uiuc-ischool-dataviz.github.io/is445_bcubcg_fall2022/nbv.html?notebook_name=%2Fis445_bcubcg_fall2022%2Fweek13%2FinClass_week13.ipynb
5. https://uiuc-ischool-dataviz.github.io/is445_bcubcg_fall2022/nbv.html?notebook_name=%2Fis445_bcubcg_fall2022%2Fweek11%2FinClass_week11.ipynb
6. https://altair-viz.github.io/user_guide/encoding.html#encoding-data-types
7. https://worldpopulationreview.com/state-rankings/crime-rate-by-state
8. https://www.statista.com/statistics/200445/reported-violent-crime-rate-in-the-us-states/



