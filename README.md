# kost-rental-data-analysis
Exploratory Data Analysis of Kost Rental Listings using Microsoft Excel

## Project Overview

This project focuses on Exploratory Data Analysis (EDA) of kost rental listings in the Jabodetabek area using Microsoft Excel.

The analysis was conducted to understand the distribution of kost listings, rental price variations, and differences across regions and kost types. The project covers data cleaning, descriptive statistics, data analysis, visualization, and insight generation.

---

## Project Objectives

The main objectives of this project are:

- To clean and prepare kost rental listing data for analysis.
- To understand the distribution of kost listings across different regions.
- To analyze rental price variations across regions.
- To compare rental prices and listing counts based on kost types.
- To identify the minimum and maximum rental prices.
- To perform an initial inspection of potential price outliers.
- To extract meaningful insights from the dataset.

---

## Dataset

The dataset contains **2,486 kost rental listings** with information related to rental prices, locations, kost types, facilities, ratings, and other listing attributes.

Some of the main columns used in the analysis include:

- `region`
- `location`
- `price`
- `price_clean`
- `tipe kost`
- `room size`
- `all fasilitas`
- `rating`

For this analysis, the main focus was placed on **region, rental price, and kost type**.

---

## Tools & Technologies

- **Microsoft Excel**
- Pivot Tables
- Excel Formulas
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization

---

## Data Cleaning

The dataset was reviewed and cleaned using Microsoft Excel.

The main cleaning steps included:

- Checking missing values.
- Checking duplicate records.
- Reviewing data types and formatting inconsistencies.
- Converting rental prices from text format into numeric values.
- Creating a `price_clean` column for numerical analysis.
- Handling `N/A` values in the `price before discount` column by excluding them from numerical calculations.
- Preserving the original data while creating cleaned columns for analysis.

Example of the original price format:

`Rp1.000.000`

After cleaning:

`1000000`

---

## Exploratory Data Analysis

Several analyses were performed using Pivot Tables and Excel formulas.

### 1. Number of Kost Listings by Region

A Pivot Table was created to determine the number of kost listings available in each region. The results were then visualized using a bar chart to facilitate comparison across regions.

**Key finding:**  
Bekasi has the highest number of kost listings, while East Jakarta has the lowest number of listings.

![Number of Kost Listings by Region](Visualizations/Number%20of%20Kost%20Listings%20by%20Region.png)

---

### 2. Average Rental Price by Region

A Pivot Table was used to calculate and compare the average rental price across different regions.

**Key finding:**  
South Jakarta has the highest average rental price, while Bogor has the lowest average rental price.

![Average Rental Price by Region](Visualizations/Average%20Rental%20Price%20by%20Region.png)

---

### 3. Average Rental Price by Kost Type

A Pivot Table was used to compare the average rental prices based on each kost type.

The analysis shows differences in the average rental prices among the different kost types.

**Key finding:**  
Mixed Kost has the highest average rental price, while Male Kost has the lowest average rental price.

![Average Rental Price by Kost Type](Visualizations/Average%20Rental%20Price%20by%20Kost%20Type.png)

---

### 4. Number of Kost Listings by Kost Type

The number of kost listings was analyzed based on each kost type using a Pivot Table. The results were then visualized using a bar chart.

**Key finding:**  
Mixed Kost has the highest number of listings, while Male Kost has the lowest number of listings.

![Number of Kost Listings by Kost Type](Visualizations/Number%20of%20Kost%20Listings%20by%20Kost%20Type.png)

---

## Descriptive Statistics

The rental price analysis was performed using the cleaned `price_clean` column.

| Metric | Result |
|---|---:|
| Minimum Rental Price | Rp450,000 |
| Maximum Rental Price | Rp4,500,000 |

The rental prices range from **Rp450,000 to Rp4,500,000**, indicating considerable variation among the analyzed listings.

---

## Outlier Analysis

An initial outlier inspection was conducted by reviewing several rental prices at the lowest and highest ends of the dataset.

The observed rental price range was:

**Rp450,000 – Rp4,500,000**

Based on the initial inspection, no values appeared to be extremely isolated from the other observations. Therefore, the minimum and maximum values were retained for the analysis.

> Note: This was an initial inspection rather than a statistical outlier test such as the IQR method.

---

## Key Insights

The analysis resulted in several key findings:

1. **Regional Distribution**  
   Bekasi has the highest number of kost listings, while East Jakarta has the lowest number of listings.

2. **Regional Price Differences**  
   South Jakarta has the highest average rental price, while Bogor has the lowest average rental price.

3. **Kost Type Differences**  
   Mixed Kost has the highest average rental price, while Male Kost has the lowest average rental price.

4. **Listing Distribution by Kost Type**  
   Mixed Kost has the largest number of listings, while Male Kost has the smallest number of listings.

5. **Rental Price Variation**
   Rental prices in the dataset range from Rp450,000 to Rp4,500,000.

---

## Conclusion

This project analyzed kost rental listings using Microsoft Excel, covering data cleaning, descriptive statistics, regional analysis, kost type analysis, and rental price analysis.

The results show differences in the number of listings and average rental prices across regions and kost types. Bekasi had the highest number of listings, while South Jakarta had the highest average rental price.

Overall, this project demonstrates the use of Microsoft Excel to clean, analyze, visualize, and extract meaningful insights from rental listing data.

---

## Project Files

- Excel Analysis: `Mamikos Jabodetabek Data1.xlsx`
- **Report:** `report.pdf`
- **Visualizations:** Available in the `Visualizations` folder.
