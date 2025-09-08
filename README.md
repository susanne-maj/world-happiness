# world-happiness
World Happiness Report 2015-2019 and 2024.

Background
The World Happiness Report is the world’s foremost publication on global wellbeing and how to improve it. Wellbeing data from over 140 countries is being combined with high-quality analysis by world-leading researchers from a wide range of academic disciplines. By making the essential insights from wellbeing science accessible to all, the publisher’s goal is to give everyone the knowledge to create more happiness for themselves and others.

Objective
The goal of this analysis is to present different key factors that all have more or less impact on the level of happiness in different countries, and understand the difference between countries that achieve the highest happiness scores, versus countries that achieve the lowest happiness score.  
<img width="4464" height="155" alt="image" src="https://github.com/user-attachments/assets/62998293-584f-410a-91b3-486380f799fa" />

Data
World Happiness Report 2024, World Happiness Reports 2015-2019, world countries geospatial file (world-countries.json). Data preparation included checking the data consistency in Jupyter Lab and if the file included missing values. Some columns appeared twice, so I merged columns in order to make one column out of it. 

Tools
Excel (.csv), Tableau and Jupyter Lab (Python).

Approach 
Data cleaning and merging in Jupyter Lab (Python), dropping of NaN values, visualizations in Tableau. The time series analysis was not so relevant for this kind of data since each data file per year includes an average for the last three years. Since the data is non stationary, it is more suitable to look at the trend over years for specific countries.


