# Salary-Prediction
Salary Prediction Project(Python)

As a data scientist to examine a set of job postings with salaries and then predict salaries for a new set of job postings

Data supplied:
You are given three CSV data files:
• train_features.csv: Each row represents metadata for an individual job posting.
The “jobId” column represents a unique identifier for the job posting. The remaining columns describe features of the job posting.
• train_salaries.csv: Each row associates a “jobId” with a “salary”.
• test_features.csv: Similar to train_features.csv, each row represents metadata for an individual job posting.
The first row of each file contains headers for the columns. Keep in mind that the metadata and salary data may contain errors.

The task:
You must build a model to predict the salaries for the job postings contained in test_features.csv. The output of your system should be a CSV file entitled test_salaries.csv where each row has the following format:
jobId, salary
As a reference, your output should mirror the format of train_salaries.csv. 
