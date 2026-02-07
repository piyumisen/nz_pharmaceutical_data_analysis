# NZ Pharmaceutical Data Analysis

This notebook conducts a data-driven analysis of pharmaceutical dispensing trends, specifically focusing on regional variances and national chemical usage.

## Key Steps and Analyses:

- Data Preparation: It cleans raw dispensing data by normalizing column names, imputing redacted low-volume values (values marked '<6'), and mapping specific health districts to broader geographic regions (e.g., Auckland, Canterbury). It also integrates population data to enable per-capita calculations.

- Regional Analysis: It calculates and visualizes dispensings per capita across different regions over time to compare access or usage rates geographically.

- Top Chemical Trends: It identifies the top 10 most dispensed chemicals by total volume (such as Paracetamol and Atorvastatin) and plots their national per-capita usage trends.

- Chronic Medication Analysis: It performs a specific analysis on a targeted list of chronic medications (e.g., Atorvastatin, Metformin) to distinguish between "Initial" dispensings (new patients) and "Maintenance" dispensings (ongoing treatment).
