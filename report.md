# Mobile Phone Usage Analysis Report

## 1. Introduction

Mobile phones have become an essential part of daily life. Understanding user behavior, screen time patterns, battery consumption, and application usage can provide valuable insights into device utilization and user engagement.

This project focuses on analyzing mobile phone usage data through data cleaning, exploratory data analysis (EDA), and visualization techniques using Python.

---

## 2. Objective

The objectives of this project are:

- Analyze mobile phone usage behavior.
- Identify screen time patterns.
- Study battery consumption trends.
- Examine operating system distribution.
- Investigate relationships among usage-related variables.
- Visualize key insights through charts and graphs.

---

## 3. Dataset Description

The dataset contains information for 700 mobile phone users.

### Features

| Feature | Description |
|----------|-------------|
| User ID | Unique identifier |
| Device Model | Smartphone model |
| Operating System | Android or iOS |
| App Usage Time (min/day) | Daily app usage time |
| Screen On Time (hours/day) | Daily screen activity |
| Battery Drain (mAh/day) | Daily battery consumption |
| Number of Apps Installed | Total installed applications |
| Data Usage (MB/day) | Daily mobile data usage |
| Age | User age |
| Gender | User gender |

---

## 4. Tools and Technologies

- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab
- GitHub

---

## 5. Data Cleaning and Preparation

The following preprocessing steps were performed:

1. Loaded dataset into Pandas DataFrame.
2. Examined dataset dimensions.
3. Verified column data types.
4. Checked missing values.
5. Identified duplicate records.
6. Removed duplicates if present.
7. Generated descriptive statistics.

### Results

- Total Records: 700
- Total Features: 10
- Missing Values: 0
- Duplicate Records: 0

---

## 6. Exploratory Data Analysis

### Operating System Distribution

A bar chart and pie chart were used to analyze the distribution of Android and iOS users.

**Observation:** Android users represent a larger proportion of the dataset.

### Screen Time Distribution

A histogram was used to study the distribution of screen-on time.

**Observation:** Most users fall within moderate daily screen-time ranges.

### Gender Distribution

A pie chart was used to visualize user gender distribution.

**Observation:** The dataset contains both male and female users with varying proportions.

### Screen Time vs Battery Drain

A scatter plot was used to analyze the relationship between screen usage and battery consumption.

**Observation:** Higher screen time generally corresponds to increased battery drain.

### Age vs App Usage

A scatter plot was used to study how application usage varies across age groups.

**Observation:** App usage patterns differ across age categories.

### Device Model Analysis

A bar chart was used to compare device model frequencies.

**Observation:** Certain smartphone models appear more frequently in the dataset.

### Correlation Analysis

A correlation heatmap was generated to identify relationships among numerical features.

**Observation:** Strong positive relationships exist between screen time, app usage, battery drain, and data usage.

---

## 7. Key Findings

- Android devices dominate the dataset.
- Increased screen time contributes to higher battery consumption.
- App usage is positively associated with screen-on duration.
- Users with more installed applications tend to spend more time using their devices.
- Battery drain and screen time show a clear positive relationship.
- The dataset is clean with no missing values or duplicate records.

---

## 8. Conclusion

This project successfully analyzed mobile phone usage behavior using data wrangling and exploratory data analysis techniques.

The study revealed meaningful relationships among screen time, battery usage, application activity, and device characteristics. Visualizations helped uncover trends and patterns that improve understanding of smartphone usage behavior.

The project demonstrates practical applications of Python, Pandas, Matplotlib, and Seaborn in real-world data analysis tasks.

---

## 9. Future Scope

- Predictive modeling of battery consumption.
- User segmentation and clustering.
- Interactive dashboards using Streamlit.
- Advanced statistical analysis.
- Real-time mobile usage monitoring systems.
