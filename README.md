# pandas-challenge

#### This code project consists of Python code that analyzes school district data. It reads data from two CSV files: "schools_complete.csv" and "students_complete.csv". The code performs various calculations and creates summary tables based on the data.

## District Summary
### The code starts by merging the two datasets into a single dataframe called "df". It then calculates several summary statistics for the entire district, including:

#### Total number of schools
#### Total number of students
#### Total district budget
#### Budget per student
#### Average math score
#### Average reading score
#### Percentage of students passing math
#### Percentage of students passing reading
#### Percentage of students passing both math and reading
#### The results are displayed in a dataframe called "district_summary".

## School Summary
### The code further analyzes the data by grouping it by school name and calculating various statistics for each school. The following information is provided for each school:

#### School type
#### Total number of students
#### Budget
#### Average reading score
#### Average math score
#### Budget per student
#### Percentage of students passing math
#### Percentage of students passing reading
#### Percentage of students passing both math and reading
#### The results are displayed in a dataframe called "school_data".

## Please note that the code assumes that the CSV files are located in the "../Instructions/PyCitySchools/Resources/" directory relative to the location of the code file. Make sure the files are in the correct location or modify the file paths accordingly.
