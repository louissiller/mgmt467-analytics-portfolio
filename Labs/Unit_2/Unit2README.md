# Netflix Data Quality Project

This repository contains the code and documentation for a data quality analysis project on a Netflix user behavior dataset. The project involves downloading data from Kaggle, staging it in Google Cloud Storage, loading it into BigQuery, and performing data quality checks for missingness, duplicates, and outliers.

## Project Details

- **Google Cloud Project ID:** `mgmt467-71800`
- **Region:** `us-central1`
- **Google Cloud Storage Bucket:** `gs://{{mgmt467-netflix-87febac5}}`
- **BigQuery Dataset:** sayeeduddin/netflix-2025user-behavior-dataset-210k-records

## Data Summary

Below are the row counts for the tables loaded into BigQuery:

| table_name          | row_count |
|---------------------|-----------|
| reviews             | 216300    |
| users               | 144200    |
| movies              | 14560     |
| watch_history       | 1470000   |
| search_logs         | 371000    |
| recommendation_logs | 728000    |

## Data Quality Analysis Summary

Here is a summary of the anomaly flags identified:

| flag_name             | pct_of_rows |
|-----------------------|-------------|
| flag_binge            | 0.00        |
| flag_age_extreme      | 1.74        |
| flag_duration_anomaly | 2.21        |

---
