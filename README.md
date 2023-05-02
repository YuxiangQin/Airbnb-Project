# Installation
In order to plot neighborhood geo maps, `geopandas` package is needed, official instructions can be found [here](https://geopandas.org/en/stable/getting_started.html).
There should be no other necessary libraries to run the code here beyond the Anaconda distribution of Python.
The code should run with no issues using Python versions 3.*.
# Project Motivation
For this project, I was interested in using Airbnb listing data from 2016 and 2017 in Boston and Seattle to better understand:
1. What're the Airbnb listing vibes in different areas in Boston and Seattle?
2. Are there common trends in two cities, and what're the differences in terms of airbnb listings?
3. Price Prediction: By analyzing the Airbnb listings dataset, identify the factors that impact the price of a listing, using those features to build a predictive model for pricing prediction.
# File Descriptions
There are 2 folders contain dataset for Boston and Seattle
- Airbnb data, including `calendar.csv`, `listings.csv`, `reviews.csv` came from Kaggle:
[Boston Airbnb Data](https://www.kaggle.com/datasets/airbnb/boston)
[Seattle Airbnb Data](https://www.kaggle.com/datasets/airbnb/seattle)
- Two neighborhoods `.geojson` data files from government website:
[Boston Neighborhoods Data](https://data.boston.gov/dataset/boston-neighborhoods)
[Seattle Neighborhoods Data](https://data.seattle.gov/dataset/Neighborhood-Map-Atlas-Neighborhoods/h6sh-ea6k)

There are 2 notebooks available here to showcase work related to the above questions. Markdown cells were used to assist in walking through the thought process for individual steps.

There is an additional .py file that runs the necessary code to obtain the final model used to predict salary.
# Results
The main findings of the code can be found at the post available [here](https://medium.com/@qinyuxiangzibet/discovering-the-hidden-gems-of-boston-and-seattle-airbnb-insights-into-neighborhood-vibes-and-ef4c4e0b2801).

# Licensing, Authors, Acknowledgements
Must give credit to Kaggle for the data. You can find the Licensing for the data at the Kaggle link available [here](https://creativecommons.org/publicdomain/zero/1.0/).
Neighborhood data Licensing can be found [here](https://opendatacommons.org/licenses/pddl/summary/).
Otherwise, feel free to use the code here as you would like!

