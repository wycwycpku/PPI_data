# PPI_data
PPI data from **BioGRID** and **STRING-11.0**.
You can get it through [**RSCORE**](https://github.com/wycwycpku/RSCORE) :
```
#For BioGRID, you should choose version; for STRING, you should give the threshold of score (default is 600). Both of them should give the species (default is 9606).
getPPI_Biogrid(version = '3.5.177', species = 9606, save = TRUE)
getPPI_String(species = 10090, score_threshold = 600, save = TRUE)
```