# World Bank Data Task

## Automate WDI data ingesting from external sources
The World Development Indicators is a curated compilation of data from multiple sources. In many cases, data are manually downloaded (as spreadsheets, csv files, databases) from other sites, transformed and loaded into our data management systems for publication. We’d like to look at automating the “download and transform” step and see if there are ways to things like Data Packages  for our most popular indicators.

## DataBots - automate data collection for high value datasets
There are certain “high value datasets” that are more commonly used by Bank staff and  required in a timely fashion. We’d like to automate the ingestion of these datasets into our internal data repositories using data scraping or any other data extraction methods. 

## Extract value added metadata from data catalogs
We curate various datasets and they are made available both internally and externally in data catalogs. These datasets are tagged with reference metadata (concepts used, statistics data are  measuring, fitness for use, sampling, collection methods, timeliness, accuracy) and this is often a manual process. Automating metadata tagging will improve the discovery of datasets and bringing efficiencies to the current curation and bring efficiencies to the current curation processes. 

## Dimensioning of data-structures
Databases are constructed to match a certain standard schema for dissemination purposes (e.g WDI has three dimensions: Country, Series and Time). But the databases may be deconstructed to retrieve multi dimensions who will allow for deeper analysis of the database. (e.g - Population has female and male are additional characteristics). Constructing a multidimensional structure that will allow us to track these characteristics will be extremely useful for interesting analysis. 

## Subnational code mapping to GAUL and validation routines
We just launched a new database of subnational population data. One thing we’ve learned is that working with subnational data is hard: subnational boundaries change much more often than national boundaries and data are published against various coding schemes. Getting on top of the problem with sensible data management and validation routines is a priority.

## Build out data site analytics dashboard from Omniture API
It would be awesome to have something like https://analytics.usa.gov/ for World Bank Data - we’re currently redesigning the main data site but the analytics system we use (Omniture) will remain the same. Omniture exposes an API of the kinds of data you’d expect (visitors, page views, paths etc.) and having a simple dashboard of what’s popular (perhaps including blogs and social content too) would be great feedback for the team on what to prioritize. 

## Tableau Connectors for World Bank Data API
Tableau is a popular data visualization tool and supports “connectors” to link to different data sources. They have a web data connector SDK and writing a connector that talks to our data API (like these other ones) would be a big help to both internal and external Tableau users. 

## Scrapers and APIs for reference data
There are lots of valuable reference data that aren’t available via APIs or in standard formats for re-use. One example is this list of national statistics offices (NSOs) published and maintained by the United Nations Statistics Division. It would be great to include a link to NSO websites on each of our data site’s country pages, and the easiest way to do that is to

## WDI archives database: indicator and code name changes plus metadata extraction
We released an archived version of the WDI database last year by reading from old files archived in different formats. More needs to be done to track indicator code, name and metadata changes over the years. 

## System for archiving dataset versions in catalogs
We ventured into tracking version with the WDI database and would like to expand this function to other datasets. 

