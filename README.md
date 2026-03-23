# 📊 Student Performance Analysis – Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project focuses on performing an in-depth Exploratory Data Analysis (EDA) on a Student Performance dataset using Python. The goal was to understand data structure, distribution patterns, relationships between variables, and prepare the dataset for future Machine Learning applications.

EDA helps in identifying trends, detecting outliers, understanding feature relationships, and validating assumptions before model building.


## 📂 Dataset Information

The dataset includes the following features:

- gender
- Maths_Score
- science score
- english score
- StudyHoursPerDay
- AttendanceRate
- PreferredSubject


## 🛠 Tools & Libraries Used

- Python
- Pandas (Data manipulation)
- NumPy (Numerical operations)
- Matplotlib (Basic visualizations)
- Seaborn (Advanced visualizations)
- Plotly (3D Visualization)
- Scikit-learn (Scaling techniques)



## 🔎 Steps Performed in This Project

### 1️⃣ Data Cleaning
- Loaded dataset using Pandas
- Checked for missing values
- Verified data type
- 
### 2️⃣ Descriptive Statistics

Calculated:
- Mean
- Median
- Mode
- Skewness

This helped in understanding:
- Central tendency
- Distribution symmetry
- Potential skewed features

### 📊 Key Observation:
Most academic score variables show near-symmetric distribution, indicating balanced performance spread.


![imge alt](https://github.com/sakshiparadkar/StudentPerformanceEDA/blob/740b1734a6a65ff1a0e474fee90eb0885e3a90b4/Correlation_Heatmap.png)
![imge alt](https://github.com/sakshiparadkar/Student-PerformancEDA/blob/740b1734a6a65ff1a0e474fee90eb0885e3a90b4/Gender_Distribution.png)
![imge alt](https://github.com/sakshiparadkar/StudentPerformanceEDA/blob/740b1734a6a65ff1a0e474fee90eb0885e3a90b4/Missing_Values_Heatmap.jpg)
### 3️⃣ Distribution Analysis

Used:
- Histograms
- Countplots (Gender Distribution)

Purpose:
- Understand frequency distribution
- Check categorical balance
- Visualize data spread


### 4️⃣ Outlier Detection

Used:
- Boxplots

Purpose:
- Detect extreme values
- Validate data consistency

Result:
No severe outliers affecting the dataset significantly.


### 5️⃣ Correlation Analysis

Generated:
- Correlation Matrix Heatmap

Key Insight:
Strong positive correlation observed among:
- Maths_Score
- Science Score
- English Score

This indicates students performing well in one subject tend to perform well in others.

---

### 6️⃣ Feature Scaling

Applied:
- StandardScaler
- MinMaxScaler

Purpose:
- Normalize feature range
- Prepare dataset for machine learning algorithms



### 7️⃣ 3D Visualization

Created 3D Scatter Plot using Plotly to visualize relationships between:
- Maths Score
- Science Score
- English Score



## 📈 Key Insights

- Academic scores are positively correlated.
- Dataset is well-balanced.
- Minimal skewness observed.
- Study hours and attendance show consistent spread.
- Dataset is suitable for predictive modeling.

## 🚀 Future Scope

- Apply K-Means Clustering
- Perform PCA (Dimensionality Reduction)
- Build Regression Model for Score Prediction
- Implement Classification Algorithms


## 🎯 Conclusion

This project strengthened my understanding of:

- Exploratory Data Analysis
- Statistical Interpretation
- Feature Engineering
- Data Visualization
- Data Preprocessing for ML



