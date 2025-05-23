# Task-1--Netflix Data Cleaning & Preprocessing
## Project Objective
This project is part of a task focused on data cleaning and preprocessing. The dataset used for this task is the Netflix Movies and TV Shows dataset, which contains details about the content available on Netflix such as title, genre, release year, cast, and more.
The goal was to clean and prepare the raw dataset by addressing missing values, removing duplicates, fixing inconsistent formats, and making it analysis-ready using Python (Pandas).
## Dataset Used 
Name: Netflix Movies and TV Shows

Source:-<a href= "https://github.com/Comhek0369/Task-1--Data-Cleaning-and-Preprocessing/blob/main/netflix_dataset.csv">Kaggle - Source Netflix Dataset</a>

Format: CSV
## Tools Used
Python 3

Jupyter Notebook / VS Code

Pandas
## Cleaning and Preprocessing Steps
Missing Values	Checked using .isnull().sum() and handled with .dropna() or .fillna() depending on context.

DuplicatesRemoved using .drop_duplicates().

Text Standardization	Uniform case formatting for fields like "type", "country", "rating".

Date Conversion	Converted date_added to datetime using pd.to_datetime().

Column Renaming	Renamed columns to be lowercase and snake_case (e.g., date_added instead of Date Added).

Data Type Correction	Converted data types to correct formats, e.g., integers, strings, datetime.

Null Replacement
## Cleaned Dataset Summary & Screenshort
Screenshort : <a href= "https://github.com/Comhek0369/Task-1--Data-Cleaning-and-Preprocessing/blob/main/Screenshot%20(290).png">Screenshort</a>

Cleaned:<a href= "https://github.com/Comhek0369/Task-1--Data-Cleaning-and-Preprocessing/blob/main/Cleaned_Netflix_dataset.csv"> Clean Netflix Dataset</a>
## Repository Structure
├── Cleaned_Netflix_dataset-checkpoint      # Main Jupyter notebook

├── netflix_dataset.csv       # Original dataset

├── Cleaned_Netflix_dataset.csv            # Cleaned dataset

└── /screenshots                # Optional: Screenshots folder

