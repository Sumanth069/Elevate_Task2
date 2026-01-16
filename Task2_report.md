**Task 2: Data Cleaning \& Missing Value Handling**



**Dataset: Medical Appointment No Shows**





**1. Introduction**



Data cleaning is a crucial step in the data preprocessing phase. Real-world datasets often contain missing, inconsistent, or invalid values that can negatively affect analysis and machine learning models. In this task, the Medical Appointment No Shows dataset was cleaned and validated to ensure data quality and reliability.



**2. Dataset Overview**



The dataset contains information related to medical appointments, including patient demographics, appointment scheduling details, and whether the patient showed up for the appointment. Key attributes include age, gender, appointment dates, and attendance status.



**3. Identification of Missing Values**



Missing values were identified using column-wise null value checks. The dataset was examined using built-in Pandas functions to count missing values across all columns.



*Observation*:

No missing values were found in any column. This indicates that the dataset is already complete and well-maintained.



**4. Visualization of Missing Data**



A bar chart was used to visualize missing values across all columns. Since all columns contained zero missing values, the visualization appeared empty. This outcome confirms the absence of missing data and reflects high data quality.



**5. Data Quality Checks**



Even though missing values were not present, additional data quality checks were performed:



Negative age values were checked and removed if found.



Date columns were converted into proper datetime format. 



Duplicate records were identified and removed.



These steps ensured logical consistency and correctness of the dataset.



**6. Handling of Missing Values**



Since no missing values were detected, imputation techniques such as mean, median, or mode filling were not required. However, validation steps were included to demonstrate best data preprocessing practices.



**7. Dataset Validation After Cleaning**



After applying all cleaning and validation steps, the dataset was re-checked for missing values. The final dataset contained no null values and maintained the same number of valid records, confirming successful preprocessing.



**8. Before vs After Comparison**

Aspect				 Before Cleaning		After Cleaning

Missing Values				None				None

Invalid Records				Possible			Removed

Data Consistency			Moderate			High

Model Readiness				No				Yes





**9. Conclusion**



The Medical Appointment No Shows dataset was found to be clean with no missing values. Minor validation steps improved data consistency and ensured readiness for further analysis and machine learning tasks. This dataset is suitable for exploratory data analysis and predictive modeling without extensive preprocessing.

