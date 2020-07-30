[![CraigDoesData][logo]][link]

[logo]: https://www.craigdoesdata.de/img/logo/logo.png
[link]: https://www.craigdoesdata.de/

# Mapping Avocado Prices in the US using Python - GeoPandas, GeoPy and Matplotlib
Data Analysis project mapping price data for avocados onto a map of the USA.


See the [blog post](https://towardsdatascience.com/mapping-avocado-prices-in-python-with-geopandas-geopy-and-matplotlib-c7e0ef08bc26) that accompanies this analysis on [Towards Data Science](https://towardsdatascience.com/mapping-avocado-prices-in-python-with-geopandas-geopy-and-matplotlib-c7e0ef08bc26).

#### Project status - Complete

## Introduction
The purpose of this project was to take price data for avocados and to create an attractive and understandable visualisation representing that. I wanted to get to grips with creating maps in Matplotlib, as well as using geocoding locations - taking addresses in text form and finding their coordinates, enabling them to be represented spatially.

I also wanted to take the opportunity to pickle some data so I could gain some experience with this technique, and pull data into my notebook using APIs.

### Methods used
* EDA
* Data visualisation
* Geocoding
* Geographical mapping

### Technologies used
* Jupyter Notebook
* pandas
* Geopandas
* Geopy
* Matplotlib
* Shapely
* pickle


### Data Sources
<details>
  <summary>See Details</summary)
    <br>
Avocado price data sourced from [Kaggle](https://www.kaggle.com/neuromusic/avocado-prices) - stored [here](https://github.com/thecraigd/Avocado-Prices/blob/master/data/avocado.csv) as avocado.csv
Shape file sourced from [United States Census Bureau](https://catalog.data.gov/dataset/tiger-line-shapefile-2017-nation-u-s-current-state-and-equivalent-national) - these can be found in the [shape_files](https://github.com/thecraigd/Avocado-Prices/shape_files) folder of this repository
Get your own Bing Maps API Key [here](https://docs.microsoft.com/en-us/bingmaps/getting-started/bing-maps-dev-center-help/getting-a-bing-maps-key)
</details>

### Getting started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw Data is kept in the CSV file in the root folder of this repo.
3. All code is contained within the [Jupyter Notebook](https://github.com/thecraigd/Avocado-Prices/blob/master/Avocado%20Prices.ipynb) for this project, stored in the root folder as Avocado Prices.ipynb


## Featured Notebooks
* [Avocado Prices](https://github.com/thecraigd/Avocado-Prices/blob/master/Avocado%20Prices.ipynb)

* [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/thecraigd/Avocado-Prices/master)

## Contact
All feedback is warmly received. Craig Dickson can be contacted via his website [craigdoesdata.de](https://www.craigdoesdata.de/contact.html).
