# License
This data was generated using data from the Redistricting Data Hub.  Any use of this project shall also comply with restrictions on use of data and attribution requirements set forth in the Redistricting Data Hub terms and conditions found at: [https://redistrictingdatahub.org/terms-and-conditions/](https://redistrictingdatahub.org/terms-and-conditions/).

Use of this project is further governed by the terms of the [Creative Commons Attribution Noncommercial 4.0 International](https://creativecommons.org/licenses/by-nc/4.0/legalcode.en)

# New Mexico Json and Shapefile

This shapefile was processed by Professor Ellen Veomett and her student Ananya Agarwal using the corresponding jupyter notebook.  As part of the cleaning process, precincts were nested within counties and small rook adjacencies (under 30.5 m) were changed to queen adjacencies.

# **Sources**
All data retrieved 06/09/24:

Obtain the following data from Restricting Data Hub

[Population data](https://redistrictingdatahub.org/dataset/new-mexico-block-pl-94171-2020-by-table/): based on the decennial census at the Census Block level on 2020 Census Redistricting Data

[Congressional District data](https://redistrictingdatahub.org/dataset/2021-new-mexico-congressional-districts-approved-plan/): 2021 New Mexico Congressional Districts plan enacted on 1/13/22

[State House District data](https://redistrictingdatahub.org/dataset/2021-new-mexico-house-of-representatives-districts-approved-plan/): 2021 State House Approved Plan

[State Senate District data](https://redistrictingdatahub.org/dataset/2022-new-mexico-senate-districts-approved-plan/): 2022 State Senate Approved Plan

[2020 election data](https://redistrictingdatahub.org/dataset/vest-2020-new-mexico-precinct-and-election-results/)**:**  VEST 2020 New Mexico precinct and election results

[2018 election data](https://redistrictingdatahub.org/dataset/vest-2018-new-mexico-precinct-and-election-results/)**:**  VEST 2018 New Mexico precinct and election results

[2016 election data](https://redistrictingdatahub.org/dataset/vest-2016-new-mexico-precinct-and-election-results/ )**:**  VEST 2016 New Mexico precinct and election results

[2020 County data](https://redistrictingdatahub.org/dataset/new-mexico-county-pl-94171-2020/): from 2020 Census Redistricting Data (P.L. 94-171) Shapefiles

# **Processing**

Data were cleaned and aggregated in the corresponding jupyter notebook using MGGG’s python library [maup](https://github.com/mggg/maup). 

## Metadata
- `STATEFP20`: State FIPS code
- `COUNTYFP20`: County FIPS code
- `COUNTYNAME20`: County name
- `VTDST20`: Voting tabulation district FIPS code
- `NAME20`: Voting tabulation district name
- `CD`: Congressional district ID
- `SEND`: State Senate district
- `HDIST`: State House district
- `TOTPOP`: Total population in 2020 Census
- `NH_WHITE`: White, non-hispanic, population in 2020 Census
- `NH_BLACK`: Black, non-hispanic, population in 2020 Census
- `NH_AMIN`: American Indian and Alaska Native, non-hispanic, population in 2020 Census
- `NH_ASIAN`: Asian, non-hispanic, population in 2020 Census
- `NH_NHPI`: Native Hawaiian and Pacific Islander, non-hispanic, population in 2020 Census
- `NH_OTHER`: Other race, non-hispanic, population in 2020 Census
- `NH_2MORE`: Two or more races, non-hispanic, population in 2020 Census
- `HISP`: Hispanic population in 2020 Census
- `H_WHITE`: White, hispanic, population in 2020 Census
- `H_BLACK`: Black, hispanic, population in 2020 Census
- `H_AMIN`: American Indian and Alaska Native, hispanic, population in 2020 Census
- `H_ASIAN`: Asian, hispanic, population in 2020 Census
- `H_NHPI`: Native Hawaiian and Pacific Islander, hispanic, population in 2020 Census
- `H_OTHER`: Other race, hispanic, population in 2020 Census
- `H_2MORE`: Two or more races, hispanic, population in 2020 Census
- `VAP`: Total voting age population in 2020 Census
- `HVAP`: Hispanic voting age population in 2020 Census
- `WVAP`: White, non-hispanic, voting age population in 2020 Census
- `BVAP`: Black, non-hispanic, voting age population in 2020 Census
- `AMINVAP`: American Indian and Alaska Native, non-hispanic, voting age population in 2020 Census
- `ASIANVAP`: Asian, non-hispanic, voting age population in 2020 Census
- `NHPIVAP`: Native Hawaiian and Pacific Islander, non-hispanic, voting age population in 2020 Census
- `OTHERVAP`: Other race, non-hispanic, voting age population in 2020 Census
- `2MOREVAP`: Two or more races, non-hispanic, voting age population in 2020 Census
- `ATG18D`: Number of votes for 2018 Democratic attorney general candidate
- `ATG18R`: Number of votes for 2018 Republican attorney general candidate
- `ATG18O`: Number of votes for 2018 other party's attorney general candidate
- `AUD18D`: Number of votes for 2018 Democratic Auditor candidate
- `AUD18R`: Number of votes for 2018 Republican Auditor candidate
- `GOV18D`: Number of votes for 2018 Democratic gubernatorial candidate
- `GOV18R`: Number of votes for 2018 Republican gubernatorial candidate
- `LND18D`: Number of votes for 2018 Democratic Commissioner of Public/State Lands candidate
- `LND18R`: Number of votes for 2018 Republican Commissioner of Public/State Lands candidate
- `LND18O`: Number of votes for 2018 other party's Commissioner of Public/State Lands candidate
- `PRE16D`: Number of votes for 2016 Democratic presidential candidate
- `PRE16R`: Number of votes for 2016 Republican presidential candidate
- `PRE16O`: Number of votes for 2016 other party's presidential candidate
- `PRE20D`: Number of votes for 2020 Democratic presidential candidate
- `PRE20R`: Number of votes for 2020 Republican presidential candidate
- `PRE20O`: Number of votes for 2020 other party's presidential candidate
- `SAC16D`: Number of votes for 2016 Democratic State Appeals Court candidate
- `SAC16R`: Number of votes for 2016 Republican State Appeals Court candidate
- `SAC18D`: Number of votes for 2018 Democratic State Appeals Court candidate
- `SAC18R`: Number of votes for 2018 Republican State Appeals Court candidate
- `SAC20D`: Number of votes for 2020 Democratic State Appeals Court candidate
- `SAC20R`: Number of votes for 2020 Republican State Appeals Court candidate
- `SAC20O`: Number of votes for 2020 other party's State Appeals Court candidate
- `SOS16D`: Number of votes for 2016 Democratic Secretary of State candidate
- `SOS16R`: Number of votes for 2016 Republican Secretary of State candidate
- `SOS18D`: Number of votes for 2018 Democratic Secretary of State candidate
- `SOS18R`: Number of votes for 2018 Republican Secretary of State candidate
- `SOS18O`: Number of votes for 2018 other party's Secretary of State candidate
- `SSC16D`: Number of votes for 2016 Democratic State Supreme Court candidate
- `SSC16R`: Number of votes for 2016 Republican State Supreme Court candidate
- `SSC18D`: Number of votes for 2018 Democratic State Supreme Court candidate
- `SSC18R`: Number of votes for 2018 Republican State Supreme Court candidate
- `SSC20D`: Number of votes for 2020 Democratic State Supreme Court candidate
- `SSC20R`: Number of votes for 2020 Republican State Supreme Court candidate
- `TRE18D`: Number of votes for 2018 Democratic Treasurer candidate
- `TRE18R`: Number of votes for 2018 Republican Treasurer candidate
- `USS18D`: Number of votes for 2018 Democratic senate candidate
- `USS18R`: Number of votes for 2018 Republican senate candidate
- `USS18O`: Number of votes for 2018 other party's senate candidate
- `USS20D`: Number of votes for 2020 Democratic senate candidate
- `USS20R`: Number of votes for 2020 Republican senate candidate
- `USS20O`: Number of votes for 2020 other party's senate candidate
- 
