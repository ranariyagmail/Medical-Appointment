
#  Medical Appointment Dataset 🏥

This project involves cleaning and preprocessing a dataset of medical appointments. The original dataset is downloaded from kaggle . Dtaset contained invalid entries such as negative ages and inconsistent date formats, which have been corrected and standardized.

## ✅ Dataset Cleaning Steps
- Identify and handle missing values using .isnull() in Python or filters in Excel.
-Remove duplicate rows using .drop_duplicates() or Excel’s “Remove Duplicates”.
-Standardize text values like gender, country names, etc.
-Convert date formats to a consistent type (e.g., dd-mm-yyyy).
-Rename column headers to be clean and uniform (e.g., lowercase, no spaces).
-Check and fix data types (e.g., age should be int, date as datetime)
- Renamed all column names to lowercase and replaced spaces with hyphens for consistency
- Saved the cleaned data in CSV format

## 📁 Files

- `cleaned_data.csv` — the cleaned dataset
- `code file.py` — Python script used for data cleaning
- `README.md`
- KaggleV2-May-2016.csv - Dataset

## 🔧 Technologies Used

- Python 3.x
- Pandas
- Jupyter Notebook (optional)

## 🚀 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/medical-appointments-cleaning.git
   ```
2. Run the script or open it in Jupyter to see the cleaning process.
3. Use `cleaned_data.csv` for your analysis or modeling tasks.

## 📌 License

This project is open-source and available 
