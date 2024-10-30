# Oregon Congressional Districts

Project Criteria:
- Use the most recently available American Community Survey (ACS) data. At the time of analysis, this is the 2022 5-year survey data.
- Prioritize a “least change” approach, meaning creating a map with as little change to the current Congressional map (enacted 2022) as possible.
- Analyze the potential and performance of majority-minority districts using reconstructed 2020 election data

************

Code

- [OR_CD-MCMC-area_diff.ipynb](https://github.com/kkakey/rrep/blob/main/Mapping/oregon_congressional/OR_CD-MCMC-area_diff.ipynb) - code used to generate a sample of redistricting plans that optimize for plans that minimize area displacement
- [OR_CD-MCMC-gingles.ipynb](https://github.com/kkakey/rrep/blob/main/Mapping/oregon_congressional/OR_CD-MCMC-gingles.ipynb) - code used to generate a sample of redistricting plans that optimize for plans with a Gingles I majority-minority district
- [exploratory-county_level](https://github.com/kkakey/rrep/blob/main/Mapping/oregon_congressional/exploratory-county_level.ipynb) - exploratory analysis of population changes from 2020 to 2022 as well as population estimates in 2030

************

Maps

- Illustrative plan prioritizing a least change approach from the 2022 enacted map (utilizing 2022 ACS population data)
<p align="center">
<img src="https://raw.githubusercontent.com/kkakey/rrep/refs/heads/main/Mapping/oregon_congressional/output_area_diff/plan1-11252.png" width="400" >
</p>

- It is impossible to generate a map that allows for a majority-minority district in Oregon utilizing 2022 ACS population data

************

On Dave's Redistricting App:
- [Plan 1](https://davesredistricting.org/join/32da3ab4-add4-4703-a7b2-0d97465fcfb4)