# The US Housing Market vs. Covid-19

[Main Page](https://tnh333.github.io/covidhousingmarket/index.html)

**Team Members:** Tim Hahn, Justin Lee, Tianhao Yao, Fangge Xiong, Angel Diaz 

**Teachers:** Bo Zhao, Steven Bao

**Project Idea:**
After going over our project together when working on the design project prototype we recognized the topic we selected and project method we chose did not align. We decided to move away from the geo-narrative format and move toward a generic digital geographies project that will better represent our data. Since our data is on the housing market in the US pre and post covid we figured it would be best to use this format while also including some external resources and data along the side to give the maps more context. 

**Significance:**
The significance of this project is to show any changes within this market before and after covid, while also comparing the East and West coast markets. This will be beneficial for buyers and sellers to find the best place to participate in the market. Also, people interested in this topic can draw conclusions about the East and West markets.

**Broader Impact:**
Some negatives that could come from this project are highlighting areas where the market is worse which could force the market in this area to continue to decline and the areas where it is good will improve. To avoid this, we can use a sequential color scale in our choropleth maps. For example, we could use blue so that way the appearance of good or bad within colors are absent and the colors will just be lighter and darker. While this will give the same effect and display the data properly, it will also bring less attention to worse areas. 

**Data Sources:**
-	[Demographic information from United States Census Bureau](https://www.census.gov/data/tables.html)
-	[US Household Income Statistics from Kaggle](https://www.kaggle.com/datasets/goldenoakresearch/us-household-income-stats-geo-locations?select=kaggle_income.csv)
-	[Housing Statistics from data.world](https://data.world/adv34715/housing-price-and-population-change/workspace/file?filename=State_Zhvi_AllHomes.csv)
-	[Redfin Housing Market from Kaggle](https://www.kaggle.com/datasets/thuynyle/redfin-housing-market-data/code?select=state_market_tracker.tsv000)
-	[US County Database from simplemaps.com](https://simplemaps.com/data/us-counties)

**Primary Functions:**
Provide user interactive panels on the top that allows users to filter the data based on the areas income, property tax, and demographic per area.
Visualize the housing market change on the map of the US: the East Coast and the West Coast
Present detailed text descriptions and different multimedia via scroll on the left panel which guides the user to understand the whole picture of the East Coast and West Coast housing market pre and post covid.

**Targeted Audience:**
Our target audience is people who are interested in the US housing market, or possibly those who may be looking to enter this market whether buying or selling. 

**Multimedia:**
Some of the multimedia we will use are pictures of certain areas to show what the housing looks like in a particular area, so the viewer understands what the houses look like in person. We will also have some graphs that show change in the market over time. 

**Project Format:**
-	Projection: Mercator projection 
-	Map Zoom level: 3 (US Continent) - 15 (Buildings)
-	Map Center: 	47.116386, -101.299591 (US)
-	41.188981, -114.088269 (West Coast) 
-	37.211001, -81.401026 (East Coast)
-	Base Map: We plan to use a plain dark base map such as mapbox://styles/mapbox/dark-v10. Since our topic is housing market, a dark base map will provide better color contrast for readability.

**Layers:** the layers our map will have are, general US housing market (choropleth or proportional symbol), pre covid west (choropleth or proportional symbol),  post covid west (choropleth or proportional symbol),  pre covid east (choropleth or proportional symbol),  and post covid east (choropleth or proportional symbol). This will be shown through clickable buttons along the side of our map. Those layers will be generated using the Redfin Housing Market 2012-2021 data set joining the US County Database to acquire the geography data column.
