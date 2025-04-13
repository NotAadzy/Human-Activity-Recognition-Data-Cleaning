# Human Activity Recognition Using Smartphones Dataset

## **Project Overview**
This project demonstrates data cleaning and preparation techniques using the Human Activity Recognition dataset collected from Samsung Galaxy S smartphones. The goal is to produce a tidy dataset suitable for further analysis.

---

## **Files in Repository**
1. `run_analysis.R`: R script for cleaning and processing the data.
2. `CodeBook.md`: Describes variables, transformations, and data structure.
3. `README.md`: Explains project details, file structure, and usage.
4. Final tidy dataset (`tidy_data.txt`).

---

## **Steps Performed**
1. Merged training and test datasets into a single dataset.
2. Extracted mean and standard deviation measurements.
3. Replaced activity labels with descriptive names.
4. Renamed variables to be more descriptive.
5. Created a tidy dataset with averages of each variable grouped by activity and subject.

---

## **How to Run**
1. Clone this repository to your local machine.
2. Download the dataset from [here](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) and extract it into your working directory.
3. Run `run_analysis.R` in RStudio or any R environment:
