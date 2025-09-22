# Task-1:
# Medical Appointment No Shows – Data Cleaning & Preprocessing

This project contains my work cleaning and preprocessing the **Medical Appointment No Shows** dataset from Kaggle.  
The aim was to prepare the raw dataset for analysis by standardising formats and data types.

## Cleaning Summary

- Checked for missing values – none found.
- Checked for duplicate rows – none found.
- Standardised categorical values:
  - Converted `Gender` to lowercase and mapped `f/m` to `female/male`.
  - Converted `No-show` from “Yes/No” to 1/0.
  - Cleaned `Neighbourhood` names to title case.
- Converted `ScheduledDay` and `AppointmentDay` to proper datetime format.
- Renamed columns to lowercase with underscores for consistency.
- Ensured correct data types (e.g. `Age` as integer).

The cleaned dataset is saved .

## Tools Used

- Python 3.x
- Pandas
- Anaconda Distribution (environment management)
- Jupyter Notebook (interactive cleaning and exploration)

## Next Steps

With the cleaned data, you can now:

- Perform exploratory data analysis.
- Build predictive models for appointment no-shows.
- Create dashboards and visualizations.

## License

This project is licensed under the MIT License.  
The dataset is available on Kaggle under its own terms of use.

