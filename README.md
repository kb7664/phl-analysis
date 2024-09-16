# Philadelphia Economic Mobility Analysis

This project analyzes economic mobility in Philadelphia compared to national trends, using data from the Opportunity Atlas project by Chetty et al.

## Project Structure

- `data/raw/`: Contains the raw data files from the Opportunity Atlas project.
- `data/codebook/`: Contains the codebook files explaining the data structure.
- `notebooks/`: Jupyter notebooks for analysis.
- `src/`: Source code for the project.
- `tests/`: Unit tests for the project.

## Setup

This project uses Poetry for dependency management and requires Python 3.9.6. To set up the project:

1. Ensure you have Poetry installed and Python 3.9.6 available.
2. Clone this repository.
3. Run `poetry install` in the project root directory.

## Data

The data used in this project comes from the Opportunity Atlas. The raw data files are manually downloaded and placed in the `data/raw/` directory. The codebook files are located in the `data/codebook/` directory.

Raw data files (in `data/raw/`):
- county_by_cohort_estimates.csv
- Table_1_county_trends_estimates.csv
- Table_2_cz_trends_estimates.csv
- Table_4_cz_by_cohort_estimates.csv
- Table_5_national_estimates_by_cohort_primary_outcomes.csv
- Table_6_national_estimates_by_cohort_secondary_outcomes.csv
- Table_7_percentile_dollar_crosswalk.csv
- Table_8_county_covariates.csv
- Table_9_cz_covariates.csv

Each of these files contains different aspects of the economic mobility data, from county-level estimates to national trends. The codebook files in the `data/codebook/` directory provide detailed information about the variables in each of these data files.

## Running the Analysis

To run the analysis:

1. Activate the Poetry environment: `poetry shell`
2. Launch Jupyter Lab: `jupyter lab`
3. Open the `philly_mobility_analysis.ipynb` notebook in the `notebooks/` directory.
