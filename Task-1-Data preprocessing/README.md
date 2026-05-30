TASK-1: DATA PREPROCESSING (TITANIC DATASET)

📌 Project Overview

This project is part of the Elevate Labs AIML Internship Task 1.
The goal is to perform data preprocessing on the Titanic dataset to make it suitable for machine learning models.

⸻

📂 Project Structure

TASK-1-DATA PREPROCESSING
│
├── data              # Titanic dataset files
├── images            # Visualizations (if generated)
├── notebook          # Jupyter notebook with preprocessing steps
├── outputs           # Cleaned dataset output
├── README.md         # Project documentation
└── requirements.txt  # Required libraries

⸻

📊 Dataset Information

The Titanic dataset contains information about passengers such as:

* Passenger class
* Name
* Age
* Sex
* Siblings/Spouses aboard
* Parents/Children aboard
* Fare
* Embarked location
* Survival status

⸻

⚙️ Steps Performed

1. Data Loading

* Loaded Titanic dataset using Pandas
* Checked dataset structure using .head(), .info(), and .describe()

2. Handling Missing Values

* Filled missing values in Age column using median
* Filled missing values in Embarked column using mode
* Removed or handled unnecessary missing data if present

3. Data Cleaning

* Removed duplicates if any
* Handled inconsistent or missing entries

4. Feature Encoding

* Converted categorical variables (Sex, Embarked) into numerical format

5. Final Output

* Saved cleaned dataset as:
    cleaned_titanic.csv inside the outputs folder

⸻

📈 Result

* Dataset is clean and ready for machine learning
* No missing values in final dataset
* Categorical values converted into numerical form

⸻

🎯 Conclusion

The Titanic dataset was successfully cleaned and preprocessed.
This prepares the data for further analysis or machine learning model building.

⸻

📦 Requirements

Install required libraries using:

pip install -r requirements.txt

Libraries used:

* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn

⸻

👤 Author

Name: Jyothika Shreyanjali Gandham
Internship: Elevate Labs AIML Internship
Task: Task 1 – Data Preprocessing (Titanic Dataset)