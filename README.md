# Biogas-potential-paper-2024

Public repository with parameter values used for a 2024 research article proposing a new framework for determining the technical biomass 
potential for biogas production within a bounded geographic region with high spatial resolution. The parameters were used to apply the 
framework to estimate the technical and the unused technical biogas potential in Bavaria as a case study. The parameters may be used for 
different purposes and geographic regions as well, however caution has to be applied whether the presented parameter values can be applied.
but may be used for different.
Presented volume data refers to 0 °C and 1,013.25 mbar.

# Maintainer
Matthias Steindl. Contact details can be found here: https://www.lfl.bayern.de/ilt/umwelttechnik/technikfolgen/index.php.

# Reference
Put DOI of publication here.

# Description of files and parameters
Directory contains data files as semicolon-separated text files in UTF-8.

| Parameter | Unit | File | Description |
| :--- | :--- | :---: | :---: |
| BMP<sub>b</sub> | m<sup>3</sup>/t<sub>oDM</sub> | `2024-09-07_biomass_biochemical_methane_potential.csv` | Biochemical methane potential of biomasses |
| BU<sub>l</sub> | t<sub>FM</sub>/head | `2024-09-07_livestock_bedding_material.csv` | Bedding material demand depending on livestock |
| CU<sub>p</sub> | % | `2024-09-07_biogas_plants_GGI_capacity_utilization.csv` | Capacity utilization of biomethane gas-grid injection plants |
| DM<sub>b</sub> | % FM | `2024-09-07_biomass_dry_matter_content` | Dry matter content of biomasses |
| \eta<sub>p</sub> | % | `2024-09-07_biogas_plants_CHP_efficiency.csv` | power-weighted electrical efficiency of CHP gas engines depending on CHP gas engine size |
| FU<sub>l</sub> | t<sub>DM</sub>/head | `2024-09-07_livestock_feed_units.csv` | Feed units depending on livestock |
| HR<sub>b</sub> | % | `2024-09-07_crops_harvest_ratio.csv` | Harvest ratio of important harvest by-products from crops |
| HT<sub>l,b,m</sub> | % | `2024-09-07_livestock_housing_type.csv` | Share of housing type depending on livestock and administrative district (location) |
| IPR<sub>p</p> | % | `2024-09-07_biogas_plants_CHP_internal_power_reqirement.csv` | Internal power requirement of biogas plants depending on biogas plant type |
| oDM<sub>b</sub> | % DM  | `2024-09-07_biomass_organic_dry_matter_content.csv` | Organic dry matter content of biomasses |
| RPR<sub>c,b</sub> | - | `2024-09-07_crops_residue_to_product_ratio.csv` | Residue-to-product ratio of crops generating harvest by-products |
| S<sup>BG</sup><sub>p,b,m</sub> | % FM | `2024-09-07_biogas_plants_biomass_share.csv` | Share of biomass in input mix of biogas plants depending on biomass, farming region (location) and biogas plant type |
| S<sup>C,Feed</sup><sub>l,b,m</sub> | % DM | `2024-09-07_livestock_biomass_share.csv` | Share of biomass [%] in feed mix depending on livestock and farming region (location) |
| SI<sub>l,m</sub> | % DM | `2024-09-07_livestock_intercrops_feed.csv` | Share of animal feed per head covered by feed from intercrops, depending on livestock and administrative district (location) |
| ST<sub>l,m</sub> | % | `2024-09-07_livestock_indoor_housing_share.csv` | Livestock stabling period during one year depending on livestock and administrative district (location) |
| Y<sub>c,m</sub> | t<sub>FM</sub>/ha | `2024-09-07_crops_yields.csv` | Yield depending on crop, biomass and administrative district |
| Y<sub>l,b</sub> | t<sub>FM</sub>/head | `2024-09-07_livestock_manure_accumulation.csv` | Manure/slurry accumulation per head [t<sub>FM</sub>/head] depending on livestock |
| Y<sub>p,m</sub> | m<sup>3</sup>/t<sub>oDM</sub> | `2024-09-07_biogas_plants_methane_yield.csv` | Methane yield at full-scale biogas plants depending on farming region (location) and biogas plant type |

# Abbreviations
- BMP: Biochemical methane potential
- BU: Bedding units
- CHP: Combined heat and power
- CU: Capacity utilization
- DM: Dry matter
- FCB: Food/feed-competitive biomass
- FM: Fresh matter
- FU: Feed units
- HR: Harvest ratio
- HT: Housing type
- IPR: Internal power requirement
- LCB: Livestock-competitive biomass
- NCB: Non-competitive biomass
- oDM: Organic dry matter
- RPR: Residue-to-product ratio
- S: Share of biomass
- SI: Share of intercrops
- Y: Yield

# Further resources
