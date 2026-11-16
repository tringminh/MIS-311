# MIS-311
MIS 311 | Introduction to Business Analytics | Data Analysis Projects

# Cost of Living Analysis

![Project](https://img.shields.io/badge/Project-MIS%20311-0D9488?style=flat-square)
![Status](https://img.shields.io/badge/Status-Completed-success?style=flat-square)
![Focus](https://img.shields.io/badge/Focus-Exploratory%20Data%20Analysis-blue?style=flat-square)

## 1. Data Overview

The Cost of Living dataset contains 201 observations and 5 variables, covering 12 countries across the period from 2000 to 2023. The dataset includes both numerical variables, such as Average Monthly Income and Cost of Living, and categorical variables, including Country and Region.

The dataset provides an opportunity to explore differences in income and living costs across countries and geographical regions. Through exploratory data analysis, the study aims to identify patterns in the distribution of income and living expenses and examine how these variables vary across the available observations.


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

Data Cleaning and Preparation

The initial dataset contained 201 observations and 5 variables. During the data quality assessment, two pairs of exact duplicate records were identified and removed, resulting in 197 unique observations.

Additionally, two missing values were identified in the Average_Monthly_Income variable. These values were removed, because it took place 1% of the dataset, so it does not have significant impact. Two missing Region values were also identified and completed based on the corresponding Country information, as both records belonged to Mexico, which is classified under North America.

## 3. Descriptive Statistics

| Statistic | Monthly Income | Cost of Living |
|---|---:|---:|
| Count | 197 | 197 |
| Mean | 4243.97 | 3697.51 |
| Median | 4266.46 | 3649.03 |
| Std. Dev. | 2127.41 | 1990.70 |

### Key Insights
### Insight 1: Data Dispersion

Average income (4,244) exceeds average cost of living (3,698) by about 547 units per month, yet 44.7% of observations have living costs higher than income. Canada (-607) and the United States (-103) are the only countries with a negative average gap, while Germany (+1,211) and France (+1,023) lead. This shows that average living standards can hide financial pressure, and that North American countries face the highest cost burden in this sample.

Supporting statistics: Descriptive statistics. Suggested visualization: Histogram.

### Insight 2: Relationship Between Variables

The Pearson correlation coefficient between average monthly income and cost of living is approximately -0.026 across 197 complete observations, indicating almost no linear relationship within this dataset. This suggests that higher recorded income does not consistently correspond to higher recorded living costs, highlighting the importance of examining additional factors such as country, year, and data measurement definitions before drawing affordability conclusions.

Supporting statistics: Correlation coefficient. Suggested visualization: Scatter Plot with linear trendline.

### Data Visualizations

### Regional Comparison
Clustered bar
![Regional Comparison](regional_comparison.png)

### Income Distribution
Bar chart
![Income Distribution](income_distribution.png)

### Income vs. Cost of Living
Scatter plot
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
