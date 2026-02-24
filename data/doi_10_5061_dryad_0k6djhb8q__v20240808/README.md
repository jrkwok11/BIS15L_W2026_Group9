# Data from: Wood ducks and hooded mergansers as interspecific brood parasites: An evaluation of parasitic egg survival

## Article DOI

[10.1002/ece3.11721](10.1002/ece3.11721)

## Cite this dataset

[https://doi.org/10.5061/dryad.0k6djhb8q](https://doi.org/10.5061/dryad.0k6djhb8q)

Metadata used for evaluating the survival of parasitic wood duck and hooded merganser eggs laid interspecifically; published by Bakner et al. 2024.

This manuscript has been accepted for publication by Ecology and Evolution in 2024.

#### DATAFILES

###### *analysis.R*

This file contains R code that can be used to reproduce the analysis and numbers listed in the results section of manuscript. Stored on Zenodo

###### *cleanData6.6.24.csv*

This file is the data frame that can be read into program R to execute the code file listed above. This data frame contains several columns which are described below:

1. id - nest identifier
2. HOST - nest host with "1" = wood duck and "2" = hooded merganser
3. Nest - type of nest with "WD" = wood duck nest containing only wood duck eggs, "HM" = hooded merganser nest containing on hooded merganser eggs, and "MI" = nests containing both wood duck and hooded merganser eggs
4. type - indicates whether the row contains information on host eggs or parasitic (listed in data frame as "parasite") eggs
5. STUDY - study site identifier
6. State - state identifier
7. clutch - total number of eggs in clutch
8. hatch - total number of eggs that hatched from clutch
9. total_clutch - total number of eggs in clutch (i.e., host and parasitic combined)
10. NESTFATE - indicates weather the nest hatched at least 1 egg or failed completely
11. inc - indicates weather a clutch was incubated or not
12.  BOX_TYPE - indicates nest box size

