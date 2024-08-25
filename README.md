
# Project Overview

This project involves a descriptive analysis of a dataset, focusing on various aspects such as age distribution, total amount spent on products, education years on degree programs, and campaign acceptance. The analysis aims to provide insights into the data by examining key statistical measures such as mean, range, standard deviation, and median.

## Key Analyses

### Age Analysis
- **Average Age:** 55.19 years
- **Age Range:** 38 to 131 years
- **Standard Deviation:** 11.98 years
- **Median Age:** 55 years

### Total Amount Spent on Mnt Products
- **Average Amount Spent:** $568.27
- **Range:** $5 to $2431
- **Standard Deviation:** $568.67
- **Median Amount Spent:** $568.27

### Education Years on Degree Programs
- **Average Education Years:** 16.88 years
- **Range:** 9 to 21 years
- **Standard Deviation:** 2.82 years
- **Median Education Years:** 16 years

### Campaigns Accepted
- Analysis of total campaigns accepted by the participants, examining the distribution and key statistics.

## Data Cleaning and Preprocessing

The project includes several important data cleaning and preprocessing steps:
1. **Column Renaming:** All column names were cleaned by removing spaces to ensure consistency.
2. **Income Data Cleaning:** The `Income` column was cleaned by removing dollar signs and commas, then converting it to a float for analysis. Missing values were imputed with the mean income.
3. **General Data Cleaning:** Further steps included handling missing values in other columns to prepare the data for analysis.

## Data Visualization

Visualizations played a key role in understanding the data:
1. **Histograms:** Plotted for key variables such as `Age`, `TotalAmount_Spent`, and `TotalCampaignAcc` to visualize frequency distributions.
2. **Boxplots:** Used to identify outliers and understand the range and interquartile range (IQR) of variables like `Age` and `TotalAmount_Spent`.

## Advanced Analysis

The project currently focuses on descriptive statistics and exploratory data analysis (EDA). Future enhancements could include:
- **Correlation Analysis:** Exploring relationships between different variables.
- **Predictive Modeling:** Extending the analysis to build predictive models based on the dataset.
- **Summary Tables:** Including summary tables of key statistics for quick reference.

## Installation

To run this project, you'll need to have Python installed along with the following libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

You can install these dependencies using pip:
```bash
pip install pandas numpy matplotlib seaborn
```

## Usage

To replicate the analysis, you can run the Jupyter notebook provided in this repository. The notebook includes all the code and outputs necessary to reproduce the analysis.

## Data Insights

This project provides insights into:
- The distribution of age among participants.
- Spending behavior on Mnt products.
- Educational attainment in years.
- Acceptance rates of campaigns.

## Conclusion

The analysis reveals key trends and distributions within the dataset, which could be useful for understanding the demographic and behavioral patterns of the participants. Further analysis could enhance the insights derived from this dataset.
