# Healthcare Data Cleaning & Preprocessing using Python

## Project Overview

This project demonstrates end-to-end data cleaning and preprocessing on a healthcare dataset using Python.

## Dataset

- Total Records: 5,100
- Features: 9

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib

## Data Cleaning Tasks

- Identified missing values
- Handled missing Age values using Mean/Median
- Handled missing Treatment Cost using Median
- Removed duplicate records
- Detected invalid Age values
- Detected outliers using the IQR method
- Applied Winsorization (5th & 95th percentile capping)
- Applied Log Transformation
- Performed time-based missing value handling using Forward Fill

## Results

- Missing values handled successfully.
- Removed 99 duplicate records.
- Applied Winsorization using the 5th and 95th percentiles.
- Reduced skewness using log transformation.
- Prepared the dataset for further analysis and machine learning.
 ## Distribution Comparison

### Before Log Transformation

<img width="641" height="664" alt="Histogram before log transformation" src="https://github.com/user-attachments/assets/61ca6933-ec2a-4625-ac26-1ef54dd83da6" />



### After Log Transformation

<img width="761" height="637" alt="histogram after log transformation" src="https://github.com/user-attachments/assets/3145117c-1624-444b-baa9-041e60863519" />



## Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Data Validation- Feature Engineering
- Pandas
- NumPy
- Matplotlib
