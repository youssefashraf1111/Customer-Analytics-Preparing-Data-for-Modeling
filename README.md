# Customer-Analytics-Preparing-Data-for-Modeling
We have a dataset which its data need to be stored more efficiently, so we can create a model that predicts if course enrollees are looking for a job. I'll convert data types, create ordered categories, and filter ordered categorical data, so the data is ready for modeling.

About the project
A data preprocessing project for a major online data science training provider. The goal is to prepare enrollee data for a machine learning model that predicts whether a course enrollee is actively looking for a job — enabling the company to better target and retain potential candidates.

What I did 
Converted columns to the most efficient data types to reduce memory usage
Created ordered categorical variables from raw text columns
Filtered and validated categorical data to ensure modeling readiness
Reduced dataset size significantly without losing any information

Key results
Metric                                             Value
Columns cleaned                                     14
Memory reduced by                                   ~70%
Final dataset status                        Ready for ML modeling

Project structure
customer-analytics/
├── notebook.ipynb      ← main analysis and preprocessing
├── data/
│   └── customer_train.csv
└── README.md

How to run
1. Download `project1.ipynb`
2. Download `customer_train.csv`
3. Run using Jupyter Notebook or Google Colab

Libraries used
pandas — data manipulation and type conversion

Dataset
Provided by DataCamp. Contains information about data science course enrollees including city, education level, experience, and training hours.

Author
Youssef Ashraf — Aspiring Data Scientist

   
