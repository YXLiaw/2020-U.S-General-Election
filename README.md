# 2020 U.S General Election : Project Overview (EDA focus)

**Background**
---

**Code and Resources Used**
---
- **Python Version** : 3.7
- **Packages** : pandas, matplotlib, numpy, seaborn, json, warnings, folium
- **Dataset source** : FiveThirthyEight - https://github.com/fivethirtyeight/data/tree/master/election-forecasts-2020
- **U.S states json file** : https://github.com/python-visualization/folium/tree/master/examples/data
- **choropleth map reference** : https://python-graph-gallery.com/292-choropleth-map-with-folium/

**Data Cleaning**
---
After importing the data from csv to data frames, I needed to clean up the data a bit for further analysis by making the following changes:
- Remove redundant and irrelavant columns (i.e variables related to third party candidates are removed, since the data is empty for those columns)
- Remove unwanted non-ASCII characters from string data for "scenario_description" column
- Encoding data for several columns into categorical data.

**EDA**
---
![Prob  distribution](https://user-images.githubusercontent.com/34255556/93668271-ea023e80-fabd-11ea-8c4d-2a3ac4879f6e.png)<br/>
From the shape of both probability distributions, Joe Biden seems to have higher chance to win majority of electoral college votes.

![Likelihood of outcomes](https://user-images.githubusercontent.com/34255556/93668240-cdfe9d00-fabd-11ea-9974-524796456846.png)<br/>

![Tipping](https://user-images.githubusercontent.com/34255556/93668083-ef12be00-fabc-11ea-9a7d-2d0fb67676e7.PNG)<br/>

![Voting Power Index](https://user-images.githubusercontent.com/34255556/93668084-f0dc8180-fabc-11ea-91ce-be468cd88071.PNG)<br/>

![Margin difference](https://user-images.githubusercontent.com/34255556/93668168-80823000-fabd-11ea-96fb-66a4ebad5268.PNG)<br/>

**Usage**
---
This project is best viewed in a notebook render viewer, which can be accessed [here](https://nbviewer.jupyter.org/github/YXLiaw/2020-U.S-General-Election/blob/master/2020%20U.S%20General%20Election.ipynb). In this notebook, you will find a walkthrough of the work and the respective code with comments on observations from figures.

**Legality**
---
This is a personal project made for non-commercial uses ONLY. This project will not be used to generate any promotional or monetary value for me, the creator, or the user.
