# MIS-311
MIS 311 | Introduction to Business Analytics | Data Analysis Projects

# Cost of Living Analysis

![Project](https://img.shields.io/badge/Project-MIS%20311-0D9488?style=flat-square)
![Status](https://img.shields.io/badge/Status-Completed-success?style=flat-square)
![Focus](https://img.shields.io/badge/Focus-Exploratory%20Data%20Analysis-blue?style=flat-square)

## 1. Data Overview

This project conducts Exploratory Data Analysis (EDA)
on a Cost of Living dataset covering 12 countries
from 2000 to 2023.

The analysis examines income and living-cost patterns
and explores their variation across observations
and geographical regions.


| Variable | Description |
|---|---|
| Country | Country name |
| Year | Observation year |
| Average_Monthly_Income | Average monthly income |
| Cost_of_Living | Living cost |
| Region | Geographical region |

Initial observations: 201

Cleaned observations: 197

Countries: 12

Period: 2000–2023

## 2. Data Cleaning

The cleaning process included:

- Removal of 2 excess exact duplicate records.
- Removal of 2 missing income values.
- Completion of 2 missing region values.
- Validation of the cleaned dataset.


## 3. Descriptive Statistics

| Statistic | Monthly Income | Cost of Living |
|---|---:|---:|
| Count | 197 | 197 |
| Mean | 4243.97 | 3697.51 |
| Median | 4266.46 | 3649.03 |
| Std. Dev. | 2127.41 | 1990.70 |

    Key Insights
### Insight 1: Data Dispersion

The dataset demonstrates substantial variation in both income and living costs across the 197 observations. Average monthly income ranges from 534.74 to 7,976.56, while cost of living ranges from 464.49 to 6,981.02, indicating that overall averages alone may conceal considerable differences between country-year observations. Therefore, more segmented analysis is necessary to understand the distribution of these economic indicators.

Supporting statistics: Mean, Standard Deviation, Minimum and Maximum. Suggested visualization: Histogram.

### Insight 2: Relationship Between Variables

The Pearson correlation coefficient between average monthly income and cost of living is approximately -0.026 across 197 complete observations, indicating almost no linear relationship within this dataset. This suggests that higher recorded income does not consistently correspond to higher recorded living costs, highlighting the importance of examining additional factors such as country, year, and data measurement definitions before drawing affordability conclusions.

Supporting statistics: Correlation coefficient. Suggested visualization: Scatter Plot with linear trendline.

    Data Visualizations

### Regional Comparison

![Regional Comparison](regional_comparison.png)

### Income Distribution

![Income Distribution](income_distribution.png)

### Income vs. Cost of Living

![Correlation Plot](correlation_plot.png)

## 4. Tools Used

- Microsoft Excel
- Exploratory Data Analysis
- Data Visualization

## 5. Limitations

The provided dataset does not specify
the currency unit or the original source metadata.
Therefore, conclusions are limited to
the numerical patterns within the dataset.

---

**MIS 311 | Introduction to Business Analytics**
