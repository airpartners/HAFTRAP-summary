# HAFTRAP-summary
All outlying analysis (primarily summary statistics) for the HAFTRAP study from November 1, 2024.

## Data
The data files - both raw and cleaned - are large and therefore not committed to this repository (see gitignore).

This [Google Drive folder](https://drive.google.com/drive/folders/1PnhpKO4doi4ZTjJZnZ5-LmHT_GkFLuK_?usp=sharing) contains the data folders. Download a copy locally, and place the subfolders `data_raw` and `data_cleaned` in the root directory of your clone of this repository.

## Running
The files in `data_cleaned` are the output of running `data_raw` through the scripts in `cleaning/`. If you would like to re-generate the cleaned data, run the scripts in `cleaning/`, otherwise feel free to start with the cleaned data (`data_summarized` is likewise the output of running `data_cleaned` through the scripts in `summarizing/`).