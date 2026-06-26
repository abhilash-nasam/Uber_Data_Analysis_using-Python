# Uber_Data_Analysis_using-Python

A data analysis project that explores Uber ride data using Python. This project performs data cleaning, preprocessing, exploratory data analysis (EDA), feature engineering, and data visualization to discover patterns and insights from Uber ride records.

---

## 📌 Project Overview

The objective of this project is to analyze Uber ride data and answer questions such as:

- How are rides distributed across different categories?
- What are the most common trip purposes?
- Which time of day has the highest number of rides?
- How do ride distances vary?
- How are rides distributed across months and weekdays?
- What relationships exist between different features?

This project demonstrates fundamental data analysis techniques using Python libraries.

---

## 📂 Dataset

The dataset contains Uber ride information, including:

- Start Date
- End Date
- Category
- Start Location
- Stop Location
- Miles
- Purpose

**Dataset File**

```
UberDataset.csv
```

---

## 🛠 Technologies Used

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📚 Python Libraries

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.preprocessing import OneHotEncoder
```

---

## 📈 Project Workflow

### 1. Data Loading

- Loaded the Uber dataset using Pandas.
- Displayed dataset information.
- Checked dataset shape and preview.

---

### 2. Data Cleaning

Performed the following preprocessing steps:

- Filled missing values in the **PURPOSE** column.
- Converted date columns into datetime format.
- Removed duplicate records.
- Removed rows containing invalid or missing data.

---

### 3. Feature Engineering

Created new features including:

- Date
- Time (Hour)
- Day/Night Category
- Month
- Weekday

Day/Night was classified into:

- Morning
- Afternoon
- Evening
- Night

---

### 4. Exploratory Data Analysis (EDA)

Generated multiple visualizations such as:

- Ride Category Distribution
- Trip Purpose Distribution
- Day vs Night Ride Distribution
- Purpose by Category
- Correlation Heatmap
- Monthly Ride Analysis
- Weekly Ride Analysis
- Ride Distance Boxplots
- Ride Distance Distribution

---

### 5. Data Encoding

Applied One-Hot Encoding on categorical columns:

- CATEGORY
- PURPOSE

using Scikit-learn's `OneHotEncoder`.

---

## 📊 Visualizations Included

- Count Plots
- Line Plot
- Bar Plot
- Heatmap
- Box Plot
- Distribution Plot

These visualizations help understand ride behavior and identify trends in the dataset.

---

## 📁 Project Structure

```
Uber-Rides-Data-Analysis/
│
├── UberDataset.csv
├── uber_rides_data_analysis_using_python.py

---


### Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Run the project

```bash
python uber_rides_data_analysis_using_python.py
```

---

## 📌 Key Learning Outcomes

This project helped practice:

- Data Cleaning
- Data Preprocessing
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Data Visualization
- One-Hot Encoding
- Correlation Analysis
- Working with Date & Time Data
- Python Data Analysis Workflow

---

## 📄 License

This project is created for educational and learning purposes.

---

## 👨‍💻 Author

**Abhilash and my Team**

B.Tech Computer Science Engineering (Generative AI)
