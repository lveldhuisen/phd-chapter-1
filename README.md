ACCESS INFORMATION
1. MIT License
2. Data derived from other sources: phylogeny from Smith & Brown 2018
3. Recommended citation for this data/code archive


DATA & CODE FILE OVERVIEW

This data repository consist of 14 data files (divided by year of data collection, 1 folder for 2021 and 1 for 2022), 6 code scripts, and this README document, with the following data and code filenames and variables


Data files and variables - all files are formatted to calculate Schoener's Index with the spaa R package. 

    1. sitename_phenology_matrix_year: one column for each species, rows for the number of open flowering units by week.  
    
    2. sitename_fitness_matrix_year: one column for each species, rows for the number of flowering units with fruit from the original flowering week


Code scripts and workflow - code should be run in order listed here. 

    1. SchoenersIndex.R: code to calculate Schoener's Index for phenology and fitness data for all sites and years. This file also contains the code for the Kruskal-Wallis test and figure in Supplemental Material Figure S1. All files for this code are in "files_SchoenersIndex" folder. 
    
    2. network_analysis.R: contains code for the network analyses (modularity and null models), but not code for the network analysis figures (this was done in Gephi). All files to run this code are in the "files_network analysis" folder. 
    
    3. S&B_phylogeneticmetrics_bysite.R: code for community phylogenetic metrics based on the Smith & Brown 2018 phylogeny. Metrics calculated are MPD, MNTD and PD for beginning and SES calculations grouped by elevational site. Files to run this code are in the "files_phylogeneticmetrics_bysite" folder.
    
    4. S&B_phylogeneticmetrics_bymodule.R: code for community phylogenetic metrics based on the Smith & Brown 2018 phylogeny. Metrics calculated are MPD, MNTD and PD for beginning and SES calculations grouped by modules from the network analysis. Files to run this code are in the "files_phylogeneticmetrics_bymodule" folder. 
    
    5. figures.R: contains code for all individual figures. Final figure editing and putting all sites and years together was done in Adobe Illustrator. Files for this code are in the "files_Figures" fodler.
    
    6. fitnessinfo_supplemental.R: contains all the fitness data and calculations for Supplemental Materials Table S1.



SOFTWARE VERSIONS

R: 4.2.3,
bipartite: 2.18,
ape: 5.7-1,
geiger: 2.0.11,
picante: 1.8.2,
ggplot2: 3.4.4,
ggraph: 2.1.0,
tidyverse: 2.0.0,
spaa: 0.2.2,
reshape: 0.8.9,
reshape2: 1.4.4,
readr: 2.1.4,
ggpubr: 0.6.0,
igraph: 1.5.1,
dplyr: 1.1.3,
tidyr: 1.3.0,
vegan: 2.6-4,
Matrix: 1.5-4.1,
pals: 1.7,
viridis: 0.6.4,
polychrome: 1.5.1


REFERENCES

Smith, S. A., and J. W. Brown. 2018. Constructing a broadly inclusive seed plant phylogeny. American Journal of Botany 105:302–314.

