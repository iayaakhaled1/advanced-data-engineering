## Learning Objectives:
- Create tasks to extract, transform, and load data
- Handle missing data while transforming
- Load filtered data into a database based on conditions

## Steps:
1. Create a new DAG called census_data_pipeline
2. Define a PythonOperator to download the census CSV data from:https://raw.githubusercontent.com/practical-bootcamp/week4-assignment1-template/main/city_census.csv 
3. Read in the CSV data and handle any missing values.
4. Filter the data and choose a condition to extract specific data. For example:
5. Parse the data into a clean DataFrame and store it in a database
6. Set up the task ordering and dependencies correctly
7. Monitor the pipeline execution in the Airflow UI
8. Perform validation on the number of rows before loading into the database and add some simple statistics about the data as a final step.
