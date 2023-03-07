# Global Terrorism Dashboard

## Description
A R language based visualization dashboard to see and infer from the trends in terrorism over a long period of time ranging from (start year- end year) in various aspects like region wise,year wise display of data, attack type distribution during an year, region wise deaths, organisation/terror groups causing most damage to public life and property.

## How to run the code
1. Open the file in **RStudio IDE**
2. Install the dependencies by running the following command in R console  
    `install.packages(c("flexdashboard", "readxl", "tidyverse", "shiny" ,"hrbrthemes", "wordcloud", "tm", "treemap", "packcircles", "viridis"))`
3. Click on **knit** in the toolbar to run the code

## Output
- World View Tab  
    Contains four vizualizations, scatterplot on the world map showing the locations on which terrorist attacks took place in the given year, bar chart showing region wise total deaths, doughnut graph showing Top 15 terrorist groups/organisations on the basis on number of fatalities caused and a wordcloud showing most used weapon types.

    ![Screenshot from 2022-04-28 13-02-26](https://user-images.githubusercontent.com/60532223/165757304-0a60daff-5885-4409-8872-ab6fe94a225b.png)

- Country-Wise view Tab  
    On selecting a country and a particular year, four vizualisation appears: line chart which shows number of terror attack incidents over time for the given country, bubble chart showing most terror attack prone regions in a country, treemap denoting the most active terror organisations marked by their areas and a donut chart showing the attack type distribution.

    ![Screenshot from 2022-04-28 13-02-31](https://user-images.githubusercontent.com/60532223/165757323-d0ae2d45-1520-425b-9c6e-c772e4ab74fc.png)
