# FAX-Data-analysis
FAX Store Sales Analysis- 2024 First Half

## Table of contents:
- [Introduction/Project Overview](#Introductionproject-overview)
-	[Data Source](#Data-Source)
-	[Tools](#Tools)
-	[Data Cleaning/Preparation](#Data-CleaningPreparation)
-	[Exploratory Data Analysis](#Exploratory-Data-Analysis)
-	[Data Analysis](#Data-Analysis)
-	[Results/Findings](#ResultsFindings)
-	[Recommendations](#Recommendations)
-	[Limitations](#Limitations)
-	[References](#References)

***

### Introduction/Project Overview:

This is a python and SQL project on an imaginary supermarket called FAX STORE.
This analysis project aims to analyse the sales the FAX Store made over the 1st half of the year 2024. From this data analysis, we want to identify the trend of sales, make data-driven recommendations, gain a deeper understanding of FAX store’s performance, and make critical decisions regarding the progress of the organization.


![FAX SALE ANALYSIS CORRECTED](https://github.com/RT-2024/FAX-Data-analysis/assets/173732703/c3fb0cfd-4b10-4e75-88f0-407954177813)


### Data Source:

The primary dataset used for this analysis is the “fax.csv” file. It contains detailed information about each sale made by the store in the 1st half of 2024.

### Tools:

-	Excel
-	Python Data Analysis (Spyder)

### Data Cleaning/Preparation:

In the initial data preparation phase, I performed the following tasks:
1. Data loading and Inspection
2. Handling missing values
3. Data cleaning and formatting

### Exploratory Data Analysis:

EDA provides the means to exploring the sales data to answer critical questions such as:
- What is the overall sales trend?
- Which products are top sellers?
- What are the peak sales period?
- What could account for the peak sales period of certain items?

### Data Analysis:

Some interesting codes/features worked with:
```python
fax = pd.read_csv("C:\\Users\\tomee\\Documents\\DATA ANALYSIS\\FAX STORES SALES ANALYSIS 2.csv")
```

```python
fax_clean.columns = [i.lower() for i in fax_clean.columns]
```

```sql
fax_sql = select * from fax
```

### Results/Findings:

- Items like stationeries and detergent were top sellers all through the 1st half. Perhaps because the store is in a school environment where they are needed frequently.
- Items like umbrellas & sweaters increased in sales as the raining season approached (May, June).
- Sale of sanitizers increased in the month of June. Perhaps because of the cholera outbreak that occurred in June.

### Recommendations:

-	The store should invest in stocking and marketing students/children items during the months of school resumption.
-	Items like stationeries and detergent should be stocked up in a variety of brands all through the year.
-	Items like umbrellas & sweaters should be stocked up as the raining season approaches.

### Limitations:
I had to remove all missing values and zeros from Jan-June columns as they would have impacted the accuracy of my result and the findings of this analysis.

### References:
FAX STORE RECORDS 2024

*Table*

  |Column1|Column2|
  |-------|-------|
  |SQL|Python|

  😄 😏
