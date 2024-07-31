# Data Cleaning

## Row Impact Cleaning Tasks

1. Handle Rows with Too Few Columns - delete or correct if possible
2. Remove Unnecessary Columns - keep only useful columns
3. Remove Duplicate Rows
4. Handle Missing Values - fill in or remove the row
5. Filter Outliers - remove rows with values outside expected range

## Field Impact Cleaning Tasks

1. Correct Data Errors
2. Standardize Data Formats
3. Correct Data Types
4. Encode Categorical Data
5. Handle Inconsistent Data
6. Validate Data Accuracy

-----

## Correct Data Errors

Identify: Look for inaccuracies or inconsistencies in individual fields (e.g., typos in names, incorrect numerical values).

Fix: Correct errors manually or through automated scripts. 
Ensure that corrections are based on reliable sources or rules.

## Standardize Data Formats

Identify: Check for variations in formats (e.g., date formats, phone number formats).

Fix: Convert all values to a consistent format. For example, change dates to YYYY-MM-DD, phone numbers to a standard format, etc.

## Correct Data Types

Identify: Look for fields with incorrect data types (e.g., numbers stored as text, dates stored as text).

Fix: Convert fields to the appropriate data type. 
For example, convert text fields with numbers to integer or float types.

## Encode Categorical Data

Identify: Locate categorical variables (e.g., gender, marital status) that need to be converted into numerical formats.

Fix: Use encoding techniques like one-hot encoding or label encoding. 
For example, convert "Married" and "Single" to 1 and 0, respectively.

## Handle Inconsistent Data

Identify: Find inconsistencies where the same information is represented differently (e.g., "NY" vs "New York").

Fix: Normalize values to a single, consistent representation. 
For example, standardize city names or address formats.

## Validate Data Accuracy

Identify: Check if data aligns with expected values or ranges. For example, validate age ranges or postal codes.

Fix: Cross-check with reliable sources or apply validation rules to ensure data accuracy. 
For example, ensure that ages fall within a reasonable range.

