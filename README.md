# BIOSTATS-690E-Capstone

## Data source

Data and documentation files were downloaded on 09/09/2026
from https://causeweb.org/tshs/acupuncture/

The raw data file was downloaded as `acupuncture_data_reduced.RData` 
and is stored in the folder `data/raw`.

The 2 raw data documentation files were downloaded as 
`Acupuncture Data Dictionary_2.pdf` & `Acupuncture Dataset Introduction_2.pdf`
and are stored in the folder `data/original_documentation`.

## The `data` folder

The folder `data` contains 3 subfolders: `original_documentation`, `raw`, 
and `processed`. 

The subfolder `original_documentation` contains the documentation files 
that accompanied the original data download.

The subfolder `raw` contains the original data download, 
exactly as provided by the online source.

The subfolder `processed` contains the following data files:
- `acupunc_full.RData`: the original raw data, but the variable `practice_id` 
  has been renamed `gp`, and the variables `id`, `sex`, `migraine`, 
  `acupuncturist`, `gp`, and `group` have been converted from numeric type into 
  factor type. Contains 14 variables and 401 observations. 
  Created in 01-data_management.qmd
- `acupunc.RData`: the same as `acupunc_full.RData` but filtered to include only
  subjects with migraine (as opposed to tension-type headache). Contains 
  14 variables and 377 observations. Created in 01-data_management.qmd



