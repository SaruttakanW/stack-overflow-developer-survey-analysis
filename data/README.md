# Data Description

This folder contains sample datasets used to demonstrate the data preparation workflow for the Stack Overflow Survey Analysis project.
Due to file size limitations, the full dataset is not included. Instead, sample versions of the datasets are provided.

## Folder Structure
- `raw/`: contains the sample of the original dataset
- `cleaned/`: contains samples of cleaned datasets used for analysis and dashboard

## Files

### raw
- `sample_survey_data.csv`  
  A sample of the original survey dataset before cleaning and transformation.

### cleaned
- `sample_survey_data_updated.csv`  
  A cleaned version of the survey data after handling missing values and selected preprocessing steps.

- `sample_languages.csv`  
  Processed sample dataset derived from the programming language field for language analysis.

- `sample_databases.csv`  
  Processed sample dataset derived from the database field for database analysis.

- `sample_platforms.csv`  
  Processed sample dataset derived from the platform field for platform analysis.

- `sample_webframes.csv`  
  Processed sample dataset derived from the web framework field for web framework analysis.

## Notes
The original survey dataset contains multi-value columns in which multiple technologies are stored in a single cell, separated by semicolons. 
For dashboard analysis, these columns were transformed into separate cleaned datasets so each technology could be analyzed more clearly.
