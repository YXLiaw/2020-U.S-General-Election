# 2020 U.S General Election : Project Overview

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

**Usage**
---
This project is best viewed in a notebook render viewer, which can be accessed [here](https://nbviewer.jupyter.org/github/YXLiaw/2020-U.S-General-Election/blob/master/2020%20U.S%20General%20Election.ipynb). In this notebook, you will find a walkthrough of the work and the respective code with comments on observations from figures.

**Legality**
---
This is a personal project made for non-commercial uses ONLY. This project will not be used to generate any promotional or monetary value for me, the creator, or the user.
