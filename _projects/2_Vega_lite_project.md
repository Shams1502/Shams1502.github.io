---
name: FinalProject-Group31
tools: [Python, HTML, vega-lite, Altair]
image: assets/pngs/Interactiveplot1.png
description: This is a "showcase" project that uses vega-lite for interactive viz!
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# Data Visualization Final Project
Group 27

Team Members : Shambhavi Sahay(ssahay4), Goura Karn(goura2), Vikramaditya Agarwala(va22)


# Visualization 1

In this visualization, we are trying to plot the rate of all property crimes with the rate of all Violent Crimes. We have used Altair to create the below plot. We have used brush to highlight selection intervals. We have also added color based on the count of the records.

<vegachart schema-url="{{ site.baseurl }}/assets/json/Interactiveplot1.json" style="width: 100%"></vegachart>

# Visualization 2

Below, we have created a non-interactive histogram using altair based on building status and the total square footage. The x-axis has the building status that is an ordinal value and we have specified square footage as quantitative.

<vegachart schema-url="{{ site.baseurl }}/assets/json/jsonBldgStatusVsSquareFootage.json" style="width: 100%"></vegachart>

# Visualization 3 and Visualization 4

Next, we have created two line charts based on the year the building was acquired and the total square footage of the building. We have used the agency name as the legend in both of the visualizations.

For the first visualization we have created a selection based interaction. Upon selection the area gets highlighted.

For the second visualization, the line chart gets highlighted based on the agency selected from the label.

<vegachart schema-url="{{ site.baseurl }}/assets/json/jsonIntYearAcquiredVsSquareFootage.json" style="width: 100%"></vegachart>

<vegachart schema-url="{{ site.baseurl }}/assets/json/jsonLabYearAcquiredVsSquareFootage.json" style="width: 100%"></vegachart>



#References:

https://uiuc-ischool-dataviz.github.io/is445_bcubcg_fall2022/nbv.html?notebook_name=%2Fis445_bcubcg_fall2022%2Fweek13%2FinClass_week13.ipynb
https://uiuc-ischool-dataviz.github.io/is445_bcubcg_fall2022/nbv.html?notebook_name=%2Fis445_bcubcg_fall2022%2Fweek11%2FinClass_week11.ipynb
https://altair-viz.github.io/user_guide/encoding.html#encoding-data-types


