# Soil and crop management for climate-smart soils

This repository is part of the [EJP SOIL CLIMASOMA project](https://ejpsoil.eu/soil-research/climasoma/).

This work aims at creating an integrative literature review on the effect of agricultural practices on sustainable soil water management in Europe. For this we selected multiple meta-analysis using the followig query string:

`soil AND meta-analysis NOT forest NOT urban AND (management OR tillage OR cropping OR crops OR crop OR (cover and crops) OR (catch and crop) OR residue OR residues OR fertilizer OR manure OR amendment OR liming OR compost OR traffic OR biochar OR irrigation OR intercropping OR agroforestry) AND (hydraulic conductivity OR water retention OR available water OR runoff OR infiltration OR bulk density OR macroporosity OR penetration resistance OR soil strength OR aggregate stability OR aggregation OR yields OR organic matter OR organic carbon OR (microbial OR faunal OR earthworm) AND (biomass OR activity) root AND (depth or biomass or growth))`

These meta-analysis were after analysed in terms to extract the relationships between drivers and variables. The quality of the meta-analysis was also evaluated using method from [Beillouin et al. (2019)](https://doi.org/10.1016/j.dib.2019.103898)

This folder contains:
- [CLIMASOMA meta-analysis.xlsx](CLIMASOMA%20meta-analysis.xlsx): contains references of the meta-analysis, information about the quality assessment and relationships between extracted drivers and variables
- [notebooks/meta-graph.ipynb](notebooks/meta-graph.ipynb): Figures to display the relationships between drivers and variables and the results of the quality assessement
- `meta/*`: folders with the excel files containing the references of the primary studies for selected meta-analyses.
- [notebooks/redundancy.ipynb](notebooks/redundancy.ipynb): Redundancy analysis similar to Beillouin et al. (2019) based on the references used in the meta-analysis and stored in separated file in the `meta` directory.

## Citation
Refer to this citation if you make use of the database:
```
CLIMASOMA authors, 2022 "Open-source Tension-disk Infiltrometer Meta-Databse (OTIM-DB)" CLIMASOMA report.
```
