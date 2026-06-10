# 📱 Mobile Phone Usage Analysis

A complete Exploratory Data Analysis (EDA) project that investigates mobile phone usage behavior using Python, Pandas, Matplotlib, and Seaborn.

This project focuses on understanding user habits, screen time patterns, battery consumption, app installation trends, operating system distribution, demographic characteristics, and relationships between multiple variables through statistical analysis and visualizations.

---

# 🎯 Project Objectives

- Load and inspect raw mobile usage data
- Perform data cleaning and validation
- Check for missing values
- Detect duplicate records
- Generate descriptive statistics
- Analyze user behavior patterns
- Visualize distributions of important variables
- Identify relationships between features
- Study demographic trends
- Generate insights from the dataset

---

# 📂 Dataset Information

Dataset Size:

- Rows: **700**
- Columns: **10**

Features Included:

| Feature | Description |
|----------|-------------|
| User ID | Unique identifier |
| Device Model | Smartphone model |
| Operating System | Android / iOS |
| App Usage Time (min/day) | Daily app usage time |
| Screen On Time (hours/day) | Daily screen time |
| Battery Drain (mAh/day) | Daily battery consumption |
| Number of Apps Installed | Total installed apps |
| Data Usage (MB/day) | Daily mobile data usage |
| Age | User age |
| Gender | Male / Female |

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- GitHub

---

# 📊 Data Cleaning Process

The following preprocessing steps were performed:

### Dataset Inspection

```python
df.shape
df.info()
df.head()
```

### Missing Value Analysis

```python
df.isnull().sum()
```

Result:

- No missing values found

### Duplicate Detection

```python
df.duplicated().sum()
```

Result:

- No duplicate records found

### Statistical Summary

```python
df.describe()
```

Generated descriptive statistics including:

- Mean
- Median
- Standard Deviation
- Minimum
- Maximum
- Quartiles

---

# 📈 Exploratory Data Analysis

## Average App Usage Time

```python
df["App Usage Time (min/day)"].mean()
```

Average:

**271.13 minutes/day**

---

## Average Screen On Time

```python
df["Screen On Time (hours/day)"].mean()
```

Average:

**5.27 hours/day**

---

## Average Battery Drain

```python
df["Battery Drain (mAh/day)"].mean()
```

Average:

**1525.16 mAh/day**

---

# 📉 Visualizations Generated

## 1. Operating System Distribution

Purpose:

- Compare Android and iOS users

File:

```text
images/os_distribution.png
```

---

## 2. Operating System Share Pie Chart

Purpose:

- Percentage distribution of operating systems

File:

```text
images/os_share_pie.png
```

---

## 3. Screen Time Distribution Histogram

Purpose:

- Analyze frequency distribution of screen-on time

File:

```text
images/screen_time_distribution.png
```

---

## 4. Screen Time vs Battery Drain Scatter Plot

Purpose:

- Examine relationship between screen time and battery usage

File:

```text
images/battery_vs_screen_time.png
```

---

## 5. Device Model Distribution

Purpose:

- Compare popularity of device models

File:

```text
images/device_model_distribution.png
```

---

## 6. Gender Distribution

Purpose:

- Analyze gender representation

File:

```text
images/gender_distribution.png
```

---

## 7. Age Distribution Box Plot

Purpose:

- Detect age spread and outliers

File:

```text
images/age_boxplot.png
```

---

## 8. Age vs App Usage Scatter Plot

Purpose:

- Study relationship between age and app usage

File:

```text
images/age_vs_app_usage.png
```

---

## 9. Screen Time Violin Plot

Purpose:

- Understand distribution density and spread

File:

```text
images/screen_time_violin.png
```

---

## 10. Correlation Heatmap

Purpose:

- Analyze relationships among numerical variables

File:

```text
images/correlation_heatmap.png
```

---

## 11. Missing Values Heatmap

Purpose:

- Verify absence of missing values

File:

```text
images/missing_values_heatmap.png
```

---

## 12. Pair Plot

Purpose:

- Visualize pairwise relationships among numerical features

File:

```text
images/pairplot.png
```

---

# 🔍 Key Findings

### Operating System

- Android users significantly outnumber iOS users.

### Screen Time

- Average screen-on time exceeds 5 hours per day.

### Battery Usage

- Battery consumption increases with higher screen time.

### App Usage

- Users with higher screen time generally show increased app usage.

### Data Quality

- No missing values detected.
- No duplicate records detected.

### Correlations

- Positive relationship observed between:
  - Screen Time
  - Battery Drain
  - App Usage Time

---

# 📁 Project Structure

```text
mobile-phone-usage-analysis/
│
├── dataset/
│   ├── user_behavior_dataset.csv
│   └── user_behavior_dataset-selected-columns.csv
│
├── images/
│   ├── age_boxplot.png
│   ├── age_vs_app_usage.png
│   ├── battery_vs_screen_time.png
│   ├── correlation_heatmap.png
│   ├── device_model_distribution.png
│   ├── gender_distribution.png
│   ├── missing_values_heatmap.png
│   ├── os_distribution.png
│   ├── os_share_pie.png
│   ├── pairplot.png
│   ├── screen_time_distribution.png
│   └── screen_time_violin.png
│
├── Mobile_Usage_Analysis.ipynb
├── README.md
└── report.md
```

---

# 🚀 How To Run

1. Clone the repository

```bash
git clone https://github.com/namitha-koduru/mobile-phone-usage-analysis.git
```

2. Open the notebook

```text
Mobile_Usage_Analysis.ipynb
```

3. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn
```

4. Run all notebook cells

---

# 📌 Future Enhancements

- Machine Learning Models
- User Segmentation
- Predict Battery Drain
- Predict Screen Time
- Dashboard Development using Streamlit
- Interactive Visual Analytics

---

# 👩‍💻 Author

**Namitha Koduru**

B.Tech Computer Science and Engineering  
VFSTR University

GitHub: https://github.com/namitha-koduru
