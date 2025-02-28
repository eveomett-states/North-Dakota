# License
This data was generated using data from the Redistricting Data Hub.  Any use of this project shall also comply with restrictions on use of data and attribution requirements set forth in the Redistricting Data Hub terms and conditions found at: [https://redistrictingdatahub.org/terms-and-conditions/](https://redistrictingdatahub.org/terms-and-conditions/).

Use of this project is further governed by the terms of the [Creative Commons Attribution Noncommercial 4.0 International](https://creativecommons.org/licenses/by-nc/4.0/legalcode.en)

# North Dakota Json and  Shapefile

This shapefile was processed by Professor Ellen Veomett and her student Ananya Agarwal using the corresponding jupyter notebook.  As part of the cleaning process, precincts were nested within counties and small rook adjacencies (under 30.5 m) were changed to queen adjacencies.

# **Sources**
All data retrieved 05/29/24:

Obtain the following data from Restricting Data Hub

[Population data](https://redistrictingdatahub.org/dataset/north-dakota-block-pl-94171-2020-by-table/): based on the decennial census at the Census Block level on 2020 Census Redistricting Data

[State House District data](https://redistrictingdatahub.org/dataset/2021-north-dakota-state-house-of-representatives-approved-plan/): 2021 State House Approved Plan

[State Senate District data](https://redistrictingdatahub.org/dataset/2021-north-dakota-state-senate-approved-plan/): 2021 State Senate Approved Plan

[2020 election data](https://redistrictingdatahub.org/dataset/vest-2020-north-dakota-precinct-boundaries-and-election-results/)**:**  VEST 2020 north-dakota precinct and election results

[2018 election data](https://redistrictingdatahub.org/dataset/vest-2018-north-dakota-precinct-and-election-results/)**:**  VEST 2018 north-dakota precinct and election results

[2016 election data](https://redistrictingdatahub.org/dataset/vest-2016-north-dakota-precinct-and-election-results/)**:**  VEST 2016 north-dakota precinct and election results

[2020 County Data](https://redistrictingdatahub.org/dataset/north-dakota-county-pl-94171-2020/): from 2020 Census Redistricting Data (P.L. 94-171) Shapefiles

# **Processing**

Data were cleaned and aggregated in the corresponding jupyter notebook using MGGG’s python library [maup](https://github.com/mggg/maup). 

# **Metadata**

Below is a brief description of each of the listed variables in the attribute table of the VTD shapefile:

- `STATEFP20`: State FIPS code
- `COUNTYFP20`: County FIPS code
- `PRECINCT20`: Precints
- `SEND`: State Senate district for 2021 State Senate Adopted Plan
- `HDIST`: State House district for 2024 State House of Representatives Districts Plan
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
- `AGR18D`: Number of votes for 2018 Democratic Commissioner of Agriculture candidate
- `AGR18R`: Number of votes for 2018 Republican Commissioner of Agriculture candidate
- `AGR18O`: Number of votes for 2018 other party's Commissioner of Agriculture candidate
- `ATG18D`: Number of votes for 2018 Democratic attorney general candidate
- `ATG18R`: Number of votes for 2018 Republican attorney general candidate
- `ATG18O`: Number of votes for 2018 other party's attorney general candidate
- `AUD16R`: Number of votes for 2016 Republican Auditor candidate
- `AUD16O`: Number of votes for 2016 other party's Auditor candidate
- `AUD20R`: Number of votes for 2020 Republican Auditor candidate
- `AUD20D`: Number of votes for 2020 Democratic Auditor candidate
- `AUD20O`: Number of votes for 2020 other party's Auditor candidate
- `GOV16D`: Number of votes for 2016 Democratic gubernatorial candidate
- `GOV16R`: Number of votes for 2016 Republican gubernatorial candidate
- `GOV16O`: Number of votes for 2016 other party's gubernatorial candidate
- `GOV20D`: Number of votes for 2020 Democratic gubernatorial candidate
- `GOV20R`: Number of votes for 2020 Republican gubernatorial candidate
- `GOV20O`: Number of votes for 2020 other party's gubernatorial candidate
- `HAL16D`: Number of votes for 2016 Democratic US House candidate
- `HAL16R`: Number of votes for 2016 Republican US House candidate
- `HAL16O`: Number of votes for 2016 other party's US House candidate
- `HAL18D`: Number of votes for 2018 Democratic US House candidate
- `HAL18R`: Number of votes for 2018 Republican US House candidate
- `HAL18O`: Number of votes for 2018 other party's US House candidate
- `HAL20D`: Number of votes for 2020 Democratic US House candidate
- `HAL20R`: Number of votes for 2020 Republican US House candidate
- `HAL20O`: Number of votes for 2020 other party's US House candidate
- `INS16D`: Number of votes for 2016 Democratic Insurance Commissioner candidate
- `INS16R`: Number of votes for 2016 Republican Insurance Commissioner candidate
- `INS16O`: Number of votes for 2016 other party's Insurance Commissioner candidate
- `INS20R`: Number of votes for 2020 Republican Insurance Commissioner candidate
- `INS20O`: Number of votes for 2020 other party's Insurance Commissioner candidate
- `PRE16D`: Number of votes for 2016 Democratic presidential candidate
- `PRE16R`: Number of votes for 2016 Republican presidential candidate
- `PRE16O`: Number of votes for 2016 other party's presidential candidate
- `PRE20D`: Number of votes for 2020 Democratic presidential candidate
- `PRE20R`: Number of votes for 2020 Republican presidential candidate
- `PRE20O`: Number of votes for 2020 other party's presidential candidate
- `PSC16D`: number of votes for 2016 Democratic Public Service Commissioner candidate
- `PSC16R`: number of votes for 2016 Republican Public Service Commissioner candidate
- `PSC16O`: number of votes for 2016 other party's Public Service Commissioner candidate
- `PSC18D`: number of votes for 2018 Democratic Public Service Commissioner candidate
- `PSC18R`: number of votes for 2018 Republican Public Service Commissioner candidate
- `PSC18O`: number of votes for 2018 other party's Public Service Commissioner candidate
- `PSC20D`: number of votes for 2020 Democratic Public Service Commissioner candidate
- `PSC20R`: number of votes for 2020 Republican Public Service Commissioner candidate
- `PSC20O`: number of votes for 2020 other party's Public Service Commissioner candidate
- `SOS18D`: Number of votes for 2018 Democratic Secretary of State candidate
- `SOS18O`: Number of votes for 2018 other party's Secretary of State candidate
- `TAX18D`: Number of votes for 2018 Democratic Tax Commissioner candidate
- `TAX18R`: Number of votes for 2018 Republican Tax Commissioner candidate
- `TAX18O`: Number of votes for 2018 other party's Tax Commissioner candidate
- `TRE16D`: Number of votes for 2016 Democratic Treasurer candidate
- `TRE16R`: Number of votes for 2016 Republican Treasurer candidate
- `TRE16O`: Number of votes for 2016 other party's Treasurer candidate
- `TRE20D`: Number of votes for 2020 Democratic Treasurer candidate
- `TRE20R`: Number of votes for 2020 Republican Treasurer candidate
- `TRE20O`: Number of votes for 2020 other party's Treasurer candidate
- `USS16D`: Number of votes for 2016 Democratic senate candidate
- `USS16R`: Number of votes for 2016 Republican senate candidate
- `USS16O`: Number of votes for 2016 other party's senate candidate
- `USS18D`: Number of votes for 2018 Democratic senate candidate
- `USS18R`: Number of votes for 2018 Republican senate candidate
- `USS18O`: Number of votes for 2018 other party's senate candidate
