# ADVANCE SCAR assignment

This repository was developed as part of the interview process for the Scientific Collaborator position at the Royal Belgian Institute of Natural Sciences.  
  
The assignment involves the following tasks:  
1. Develop a workflow performing quality control checks on the [Antartic Phipoda](https://ipt.biodiversity.aq/resource?r=2438_mista_ant_phipoda) collection available in GBIF  
2. Prepare a report summarising data processing workflow and any important insights obtained during quality control  
3. Create at least two plots using the QC data, one of which must be a map  
  
Points 1 and 2 are addressed by the `01_data_qc_workflow.Rmd` notebook, while the plots are included in `02_data_plots.Rmd`. For convenience, `.Rmd` files are provided so they can be easily run locally for testing, while the `.md` files are a markdown friendly version that has been included to avoid having to run the notebooks before seeing the final product.  
    
## Requirements
  
This repository needs the following packages installed locally for it to run successfully:  
- `usethis`  
- `tidyverse`  
- `janitor`  
- `rgbif`  
- `CoordinateCleaner`  
- `rnaturalearth`  
- `ggspatial`  
- `ggOceanMaps`  
- `treemap`  
  
You can use the `Installing_R_libraries.R` included under the `Scripts` folder to check if any of these dependencies are not installed locally. If any libraries are missing, the code will automatically install them. To run the script copy the following lines into your RStudio console:  
  
```{r}
source("Scripts/installing_R_libraries.R")  
checking_libraries()
```
  
The details for the `R` session used to develop scripts in this repository are included below:  
```
R version 4.3.1 (2023-06-16 ucrt)
Platform: x86_64-w64-mingw32/x64 (64-bit)
Running under: Windows 10 x64 (build 19045)

Matrix products: default


locale:
[1] LC_COLLATE=English_Australia.utf8  LC_CTYPE=English_Australia.utf8    LC_MONETARY=English_Australia.utf8
[4] LC_NUMERIC=C                       LC_TIME=English_Australia.utf8    

time zone: Australia/Hobart
tzcode source: internal
```
  
## Additional information included in this repository
Although it was not part of the assignment brief, a couple of additional files have been added to this repository as it was encouraged for technical skills to be shown here.  
  
An Apache License version 2.0 has been added as I assume this information is needed to track the usage of workflows/tools developed during this project. A citation file has also been added, which will make it easy for users to cite this repository.  
  
These files are meant for demonstration purposes only.  


