# 🧹 Task 1: Data Cleaning & Preprocessing for Machine Learning

## 📌 Project Overview
This project focuses on **cleaning and preprocessing raw data** to make it suitable for Machine Learning models. The dataset is cleaned by handling missing values, encoding categorical features, normalizing numerical data, visualizing outliers, and removing extreme values for better accuracy.

## 🔧 Tools Used
- **Python**
- **Pandas** (for data manipulation)
- **NumPy** (for numerical computations)
- **Matplotlib & Seaborn** (for data visualization)

## 🚀 Steps Followed in the Project
1. **Loaded the dataset:** Imported a CSV file using Pandas.
2. **Explored basic details:** Printed dataset info, column types, and checked for missing values.
3. **Handled missing values:**
   - Filled missing numerical values with their mean.
   - Replaced missing categorical values with the most frequent value (mode).
4. **Converted categorical features into numerical format:** Used `.cat.codes` to encode categorical columns.
5. **Standardized numerical features:** Scaled numerical values for better performance.
6. **Visualized outliers using boxplots:** Identified extreme values.
7. **Removed outliers using the IQR method:** Eliminated values that fell outside a specific range.
8. **Saved the cleaned dataset:** Stored the processed data in a new CSV file (`cleaned_dataset.csv`) for further ML tasks.

## 📂 How Anyone Can Do This
Follow these steps to clean and preprocess your own dataset:

### **1️⃣ Install Required Libraries**
Make sure you have the necessary Python libraries installed:
``` IN bash
pip install pandas numpy matplotlib seaborn

2️⃣ Prepare Your Dataset
Ensure your dataset is in CSV format.

Place the CSV file in your project folder.

3️⃣ Create & Run the Python Script

4️⃣ Run the Python Script

bash
python data_cleaning.py

5️⃣ Check the Output
  
