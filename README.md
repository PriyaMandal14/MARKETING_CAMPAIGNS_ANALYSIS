# Marketing Campaign Analysis

## Project Overview

This project analyzes customer marketing data to understand customer behavior, purchasing patterns, and responses to marketing campaigns.

The analysis includes data cleaning, feature engineering, exploratory data analysis, hypothesis testing, and visualization using Python.

## Dataset

The dataset contains **2,240 customer records and 28 columns** with information related to:

* Customer demographics
* Education and marital status
* Income
* Number of children and teenagers at home
* Product spending
* Web, catalog, and store purchases
* Marketing campaign responses
* Customer complaints
* Country

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Google Colab

## Project Steps

### 1. Data Import & Inspection

* Imported the marketing dataset using Pandas
* Checked the dataset structure and dimensions
* Inspected data types and descriptive statistics
* Checked for missing values

### 2. Data Cleaning

* Handled missing income values using the mean based on education and marital status
* Standardized marital status categories by combining similar values

### 3. Feature Engineering

Created new features to improve the analysis:

* **Age** – calculated from year of birth
* **Total Children** – combination of children and teenagers at home
* **Total Spend** – total spending across product categories
* **Total Purchases** – total purchases across web, catalog, and store channels

### 4. Exploratory Data Analysis

The project uses visualizations to explore:

* Income distribution
* Customer age distribution
* Correlations between numerical variables
* Product spending
* Customer purchases
* Campaign acceptance
* Relationship between children and spending

### 5. Hypothesis Testing

Statistical tests were performed to investigate questions such as:

* Whether customers above and below age 50 differ in store purchases
* Whether customers with children differ from customers without children in web purchases
* The relationship between web, catalog, and store purchases
* Whether customers from the US differ from customers from other countries in total purchases

### 6. Customer & Campaign Insights

The project also analyzes:

* Best and worst-performing product categories based on average spending
* Age versus campaign acceptance
* Campaign acceptance across countries
* Relationship between number of children and total spending
* Complaints across education groups

## Key Statistical Findings

* Store purchases showed a statistically significant difference between customers above 50 and customers aged 50 or below (`p < 0.001`).
* Web purchases showed a statistically significant difference between customers with children and customers without children (`p < 0.001`).
* Web, catalog, and store purchases showed positive correlations with each other.
* The comparison between US customers and customers from other countries did not show a statistically significant difference in total purchases (`p > 0.05`).

## Project File

The complete analysis is available in:

`Project2.ipynb`

## How to Run the Project

1. Download or clone this repository.
2. Open `Project2.ipynb` in Google Colab or Jupyter Notebook.
3. Make sure `marketing_data1.csv` is available in the working directory.
4. Run the notebook cells in order.

## Author

**Priya Mandal**

