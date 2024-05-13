# Uber-data-engineering-with-GCP
## Overview
Implemented a data pipeline using the Mage tool installed on a GCP virtual machine that transfers the raw data from cloud storage, applies necessary transformations to ensure the data is in the correct format, and loads it into BigQuery to extract valuable insights using Looker.
## Dataset Used
TLC Trip Record Data
Yellow and green taxi trip records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts.
## steps
- __Step 1__: Create a data lake on GCP Cloud Storage to be used later as a staging layer. 
- __Step 2__: Load the CSV file containing raw data to Cloud Storage 
- __Step 3__:  Install Mage on an instance on GCP 
- __step 4__: Extract the raw data from the staging area and apply the necessary transformations to convert the data into a dimensional model.
- __step 5__:Create a dataset on BigQuery.
- __step 6__:Load the transformed data into BigQuery.
- __step 7__:Create an analytics layer to be utilized in Looker for extracting valuable insights.

## Technology Used
- Python
- Google Storage
- Compute Instance
- BigQuery
- Looker Studio
