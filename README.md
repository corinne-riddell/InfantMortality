# Understanding the recent increase in black infant mortality in the US
### Corinne A Riddell, [Sam Harper](samharper.org), and [Jay S Kaufman](jayskaufman.com)

This repository contains the data, code, and R markdown version of a research letter submitted to *JAMA Pediatrics* on January 16th, 2017. The research letter was revised and resubmitted on March 28th, and accepted for publication on March 29th, 2017. Here is the DOI, if you'd like to cite this work: [![DOI](https://zenodo.org/badge/76671514.svg)](https://zenodo.org/badge/latestdoi/76671514)

To view the R markdown version of this letter, please navigate to [InfantMortality/Code/Examine_Trends.md](https://github.com/corinne-riddell/InfantMortality/blob/master/Code/Examine_Trends.md).

### Overview
The infant mortality rate is an important indicator of population health. A recent report from the Centers for Disease Control and Prevention reported that the US infant mortality rate decreased by 15% in the past decade. The objective of this research letter is to establish if both blacks and whites benefitted equally from this decrease. We investigated recent trends in the absolute difference in the overall and cause-specific infant mortality rates between non-Hispanic black and whites.

### How to replicate these analyses

If your intention is to replicate our analysis and you are familiar with github, please clone this repository. All of the analysis is contained within the file Code/Examine_Trends.Rmd, and you can run this file within R Studio by running all of the code chunks within this R markdown document. Before you do, you'll need to update all the pathways to the data to your cloned repository! These are found on lines 42, 57, and 160 of the Rmd file. To re-create our research letter, use the "Knit" button to knit to word or html. 

If you are unfamiliar with github, but familiar with R and RStudio, you may wish to download the analysis file by navigating to Code/Examine_Trends.Rmd. You can download the raw version of this file and open locally within RStudio. You will also need to download three data files that are referenced on lines 42, 57, and 160 of the Rmd file. They can be found in the Data folder. Please update the pathways to read these data from your local directory where you've saved these files. You can then run the code chunks within RStudio to replicate the analsyis. To replicate the paper, you can use the "Knit" button to knit to work or html.

Happy Replicating! Reproducible Research FTW!
