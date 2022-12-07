# morrow-plots-public
R code used to clean and compile Morrow Plots yield and treatment data

The Morrow Plots at the University of Illinois at Urbana-Champaign (UIUC) are the longest-running continuous agricultural fields in the Americas. Established in 1876 by the College of Agriculture and professors Manly Miles and George E. Morrow, the plots were created to facilitate a long-term corn yield experiment with crop rotations and fertilization. 

This repository is a product of the Morrow Plots Data Curation Working Group, established in 2018 to compile, clean and share the data recorded from the experiment over the years. The Working Group has shared these files to be transparent about the methods used to transform the data. This repository does not include all of the files needed to reproduce our results because we do not have permission to publish the original data sources. However, we have published the resulting compiled dataset in the Illinois Data Bank repository where it is freely available for download at https://doi.org/10.13012/B2IDB-7865141_V1.  

This repository contains the R code used to clean and compile the data. R files are written in R Markdown, and each is accompanied by an html output file that can be downloaded and opened in any web browser without installing R. The html files include the R code, text descriptions of the code, previews of the data, and visualizations. Please note that the html files may not preview well in Github.  

v00 contains the code used to create the first compiled dataset shared privately within the University. It was compiled from 3 data sources: two spreadsheets (1888-1954 and 1955-2021), and a field notebok (1876-1913) that is available in the University Archives at https://digital.library.illinois.edu/items/b9a74f70-51c5-0138-7202-02d0d7bfd6e4-9.

v01 contains the code used to create the first published version of the compiled dataset. It combines the v00 dataset with data from the University's soil sample inventory. 

For more information about the process, please see the codebook published alongside the dataset in the Illinois Data Bank at https://doi.org/10.13012/B2IDB-7865141_V1. The Data Bank record also links to several other related resources. 
