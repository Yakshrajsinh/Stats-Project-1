# 📊 Household Socio-Economic Data Analysis

This project analyzes a socio-economic household dataset to understand income distribution, demographic patterns, and the relationship between education, family size, and income. The analysis applies descriptive statistics and data visualization techniques to extract meaningful insights from household demographic data.

---

# 📁 Dataset Description

The dataset contains **150+ household records** with demographic, income, and education information.

| Column Name | Data Type | Description |
|-------------|-----------|-------------|
| Household_ID | Categorical | Unique identifier for each household |
| Age_of_Household_Head | Numerical | Age of the household head |
| Household_Income | Numerical | Monthly income of the household |
| Education_Level | Categorical | Primary / Secondary / Graduate / Post-Graduate |
| Family_Size | Numerical | Total number of family members |
| Owns_House | Categorical | Whether the household owns a house (Yes/No) |
| Urban_Rural | Categorical | Household location type |

---

# 🎯 Project Objectives

- Understand different **types of data** (categorical vs numerical)
- Apply **descriptive statistics**
- Analyze **income distribution patterns**
- Measure **central tendency and dispersion**
- Evaluate **skewness and kurtosis**
- Visualize relationships between demographic variables

---

# 🛠 Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# 📊 Statistical Analysis Performed

## 1. Central Tendency

The following measures were calculated for **Household Income** and **Age**:

- Mean
- Median
- Mode

These metrics help identify the typical value and distribution of income across households.

---

## 2. Measures of Dispersion

To understand income variability, the following metrics were calculated:

- Range
- Variance
- Standard Deviation
- Interquartile Range (IQR)

These measures describe how spread out the income values are within the dataset.

---

## 3. Distribution Analysis

The distribution of household income was analyzed using:

- Histogram
- Kernel Density Estimation (KDE)
- Gaussian Distribution Fit

This analysis helps determine whether income follows a **normal distribution or a skewed distribution**.

---

## 4. Skewness and Kurtosis

These statistical metrics help analyze the shape of the income distribution.

- **Skewness** measures asymmetry of the data.
- **Kurtosis** measures the heaviness of the tails.

This helps identify outliers and understand inequality in income distribution.

---

# 📈 Data Visualizations

The following visualizations were created during the analysis:

### Income Distribution
- Histogram
- KDE Plot
- Normal Distribution Curve

### Comparative Analysis
- Boxplot of Income by Education Level
- Boxplot of Family Size by Education Level
- Urban vs Rural Income Comparison

### Relationship Analysis
- Scatter Plot of Age vs Household Income

---

# 🔍 Key Insights

- Income distribution shows **slight positive skewness**, indicating a few high-income households.
- Higher education levels tend to correspond with **higher median household income**.
- Urban households generally demonstrate **higher income variability** compared to rural households.
- Household income tends to increase with age until middle adulthood.

---

# 📂 Project Structure

```
Household-Data-Analysis
│
├── household_data.xlsx
├── analysis.ipynb
├── visuals
│   ├── income_histogram.png
│   ├── education_income_boxplot.png
│   ├── family_size_boxplot.png
│   └── age_income_scatter.png
│
└── README.md
```

---

# 🚀 How to Run the Project

1. Clone the repository

```
git clone https://github.com/yourusername/Household-Data-Analysis.git
```

2. Install required libraries

```
pip install pandas numpy matplotlib seaborn scipy
```

3. Open Jupyter Notebook

```
jupyter notebook
```

4. Run the analysis notebook.

---

# 📚 Concepts Covered

- Types of Data
- Descriptive Statistics
- Central Tendency
- Measures of Dispersion
- Gaussian Distribution
- Percentiles and Quartiles
- Skewness and Kurtosis
- Data Visualization

---

# 💼 Resume Value

This project demonstrates practical experience in:

- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Data Visualization
- Socio-economic data interpretation
- Python-based analytics workflows

---

# 👨‍💻 Author

**Yakshraj Gohil**

Aspiring Data Analyst | MERN Stack Developer
