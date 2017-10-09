# Codebook
Patricia Goresen  
10/9/2017  

# Codebook for Assignment 5
## Introduction
##### This assignment's objective was to sort, summarize, and clean up raw data to find the most popular girls names in 2015 and 2016

## Collection of raw data
##### Data was given to us by the instructor. It was given as two text files: yob2016.txt and yob2015.txt

## Description of files
* File yob2016.txt contains popular names for children born in the year 2016
* File yob2015.txt  contains popular names for children born in the year 2015

## Variable Descriptions for Raw Data
##### Both data sets contained the same variables and are as follows:
* "Name" Name of the popular name (Factor)
* "Gender" The gender associated with the name (Factor)
* "Frequency" Number of children with associated name in that year (int)

## Creating the final datafile
1. Import both yob2016.txt and yob2015.txt
2. Remove misspelled name from yob2016.txt
3. Combined yob2016.txt and yob2015.txt by variable name and removed NA values
4. Created a new column "total" that counted how many people were given the name in 2015 and 2016
5. Sorted the data by total
6. Omitted all boy names









