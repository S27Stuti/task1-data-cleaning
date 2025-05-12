# Task 1: Data Cleaning and Preprocessing

## 📊 Dataset Used
- **Name**: Netflix Movies and TV Shows
- **Source**: [Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)

## 🧹 Cleaning Steps Performed
- Loaded the dataset and checked shape and missing values.
- Removed duplicate rows.
- Filled missing values in 'director', 'cast', 'country', 'rating', and 'date_added' with appropriate defaults.
- Converted 'date_added' to datetime format.
- Standardized column names (lowercase with underscores).
- Standardized text fields (like 'rating' and 'country').
- Converted data types to appropriate formats.
- Saved the cleaned dataset as `cleaned_netflix_titles.csv`.

## 🛠 Tools Used
- Python
- Pandas
- Google Colab (recommended environment)

## 📁 Files Included
- `task1_data_cleaning_netflix.ipynb`: Jupyter notebook with complete code.
- `cleaned_netflix_titles.csv`: Final cleaned dataset.
- `README.md`: This summary file.

## ✅ Output Sample
| title                        | type     | country         | release_year | rating |
|-----------------------------|----------|------------------|---------------|--------|
| Dick Johnson Is Dead        | Movie    | United States    | 2020          | PG     |
| Blood & Water               | TV Show  | South Africa     | 2020          | TV-MA  |

## 📝 Submission
Upload this repository to GitHub and submit the repo link at the internship portal.

