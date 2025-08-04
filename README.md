
# Cleaned Medical Appointment Dataset 🏥

This project involves cleaning and preprocessing a dataset of medical appointments. The original dataset is downloaded from kaggle . Dtaset contained invalid entries such as negative ages and inconsistent date formats, which have been corrected and standardized.

## ✅ Dataset Cleaning Steps

- Removed rows with invalid ages (age ≤ 0)
- Converted `ScheduledDay` and `AppointmentDay` to `dd-mm-yyyy` format
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
