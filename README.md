## Air-Quality-EDA

# Air Quality Exploratory Data Analysis (EDA)

## Overview
This project performs an exploratory data analysis (EDA) on air quality data collected from monitoring stations in Portugal.
The main objective is to assess data quality, identify valid monitoring stations and pollutants, and evaluate air quality conditions based on regulatory and environmental criteria.

The project focuses on preparing and validating the data to support environmental analysis and decision-making.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Project Objectives
The main goals of this project are:

- Determine valid monitoring stations and pollutants based on data availability and quality
- Compute and analyze the Air Quality Index (AQI)
- Identify legal threshold violations for regulated air pollutants

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Dataset
The dataset was obtained from the QualAr platform (https://qualar.apambiente.pt) and contains hourly air quality measurements from multiple monitoring stations.

Each station provides yearly Excel files with measurements of the following pollutants:
- Sulfur Dioxide (SO₂)
- Particulate Matter < 10 µm (PM10)
- Ozone (O₃)
- Nitrogen Dioxide (NO₂)
- Carbon Monoxide (CO)
- Benzene
- Particulate Matter < 2.5 µm (PM2.5)

A complementary metadata file includes information about station location, type, and geographical attributes.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Data Processing
The data processing workflow includes:

- Integration of multiple Excel files into a unified dataset
- Standardization and renaming of column names
- Filtering monitoring stations located in the Lisbon Metropolitan Area (LMA)
- Handling missing and inconsistent values
- Replacing negative sensor readings with zero due to sensor imprecision
- Validation of stations and pollutants based on data completeness

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Analysis
The exploratory analysis focuses on:

- Identifying stations and pollutants with sufficient valid data for analysis
- Calculating the Air Quality Index (AQI) to assess overall air quality conditions
- Detecting exceedances of legal air quality thresholds
- Exploring temporal patterns and trends in pollutant concentrations

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Results
The project outputs include:

- A cleaned and validated dataset in CSV format
- Identification of valid monitoring stations and pollutants
- AQI-based air quality assessment
- Detection of legal limit violations

These results provide a reliable foundation for further statistical analysis or predictive modeling.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## How to Run
1. Clone this repository
2. Install the required Python dependencies
3. Run the Jupyter notebooks in sequential order

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Future Improvements
- Automate the data ingestion and validation pipeline
- Extend the analysis to additional regions
- Incorporate real-time air quality data
- Develop predictive models for air quality forecasting


## Project Status
Last updated: January 2026
