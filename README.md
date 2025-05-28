# brainhack_brainage_project

Code for creating brainAGE calculator specific templates.

Welcome to the brainhack_brainage_project! This project is focused on estimating and analyzing brain age using neuroimaging data and BrainAge calculators

🚀 **Project Goals**

1. Develop accurate models for predicting brain age from MRI-derived features.
2. Investigate factors contributing to brain age acceleration or deceleration.
3. Promote open science, reproducibility, and collaboration in neuroimaging research.

**Features**

1. Preprocessing pipelines for T1-weighted MRI data.
2. Feature extraction (e.g., cortical thickness, gray matter volume).
3. Brain age prediction models using linear regression
4. Visualization tools for interpreting brain age gaps

**Prerequisites**
> R 
> FreeSurfer Outputs 
> Demograhic Files 
> BrainAge Templates

**Libraries Needed** 
library(readxl)      # To read Excel files (.xlsx)
library(openxlsx)    # To write Excel files
library(stringr)     # For string manipulation
library(dplyr)       # For data wrangling (filter, mutate, group_by, etc.)
library(readr)       # For fast CSV reading/writing

You can install any missing packages using:
install.packages(c("readxl", "openxlsx", "stringr", "dplyr", "readr"))

🚀 How to Run
1. **Clone the repository**:
git clone https://github.com/yourusername/brainhack_brainage_project.git


2. **Open R or RStudio and run the main script:**
source("scripts/brainage_analysis.R")

Results (tables, figures) will be saved in the /results and /figures directories.

3. ADD MORE HERE




