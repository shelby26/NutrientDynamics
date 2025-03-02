# NutrientDynamics

This repository includes all data and analysis to accompany the manuscript:

## Nutrient dynamics in coral symbiosis depend on both the relative and absolute abundance of Symbiodiniaceae species.

**Authors:** Shelby E. McIlroy, Casey terHorst, Mark Teece, Mary Alice Coffroth

**Journal:** *Microbiome (2022) 10:192*
Link: [Article](https://microbiomejournal.biomedcentral.com/articles/10.1186/s40168-022-01382-0)

### Repository contents:

#### Data:

* **data/RecruitsByFilter.csv:** Symbiont community per recruit (Sample). For each sample, qPCR was used to quantify the absolute and relative proportion of S. microadriaticum (NumA), absolute abundance of B. minutum (NumB), and their relative proportion (PercentB). For downstream analyses, 8-12 recruits (Sample) were combined onto a single filter (Filter).

* **data/IsotopesByFilter.csv:** Isotope values were determined for each  of the paired host and symbiont filters. Each row shows the combined data for those filters pairs including: the number of recruits combined onto each filter (NumPolyps), the absolute abundance of S. microadriaticum (NumA), absolute abundance of B. minutum (NumB) and their relative proportion (PercentB), the mean total number of symbionts per recruit (CellsPerPolyp), the Atom Percent of 13Carbon and 15Nitrogen in the host tissue filter (APC_Host & APN_Host), Atom Percent of 13Carbon and 15Nitrogen in the symbiont tissue filter (APC_Sym & APN_Sym), the mean combined new nitrogen (mg) per recruit (CombNewNPolyp).


#### R_script:

* **R_script/NutrientDynamics_analysis.Rmd:** Code and outputs for all analyses
