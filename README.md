# SSHS Snackbot Backend

## Setup

### prerequisities
Make sure you installed python. When using windows, install unix tools and git bash from git.

### Initial setup
Clone this repository and install all dependencies:

```shell
$ git clone https://github.com/coinmoles/snack-backend.git
$ cd push-backend
$ pip install -r requirements.txt
```

You need co2 emission data, global car sales data, and global electric car sales data for this code to function properly. Download them from the links below
|Data|Type|Link|
|--|--|--|
|CO2 Emissions per capita|csv|https://ourworldindata.org/co2/country/united-states?country=|
|Global electric car sales by key markets, 2010-2020|csv|https://www.iea.org/data-and-statistics/charts/global-electric-car-sales-by-key-markets-2015-2020|
|Global car sales by key markets, 2005-2020|csv|https://www.iea.org/data-and-statistics/charts/global-car-sales-by-key-markets-2005-2020|

Create a folder named "data" at the root of your project folder, and place the data files inside it.

```shell
$ mkdir data
$ mv "Your Data Location" /data
```
