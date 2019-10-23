## Geopandas Dataviz: State Demographics and the Heartbeat Bill

Georgia Gov. Brian Kemp in early May 2019 signed into law a so-called “heartbeat” bill, banning abortion as early as six weeks into pregnancy. This mini-project aims to use `geopandas` to visualise US state demographics by first scraping state-level data from Wikipedia for up-to-date numbers with `BeautifulSoup` to create choropleth maps. I consider education attainment rates, US House Rep/Dem seats, religiosity, maternal mortality rate, urbanisation rate, and higher education rankings. 

This project can be expanded by using county level data for higher definition, though certain metrics may not be available at the county level. 

#### Getting started

The jupyter notebook `abortion.ipynb` requires the following packages: 
- `numpy`
- `pandas`
- `requests`
- `BeautifulSoup`
- `geopandas`
- `shapely`
- `matplotlib`

The static data files `rural.csv` and `usnewsrank.csv` are required in the complete execution of the notebook. The shape files contained in the directory `states_21basic` were developed by ArcGIS and all files within are required as well. 

#### Deployment

Fork this repository and open `abortion.ipynb` in Jupyter Lab. 

#### Preview

Preview the `abortion.ipynb` notebook by viewing the `abortion.html` export. 
