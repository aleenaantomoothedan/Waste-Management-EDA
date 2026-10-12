# ♻️ Waste Management in India — Exploratory Data Analysis (EDA)

## 📌 Project Overview

Waste management is an important environmental challenge in India. Population growth, urbanization, and increasing waste generation create a need for efficient waste collection, recycling, and disposal practices.

This project focuses on performing **Exploratory Data Analysis (EDA) on waste management in India from 2015 to 2026**. Using Python, I explored waste generation patterns, waste treatment methods, collection efficiency, recycling, composting, landfill dependency, municipal efficiency, and sustainability indicators across different states, regions, and city categories.

The objective is to understand patterns and relationships in the dataset, identify differences in waste management performance, and derive insights that can support better waste management planning.

## 🎯 Project Objectives

* Analyze waste generation patterns across different waste types, states, regions, and city categories.
* Examine waste collection efficiency, recycling rates, composting rates, and landfill dependency.
* Investigate the relationship between population and daily waste generation.
* Explore the relationship between waste segregation and recycling rates.
* Compare waste management performance across regions and city categories.
* Analyze the distribution of waste treatment methods.
* Identify numerical factors associated with the Sustainability Index.
* Examine changes in waste generation and sustainability indicators over time.
* Identify potential improvements in waste management practices.

## 🛠️ Tools and Technologies

* **Python** — Data analysis and programming.
* **Pandas** — Data manipulation, grouping, and statistical analysis.
* **NumPy** — Numerical operations.
* **Matplotlib** — Data visualization.
* **Seaborn** — Statistical plots and visual analysis.
* **Jupyter Notebook** — Performing and documenting the analysis.

## 🔍 What I Did in This Project

### 1. Data Exploration and Understanding

* Inspected the dataset structure, dimensions, columns, and data types.
* Examined the first and last records.
* Used descriptive statistics to understand numerical variables.
* Analyzed the distribution of categorical variables, including waste types and treatment methods.

### 2. Data Quality Checks

* Checked for missing values and duplicate records.
* Examined unique values in the dataset.
* Validated percentage-based columns to identify values outside the 0–100 range.
* Checked year and month values against their expected ranges.
* Investigated negative and zero values in numerical columns.

### 3. Waste Generation Analysis

* Compared average daily waste generation across waste types.
* Examined waste generation per capita.
* Compared waste generation across Metro, Tier-1, Tier-2, and Tier-3 cities.
* Analyzed variations in waste generation across seasons.
* Investigated changes in average daily waste generation from 2015 to 2026.

### 4. Regional and State-Level Analysis

* Compared waste collection efficiency across regions.
* Analyzed average recycling rates across regions.
* Compared Sustainability Index values across states.
* Examined differences in municipal efficiency across city categories.

### 5. Waste Treatment Analysis

* Examined the distribution of waste treatment methods.
* Compared treatment methods across different waste types.
* Analyzed Sustainability Index values across treatment methods.

### 6. Correlation Analysis

* Investigated relationships between population and daily waste generation.
* Examined the relationship between waste segregation and recycling.
* Used a correlation matrix and heatmap to explore relationships between waste management indicators.
* Identified numerical variables with strong positive and negative correlations with the Sustainability Index.

### 7. Data Visualization

Created visualizations using Matplotlib and Seaborn, including:

* Bar plots for regional and categorical comparisons.
* Count plots for waste type distribution.
* Histograms for numerical variable distributions.
* Boxplots for examining variability and potential outliers.
* Scatter plots for investigating relationships between variables.
* Correlation heatmaps.
* Time-series line plots for waste generation and sustainability trends.

### 8. Outlier Detection

* Used boxplots to examine daily waste generation.
* Applied the Interquartile Range (IQR) method to identify potential outliers.
* Calculated the number and percentage of identified outliers.

### 9. Feature Engineering

Created additional features to support further analysis:

* Date from the Year and Month columns.
* Combined recycling and composting rate.
* Collection gap.
* Non-landfill rate.
* Waste generated per collection vehicle.
* Numerical codes for waste type, city category, treatment method, and region.

### 10. Time-Series Analysis

* Analyzed average daily waste generation over time.
* Compared yearly average waste generation from 2015 to 2026.
* Examined changes in the average Sustainability Index over the same period.

## 📊 Key Findings

The following insights were identified in the dataset:

* **Waste generation:** Organic waste had the highest average daily waste generation, at approximately 407.45 tons, while biomedical waste had the lowest, at approximately 8.10 tons.
* **Regional collection efficiency:** The West region recorded the highest average collection efficiency, at approximately 63.46%, while the Northeast recorded the lowest, at approximately 53.71%.
* **City categories:** Metro cities had the highest average daily waste generation, at approximately 1,552.87 tons.
* **Waste treatment:** Landfill was a commonly recorded treatment method for several waste types, while recycling was the most frequently recorded method for glass, metal, and paper.
* **Sustainability indicators:** The Municipal Efficiency Score and Waste Segregation Rate had strong positive correlations with the Sustainability Index, at approximately 0.741 and 0.735, respectively.
* **Landfill dependency:** Landfill Dependency Rate had a strong negative correlation with the Sustainability Index, at approximately -0.852.
* **Waste generation trend:** Average daily waste generation showed an overall upward trend between 2015 and 2026, despite some yearly fluctuations.
* **Sustainability trend:** The average Sustainability Index increased from approximately 40.43 in 2015 to 47.71 in 2026.

*These findings describe relationships and patterns in the dataset. Correlation does not establish causation, and the results should be interpreted in the context of the dataset.*

## 💡 Recommendations

Based on the analysis, the following improvements may help support more effective waste management:

* Encourage waste segregation at the source to support recycling.
* Improve collection infrastructure in regions with lower collection efficiency.
* Prioritize appropriate treatment methods for high-volume waste categories.
* Plan waste collection capacity according to population and expected waste generation.
* Promote recycling, composting, and suitable alternatives to landfill disposal.
* Monitor collection efficiency, recycling rates, and sustainability indicators regularly.
* Use data-driven analysis to identify areas where waste management resources may be needed.

## ✅ Conclusion

This project demonstrates how Exploratory Data Analysis can be used to investigate waste generation, collection efficiency, waste treatment practices, and sustainability indicators.

Through data quality checks, statistical analysis, visualization, correlation analysis, outlier detection, feature engineering, and time-series analysis, I identified important patterns and differences in waste management across regions, states, and city categories.

The findings highlight the importance of waste segregation, efficient collection systems, appropriate waste treatment, and reduced dependence on landfills. This project strengthened my practical understanding of Python-based data analysis and how data-driven insights can contribute to understanding environmental challenges.

## 👩‍💻 Author

**Aleena Anto**

**Project Type:** Exploratory Data Analysis (EDA)

