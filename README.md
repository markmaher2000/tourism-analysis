# tourism-analysis
## Data Cleaning Summary
### Before starting the analysis, several data cleaning steps were performed to ensure high-quality and consistent data:

#### 1. Handling Missing Values:
##### Using Mode: For categorical columns like preferred_device and preferred_location_type, missing values were filled with the most frequent value (mode).

##### Using Median: For numerical columns with skewed distributions, missing values were filled using the median to reduce the impact of outliers.

##### Using fillna() for Unknown Devices: Missing or unclear device values were replaced with "Unknown" using fillna() to maintain consistency.

#### 2. Standardizing Values:
##### Merged similar values like "Other" and "Others" under a single consistent category.

##### Removed extra spaces and unified the case (e.g., lowercase formatting) where needed to avoid duplication.

#### 3. Data Type Conversion:
##### Converted boolean and numerical columns to their appropriate data types (e.g., int) for better performance and accurate analysis.
