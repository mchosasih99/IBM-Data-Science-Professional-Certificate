# IBM Data Science Professional Certificate

This is a standalone project completed in order to fulfill the [IBM course certification on Coursera.](https://www.coursera.org/professional-certificates/ibm-data-science)

## Project Background
SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage. Therefore, if we can determine if the first stage will land, we can determine the cost of a launch. This information can be used if an alternate company wants to bid against SpaceX for a rocket launch. The goal of this project is to predict if the first stage of Falcon 9 will land successfully.

## Problem Statement
1. What factors affect the success of landing Falcon 9 in the first stage?
2. The relationship between variables that affect the success rate of the first stage landing of 
Falcon 9

## Methodology
1. Data was collected from Spacexdata API and Wikipedia web scraping.
2. Data wrangling
3. Exploratory data analysis (EDA) using visualization and SQL
4. Interactive visual analytics using Folium and Plotly Dash
5. Predictive analysis using classification models

## Findings
1. The larger the flight number and the lower payload mass leads to better success rate at launch sites.
2. Rocket launch overall success rate has positive trend between 2013-2020,  although had minor negative trend in 2017-2018.
3. Orbit type with most success rate are ES-L1, GEO, HEO, SSO and VLEO.
4. Most successful launch site is KSC LC-39A.
5. All launch site is far from railway, highway, city, and close to coastline.
 Decision Tree is best classification model for this project, with parameters criterion: gini, max_depth: 6, max_features: auto, min_samples_leaf: 2, min_samples_split: 5, splitter: random.
