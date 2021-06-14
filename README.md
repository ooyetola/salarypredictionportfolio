# Salary Prediction Project
The project predicts salaries for various jobs based on degree, major, industry, years of experience, miles from metropolis.

This is to help companies and job applicants estimate salaries for various jobs.

# Datasets
Datasets contain 1 million records.
train_features.csv is a training dataset and has 8 columns with the JobId as the unique ID.
train_salaries.csv is also a training dataset and has 2 columns - JobId and Salary
test_features.csv is the test dataset. It has 8 columns with the JobId as the unique ID.

Features of train_features.csv and test_features.csv
jobId - unique identifier for job
companyId  - unique identifier for company
jobType  - Job type
degree  - degree required for the job
major  - major required for the job
industry - industry for the job
yearsExperience - required years of experience
milesFromMetropolis - distance of the job location from the metropolis 

Features of train_salaries.csv
jobId - unique identifier for job
salary - job salary
