# student-alcohol-data-cleaning

## Project Description
This project demonstrates a complete data cleaning workflow using the Student Alcohol Consumption dataset. It covers importing and merging datasets, slicing columns, capitalizing text fields, handling inconsistencies, creating new features, and applying transformations to make the data accurate, consistent, and analysis-ready.

## Resources
**File Used:**
  - student-mat.csv → Student performance in Mathematics.
  - student-por.csv → Student performance in Portuguese.

**Source:** [UCI Machine Learning Repository – Student Performance Dataset](https://archive.ics.uci.edu/dataset/320/student+performance)


## About the Data
Each file (student-mat and student-por) contains student information such as school, gender, guardian, study time, alcohol consumption, and other personal/academic details.
The datasets share a number of common attributes, which allows them to be merged into a single dataset.

## Data Information
**Key columns:**
  - school → Student’s school.
  - guardian → Guardian of the student.
  - Mjob and Fjob → Occupations of mother and father.
  - Dalc and Walc → Alcohol consumption (weekday & weekend).

**Cleaning Steps Performed:**
  - Corrected errors in columns
  - Standardized formats
  - Filtered and sliced relevant data
  - Scaled numeric values for demonstration

## Impurities Removed
  - Inconsistent capitalization of job titles (Mjob, Fjob).
  - Missing standardization in categorical fields.
  - Added meaningful derived column (legal_drinker).
  - Normalized numeric values for transformation demonstration.
