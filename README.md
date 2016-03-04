# World Bank Data Task
This is a semi-regularly updated list of tasks on the World Bank data team's TODO list. Interested in working on them? Apply for a position here: [http://bit.ly/WorldBankData-Jobs](http://bit.ly/WorldBankData-Jobs) 
 
## Automate WDI data ingesting from external sources
The [World Development Indicators](http://data.worldbank.org/products/wdi) is a curated compilation of data from multiple sources. In many cases, data are manually downloaded (as spreadsheets, csv files, databases) from other sites, transformed and loaded into our data management systems for publication. We’d like to look at automating the “download and transform” step and see if there are ways to things like [Data Packages](http://dataprotocols.org/data-packages/) for our most popular indicators.
 
## DataBots - automate data collection for high value datasets
There are certain “high value datasets” that are more commonly used by Bank staff and are required in a timely fashion. We’d like to automate the ingestion of these datasets into our internal data repositories using data scraping or any other data extraction methods.
 
## Extract value added metadata from data catalogs
We curate various datasets and they are made available both internally and [externally in data catalogs](http://datacatalog.worldbank.org/). These datasets are tagged with reference metadata (concepts used, statistics data are  measuring, fitness for use, sampling, collection methods, timeliness, accuracy) and this is often a manual process. Automating metadata tagging will improve discovery of datasets and bring efficiencies to the current curation processes.
 
## Dimensioning of data-structures
Databases are constructed to match a certain standard schema for dissemination purposes (e.g WDI has three dimensions: Country, Series and Time). But there may be oppurutnities to deconstruct the databases to retrieve multi dimensions which will allow for deeper analysis of the database. (e.g - Population tagged with female and male as additional characteristics). Constructing a multidimensional structure that will allow us to use additional characteristics can make for interesting analysis.
 
## Subnational code mapping to GAUL and validation routines
We just [launched a new database](http://blogs.worldbank.org/opendata/new-time-series-global-subnational-population-estimates-launched) of subnational population data. One thing we’ve learned is that working with subnational data is hard: subnational boundaries change much more often than national boundaries and data are published against various coding schemes. Getting on top of the problem with sensible data management and validation routines is a priority.
 
## Build out data site analytics dashboard from Omniture API
It would be awesome to have something like [https://analytics.usa.gov/](https://analytics.usa.gov/) for World Bank Data - we’re currently redesigning the main data site but the analytics system we use (Omniture) will remain the same. Omniture exposes an API of the kinds of data you’d expect (visitors, page views, paths etc.) and having a simple dashboard of what’s popular (perhaps including blogs and social content too) would be great feedback for the team on what to prioritize.
 
## Tableau Connectors for World Bank Data API
Tableau is a popular data visualization tool and supports “connectors” to link to different data sources. They have a [web data connector SDK](https://onlinehelp.tableau.com/current/api/wdc/en-us/help.htm) and writing a connector that talks to our data API (like [these other ones](https://community.tableau.com/thread/178865)) would be a big help to both internal and external Tableau users.
 
## Scrapers and APIs for reference data
There are lots of valuable reference data that aren’t available via APIs or in standard formats for re-use. One example is this [list of national statistics offices (NSOs)](http://unstats.un.org/unsd/methods/inter-natlinks/sd_natstat.asp) published and maintained by the United Nations Statistics Division. It would be great to include a link to NSO websites on each of our [data site’s country pages](http://data.worldbank.org/country), and the easiest way to do that is to
 
## WDI archives database: indicator and code name changes plus metadata extraction
We [released an archived version of the WDI database](http://blogs.worldbank.org/opendata/2015-year-data-time-travel) last year by reading from old files archived in different formats. More needs to be done to track indicator code, name and metadata changes over the years.
 
## System for archiving dataset versions in catalogs
We ventured into tracking versions with the WDI database and would like to expand this function to other datasets and explore the use of [distributed revision control]((http://blog.okfn.org/2010/07/12/we-need-distributed-revisionversion-control-for-data/).) for data.