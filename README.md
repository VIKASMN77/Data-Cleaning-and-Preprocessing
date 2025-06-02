# Data-Cleaning-and-Preprocessing
# 🧹 Sales Data Cleaning (Google Colab)

This project focuses on cleaning a synthetic sales dataset using Python and pandas in Google Colab. The dataset was sourced from Kaggle and includes sales transaction records.

## 📁 Dataset

- **Source:** [Sales Dataset on Kaggle](https://www.kaggle.com/datasets/mdsadikujjamanshihab/sales-dataset)
- **File Used:** `synthetic_sales_data.csv`

## 🔧 Cleaning Steps Performed

1. **Loaded CSV file** using pandas.
2. **Checked for missing values** using `.isnull().sum()`.
3. **Removed duplicate rows** using `.drop_duplicates()`.
4. **Standardized column names** (lowercase, replaced spaces).
5. **Converted date and time** fields to `datetime` type.
6. **Fixed data types** (e.g., `customerage` as integer).
7. **Standardized text entries** like `customergender`, `region`, `category`.

##  Tools Used

- Google Colab
- Python 3
- pandas

##  Author

- **Vikas M N**
- [GitHub Profile](https://github.com/VIKASMN77)

## License

This project is for educational purposes and uses publicly available data.
