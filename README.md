# OMOP_CDM_TABLES : GENERATING NEW AND ADAPTED CDM

This project contains several components to create and test a new and adaptable Common Data Model (CDM) based on the OMOP CDM standard.

## Directory Structure

### CDMS
This directory contains common data models that can be used as a basis for creating a new and adaptable CDM.

### ENOMIA_CSV_TABLES
This directory includes all standard tables of the OMOP CDM, made available through the eunomia package for R software.

### MOCK_DATA
This directory holds mock data for testing the insertion and functionality of the newly created tables.

### NEW_CDM
This directory is where the output of the new adapted common data model is stored.

## Scripts

### script_table_creation.R
This script is used to create new tables as per the OMOP CDM standard.

### script_inserting_data.R
This script inserts mock data to test the functionality of the tables.

### script_generating_a_new_cdm.R
This script generates the new adapted CDM using the DatabaseConnector and dplyr libraries.

### script_some_charts.R
This script generates some charts from the mock data to briefly test the quality of the tables.

## Getting Started

### Prerequisites
- R
- DatabaseConnector package
- dplyr package
- eunomia package

### Running the Scripts
1. Use `script_table_creation.R` to create new tables according to the OMOP CDM standard.
2. Use `script_inserting_data.R` to insert mock data and test table functionalities.
3. Use `script_generating_a_new_cdm.R` to create the new adapted CDM.
4. Use `script_some_charts.R` to generate charts and test the quality of the tables.

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
- OMOP CDM
- eunomia package
- DatabaseConnector package
- dplyr package
- oxford-pharmacoepi/PETDiagnostics package


## References 

https://github.com/OHDSI/Eunomia  
https://github.com/oxford-pharmacoepi/PETDiagnostics
