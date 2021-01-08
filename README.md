# fintech_group_assignment_1
## Presentation Plan

### Presenter 1
Motivation
Try to underatand whether there is a correlation between air quality data and stock market, in the the world's most populous countries (or the biggest economies), and Australia.

We took into account environment polutants such as **co, so2, o3, pm10 and pm25** etc.
In the end we decided that **co** is the most relevant polutant.

The stock market data was acquired through the Yahoo finance API, and was limited to 2019 and 2020.
The attempt was to detect any correlation between the two years as well, taking in to account the bushfires in Australia and the resctricted industrial activities due to the global pandemic.

### Presenter 2
Introduce the polutant datasets, data cleansing and charts.
The team then continued on to cleanse the data.
Reduced the dataset size by:
* Removing the countried we were not considering
* Removing the cities that were too small or irrelavant
* Removed to the polutant species that we were not interested in
* Restricted the stock market data to the main indices of each country only

We used a few intermediate graphs to visualise the data (describe)

### Presenter 3
Introdcing the dashboard!
Let's talk through the 2 sets of graphs - 2020 and 2019.
We can compare correlations among contries and years.
As per the graphs you can see the impact of Covid on the environmental polutants as well as the market.
It's evident from the 3rd graph - conclusion was that the correlation was spurious - and we either need a diffrent rolling window to see any correlation.

### Possible Enhancements
We believe there are huge oppertunities to enhance the investigation, but picking more relevant (industrial stocks such as airlines) etc


Country | CO2 | NO2 | P10 |
--- | --- | --- | --- | --- |
GSPC  | -   | -   | - | - |
BSESN  | -   | -   | - | - |
000001.SS  | -   | -   | - | - |
N225  | -   | -   | - | - |
FTSE  | -   | -   | - | - |
AXJO  | -   | -   | - | - |
