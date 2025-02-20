# Iran HEIS and LFS (1392-1401)

## Overview
This repository contains an **RMarkdown script** to clean and standardize **10 years** of **Iranian Labor Force Survey (LFS)** and **Household Expenditure & Income Survey (HEIS)** data from **1392 to 1401 (2013-2022)**. The cleaning process ensures **variable consistency**, removes **missing values**, and makes the datasets ready for further analysis.

## Features
- **Standardizes LFS & HEIS variables** across 10 years.
- **Cleans missing values & inconsistencies** to improve data quality.
- **Ensures cross-year comparability** for analysis.
- **Outputs ready-to-use datasets** for research and modeling.

## Data Source & Availability
- The original datasets can be downloaded from:  
  🔗 **[amar.org.ir](https://amar.org.ir)**  
- This repository contains **only the cleaning script**; the datasets are not included due to size and privacy concerns.

## File Structure
```
├── clean_LFS_HEIS_1392_1401.Rmd  # RMarkdown script for data cleaning 
├── README.md                      # Project documentation 
├── .gitignore                     # Files to ignore (e.g., raw datasets)
```

## Requirements
To run this project, install the necessary R packages:

### Installation
Inside R, install the required dependencies:
```r
install.packages(c("dplyr", "data.table", "tidyr", "tidyverse", "stringr", 
                   "readxl", "haven", "foreign", "writexl", "ggplot2", 
                   "leaflet", "kableExtra", "psych", "Hmisc", "labelled", 
                   "sf", "tigris"))
```

## Usage

### Running the Cleaning Script
1. Clone the repository:
   ```sh
   git clone https://github.com/Ali-Iranpour/Iran_LFS_HEIS_Cleaning.git
   cd Iran_LFS_HEIS_Cleaning
   ```
2. Open RStudio and load `clean_LFS_HEIS.Rmd`.
3. Run the script:
   - Execute individual chunks inside RStudio.
   - Click **"Knit"** to generate a report with cleaned output.
