# Employee Dataset Generation

This project generates an artificial employee dataset for a company, simulating various attributes such as gender, job position, salary, performance ratings, and more. The dataset is reproducible, ensuring consistent results when using the same index number (seed value).

## Dataset Attributes:
- **EmployeeID**: Unique ID for each employee (e.g., E1001, E1002, ...)
- **Gender**: Gender of the employee (Male or Female)
- **Age**: Age of the employee (between 25 and 40)
- **JobPosition**: Job position of the employee (Software Engineer, Data Analyst, System Administrator, Project Manager)
- **Salary**: Salary of the employee (random values between 100,000 and 200,000)
- **Department**: Department the employee belongs to (IT, Finance, HR, Marketing)
- **Bonus**: Performance-based bonus (between 5,000 and 20,000)
- **YearsExperience**: Years of experience (between 1 and 15 years)
- **PerformanceRating**: Performance rating on a scale from 1 (Poor) to 5 (Excellent)
- **RemoteWorkEligibility**: Whether the employee is eligible for remote work (Yes/No)

## Tasks Completed:
- Data generation using random values
- Summary statistics calculation for numeric variables
- Various subsets and group operations
- Data visualization (histograms, boxplots, scatter plot)
- Statistical analysis (correlation, regression model, confidence intervals)

## How to Run:
- Install R and required packages (`dplyr` for grouping, `ggplot2` for visualizations)
- Set a seed using your index number for reproducibility
- Run the R script to generate the dataset and perform analysis

## Dataset Output:
The final dataset is saved as `employee_data.csv`.

