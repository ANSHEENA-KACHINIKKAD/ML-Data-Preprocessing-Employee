# ML Data Preprocessing Project

This project focuses on building a comprehensive data preprocessing pipeline for a machine learning project. It addresses common data quality issues to improve the reliability and performance of machine learning models.

## Dataset

The dataset used for this project " Employee.csv"

## Key Components

### Data Exploration
* Explored the data to understand its structure and characteristics.

* Identified unique values in each feature and their lengths.

* Performed statistical analysis to gain insights into the data distribution.

* Renamed columns for clarity and consistency.

### Data Cleaning

* Identified and handled missing values using appropriate techniques.

* Removed duplicate rows to ensure data integrity.

* Detected and treated outliers using the IQR method.

* Replaced the value 0 in the `Age` column with NaN to represent missing values.

* Treated null values in all columns by either removing rows or replacing them with mean/median/mode.

### Data Analysis

* Filtered the data for specific criteria (age > 40 and salary < 5000).

* Plotted charts to visualize the relationship between age and salary.

* Counted the number of people from each place and represented it visually.

### Data Encoding

* Converted categorical variables into numerical representations using one-hot encoding and label encoding.

### Feature Scaling

* Performed feature scaling using StandardScaler and MinMaxScaler to standardize and normalize numerical features.
