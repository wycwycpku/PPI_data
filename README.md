# PPI_data
PPI data from **BioGRID** and **STRING-11.0**.
You can get it through [**RSCORE**](https://github.com/wycwycpku/RSCORE) :
```
#For BioGRID, you should choose version, both of them should give the species.
getPPI_Biogrid(version = '3.5.177', species = 9606, save = TRUE)
getPPI_String(species = 10090, save = TRUE)
```