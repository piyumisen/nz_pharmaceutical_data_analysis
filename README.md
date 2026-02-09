# NZ Pharmaceutical Data Analysis

This notebook conducts a data-driven analysis of pharmaceutical dispensing trends, specifically focusing on regional variances and national chemical usage.

## Data Download:

To run this analysis, you will need to download the following two datasets:

1.  **Pharmaceutical Dispensing Data:**
    * Visit the [Te Whatu Ora Pharmaceutical Data Web Tool](https://tewhatuora.shinyapps.io/pharmaceutical-data-web-tool/).
    * Download the full dataset and choose the file: `Data_ByChemical.csv`.

2.  **Population Data:**
    * Visit [Stats NZ Infoshare](https://infoshare.stats.govt.nz/SelectVariables.aspx?pxID=d1d5e10c-1a9d-4954-9e32-c374aa231d90).
    * **Selection:** Ensure you select the population variables for the years **2020 to 2025**.
    * Export the data as a CSV file for use in the notebook.


## Key Steps and Analyses:

- Data Preparation: It cleans raw dispensing data by normalizing column names, imputing redacted low-volume values (values marked '<6'), and mapping specific health districts to broader geographic regions (e.g., Auckland, Canterbury). It also integrates population data to enable per-capita calculations.

- Regional Analysis: It calculates and visualizes dispensings per capita across different regions over time to compare access or usage rates geographically.

- Top Chemical Trends: It identifies the top 10 most dispensed chemicals by total volume (such as Paracetamol and Atorvastatin) and plots their national per-capita usage trends.

- Chronic Medication Analysis: It performs a specific analysis on a targeted list of chronic medications (e.g., Atorvastatin, Metformin) to distinguish between "Initial" dispensings (new patients) and "Maintenance" dispensings (ongoing treatment).
