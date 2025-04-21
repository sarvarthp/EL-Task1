# EL-Task1

# Files in the Repository
	Task1-Code.ipynb: Main Jupyter notebook containing all data cleaning steps.

	cleaned_marketing_campaign.csv: Final cleaned dataset exported from the notebook.

# Tools & Libraries Used
	Python 
	Pandas for data manipulation
	NumPy for numerical operations
	sklearn.preprocessing.LabelEncoder for encoding categorical variables

# Cleaning Steps Performed
	Import Dataset
		Loaded the raw CSV file using pandas.read_csv().

	Check and Handle Missing Values
		Identified missing values using .isnull() and removed them using .dropna().

	Remove Duplicate Rows
		Used .drop_duplicates() to remove any duplicate entries.
	
	Check and Fix Column Data Types
		Inspected column types using .dtypes and converted where necessary (e.g., date fields).
	
	Standardize Text Values
		Applied .str.title() and .str.strip() to clean text fields like Gender, Education, etc.
	
	Convert Date Columns to Consistent Format
		Used pd.to_datetime() to ensure all date fields are in datetime format.
	
	Label Encoding of Categorical Variables
		Applied LabelEncoder to convert text categories into numeric format for modeling readiness.
	
	Export Cleaned Data
		Saved the cleaned dataset as cleaned_marketing_campaign.csv using .to_csv().


