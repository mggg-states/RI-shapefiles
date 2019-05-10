# Providence Census Block Shapefile
This shapefile was obtained from the US Census Bureau and processed by members of the Metric Geometry and Gerrymandering Group (MGGG). 

## Sources
The 2010 census block shapefile for Rhode Island was downloaded from the US Census Bureau’s [TIGER/Line Shapefiles](https://www.census.gov/geographies/mapping-files/time-series/geo/tiger-line-file.html). 2010 Decennial Census demographic data were downloaded from the [Census API](https://api.census.gov/data/2010/dec/sf1). The 2014 Providence City Council ward shapefile was obtained from the [Providence Open Data Portal](https://performance.providenceri.gov/dataset/Wards-2014/mj5h-cv6e). 

## Processing
Blocks were assigned to wards using [MGGG’s proration software](https://github.com/mggg/maup).

## Metadata
* `STATEFP10`: State FIPS code
* `COUNTYFP10`: County FIPS code
* `TRACTCE10`: Census tract FIPS code
* `BLOCKCE10`: Census block FIPS code
* `GEOID10`: Unique Identifier
* `NAME10`: Census block name
* `ALAND10`: Land area in square meters 
* `AWATER10`: Water area in square meters
* `INTPTLAT10`: Latitude of internal point
* `INTPTLON10`: Longitude of internal point
* `TOTPOP`: Total population 
* `NH_WHITE`: White, non-hispanic, population
* `NH_BLACK`: Black, non-hispanic, population
* `NH_AMIN`: American Indian and Alaska Native, non-hispanic, population
* `NH_ASIAN`: Asian, non-hispanic, population
* `NH_NHPI`: Native Hawaiian and Pacific Islander, non-hispanic, population
* `NH_OTHER`: Other race, non-hispanic, population
* `NH_2MORE`: Two or more races, non-hispanic, population
* `HISP`: Hispanic population
* `VAP`: Total voting age population
* `HVAP`: Hispanic voting age population
* `WVAP`: White, non-hispanic, voting age population
* `BVAP`: Black, non-hispanic, voting age population
* `AMINVAP`: American Indian and Alaska Native, non-hispanic, voting age population
* `ASIANVAP`: Asian, non-hispanic, voting age population
* `NHPIVAP`: Native Hawaiian and Pacific Islander, non-hispanic, voting age population
* `OTHERVAP`: Other race, non-hispanic, voting age population
* `2MOREVAP`: Two or more races, non-hispanic, voting age population
* `WARD`: Providence City Council Ward ID
