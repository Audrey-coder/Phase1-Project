# Phase1-Project
**Author:** Audrey Nyanduko Kiage
## Overview
The company is diversifying its portfolio by entering the aviation industry. Specifically, they aim to purchase and operate airplanes for both commercial and private purposes. However, they lack expertise regarding the risks associated with different aircraft models.
## Business Problem
The company is expanding into the aviation industry and requires data-driven insights to determine which aircraft models pose the lowest risk for commercial and private operations. Your role is to evaluate historical data on aircraft safety and performance under varying conditions. The goal is to provide actionable recommendations that help the company select the safest aircraft models for their new business venture.
## Data
The dataset contains information from 1962 and later about civil aviation accidents and selected incidents within the United States, its territories and possessions, and in international waters.
## Methods
This project uses descriptive analysis, including description of trends over time. This provides a useful overview of the civil aviation accidents.
## Results
Most aircrafts have experience a very minimal number of accidents.
![Top 50](./Images/Top-50-Aircrafts-vs-no-of-accidents.png)

The number of aircraft accidents typically peek in the summer months(June,July,August) and hits its lowest point in January.
![Months](./Images/Months-against-no-of-accidents.png)

Most aircraft damages are substantial and happen during VMC(Visual Meteorological Conditions) weather conditions. Hence care should be taken during such times
![Aircraft](./Images/Aircraft-Damage-by-weather-Condition.png)
## Conclusions
This analysis leads to three recommendations for the company to consider:
*  Focus on acquiring aircraft models with a history of low accident frequency and high durability under diverse conditions.
*  Prepare for and mitigate seasonal risks through strategic scheduling and enhanced training during high-risk months.
*  Enhance safety protocols for flights during adverse weather to reduce the impact of severe damage and accidents
## Next Steps
Further analyses could yield additional insights to help the company make the decision:
*  Predictive Modeling: Use machine learning techniques to predict future accident rates based on historical data, weather conditions, and aircraft attributes.
*  Cost-Benefit Analysis: Compare the cost of acquisition, maintenance, and potential accident-related costs for different aircraft models.
*  Seasonal Simulations: Simulate accident scenarios under different seasonal and weather conditions to identify potential mitigation strategies.
# For More Information
See the full analysis in [jupyter notebook](./index.ipynb) or review this [presentation]
You can find the tableau dashboard [here](https://public.tableau.com/views/Dashboard_17323829453600/Dashboard?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
