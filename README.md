# Eastern quoll trials and tactics

Here we describe the analyses conducted for our journal article [Wilson *et al.* (2020) Adapting reintroduction tactics in successive trials increases the likelihood of establishment for an endangered carnivore in a fenced sanctuary](https://doi.org/10.1371/journal.pone.0234455). 

The original script and datasets for these analyses are also available at [ANU Data Commons](https://datacommons.anu.edu.au/DataCommons/rest/display/anudc:6063).

## Abstract

Threatened species recovery programs are increasingly turning to reintroductions to reverse biodiversity loss. Here we present a real-world example where tactics (techniques which influence post-release performance and persistence) and an adaptive management framework (which incorporates feedback between monitoring and future actions) significantly improved reintroduction success. 

Across three iterative trials we investigated the influence of tactics on the post-release performance of endangered eastern quolls (*Dasyurus viverrinus*) reintroduced to a [conservation-fenced haven](https://www.coexistenceconservationlab.org/mulligans-flat-goorooyarroo-woodland-experiment) in the Australian Capital Territory. We monitored eastern quoll founders for 42 days post-release, and tested their probability of survival and post-release dispersal against trial number, origin, sex, proportion of time spent den sharing, and presence of pouch young. 

Founders released in the first trial were less likely to survive (28.6%, *n* = 14) than those founders released the second (76.9%, *n* = 13) and third trials (87.5%, *n* = 8). We adapted several tactics in the second and third trials, including the selection of female-only founders (preferring those that were maternal) to avoid elevated male mortality, and releases after the mating period to reduce stress. Founders that moved dens between consecutive nights were less likely to survive, and the probability of an animal moving dens was lower in the second and third trials, for females, and when an animal den shared with another founder.

Our study demonstrated that, through iterative trials of tactics involving monitoring and learning, adaptive management can be used to significantly improve the success of reintroduction programs.

## Repository structure

This repository follows an organised structure for clarity and reproducibility:
- `input` folder: contains datasets required for analyses (e.g., raw data tables, geospatial data files, etc.).
- `output` folder: contains datasets generated from these analyses (e.g., processed data tables, maps, plots, etc.).
- `.gitattributes`: manages repository-specific configurations.
- `.gitignore`: specifies intentionally untracked files to be ignored by Git (e.g., large files or sensitive information).
- `analyses.Rmd`: R markdown containing the workflow for the project's analyses, including narrative text, code, and results.
- `project.Rproj`: RStudio Project file for managing the R environment to ensure consistent working directories and settings.
- `README.md`: provides an overview of the repository and instructions for usage (i.e., what you're reading right now).
- `tutorial.html`: rendered HTML output of the `analyses.Rmd` markdown, serving as a shareable tutorial that summarises the project's analyses and results.r