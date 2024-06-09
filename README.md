# New Mexico Election Shapefile

This shapefile was processed by Professor Ellen Veomett and her student Ananya Agarwal.

# **Sources**
@author: eveomett AI for Redistricting, USF All data retrieved 06/09/24:

Obtain the following data from Restricting Data Hub

[Population data](https://redistrictingdatahub.org/dataset/new-mexico-block-pl-94171-2020-by-table/): based on the decennial census at the Census Block level on 2020 Census Redistricting Data

[Congressional District data](https://redistrictingdatahub.org/dataset/2021-new-mexico-congressional-districts-approved-plan/): 2021 New Mexico Congressional Districts plan enacted on 1/13/22

[State House District data](https://redistrictingdatahub.org/dataset/2021-new-mexico-house-of-representatives-districts-approved-plan/): 2021 State House Approved Plan

[State Senate District data](https://redistrictingdatahub.org/dataset/2022-new-mexico-senate-districts-approved-plan/): 2022 State Senate Approved Plan

[2020 election data](https://redistrictingdatahub.org/dataset/vest-2020-new-mexico-precinct-and-election-results/)**:**  VEST 2020 New Mexico precinct and election results

[2018 election data](https://redistrictingdatahub.org/dataset/vest-2018-new-mexico-precinct-and-election-results/)**:**  VEST 2018 New Mexico precinct and election results

[2016 election data](https://redistrictingdatahub.org/dataset/vest-2016-new-mexico-precinct-and-election-results/ )**:**  VEST 2016 New Mexico precinct and election results

# **Processing**

Demographic data were aggregated from the census block level and precincts were assigned to districts using [MGGG's proration software](https://github.com/mggg/maup). Election data were also prorated onto VTDs from the original precinct shapefile using the `maup` package.

### Metadata ###

* `NAME10`: Name of precinct
* `Prec_num`: Precinct number
*	`County`: Precinct county
*	`AG18D`: Number of votes for the 2018 Democratic Attorney General candidate
*	`AG18R`: Number of votes for the 2018 Republican Attorney General candidate
*	`AG18L`: Number of votes for the 2018 Libertarian Attorney General candidate
*	`SOS18D`: Number of votes for the 2018 Democratic Secretary of State candidate
*	`SOS18R`: Number of votes for the 2018 Republican Secretary of State candidate
*	`SOS18L`: Number of votes for the 2018 Libertarian Secretary of State candidate
*	`SEN18D`: Number of votes for the 2018 Democratic Senate candidate
*	`SEN18R`: Number of votes for the 2018 Republican Senate candidate
*	`SEN18L`: Number of votes for the 2018 Libertarian Senate candidate
*	`GOV18D`: Number of votes for the 2018 Democratic Governor candidate
*	`GOV18R`: Number of votes for the 2018 Republican Governor candidate
*	`PRES16D`: Number of votes for the 2016 Democratic Presidential candidate
*	`PRES16R`: Number of votes for the 2016 Republican Presidential candidate
*	`PRES16L`: Number of votes for the 2016 Libertarian Presidential candidate
*	`SOS16D`: Number of votes for the 2016 Democratic Secretary of State candidate
*	`SOS16R`: Number of votes for the 2016 Republican Secretary of State candidate
*	`CDDIST`: 2011 enacted US congressional district ID
*	`HDIST`: 2011 enacted State House district ID
*	`SDIST`: 2011 enacted State Senate district ID
*	`Area`: Area of precinct in square meters
*	`Perimeter`: Perimeter of precinct in meters
*	`TOTPOP`: Total population
*	`NH_WHITE`: White, non-hispanic, population
*	`NH_BLACK`: Black, non-hispanic, population
*	`NH_AMIN`: American Indian and Alaska Native, non-hispanic, population
*	`NH_ASIAN`: Asian, non-hispanic, population
*	`NH_NHPI`: Native Hawaiian and Pacific Islander, non-hispanic, population
*	`NH_OTHER`: Other race, non-hispanic, population
*	`HISP`: Hispanic population
*	`H_WHITE`: White, hispanic, population
*	`H_BLACK`: Black, hispanic, population
*	`H_AMIN`: American Indian and Alaska Native, hispanic, population
*	`H_ASIAN`: Asian, hispanic, population
*	`H_NHPI`: Native Hawaiian and Pacific Islander, hispanic, population
*	`H_OTHER`: Other race, hispanic, population
*	`VAP`: Total voting age population
*	`HVAP`: Hispanic voting age population
*	`WVAP`: White, non-hispanic, voting age population
*	`BVAP`: Black, non-hispanic, voting age population
*	`AMINVAP`: American Indian and Alaska Native, non-hispanic, voting age population
*	`ASIANVAP`: Asian, non-hispanic, voting age population
*	`NHPIVAP`: Native Hawaiian and Pacific Islander, non-hispanic, voting age population
*	`OTHERVAP`: Other race, non-hispanic, voting age population
*	`2MOREVAP`: Two or more races, non-hispanic, voting age population

## Projection 
This shapefile uses a WGS84/UTM zone 13N projection (EPSG: 32613).