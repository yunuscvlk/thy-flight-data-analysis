# THY Flight Data Analysis

## Project Overview

This project aims to perform data processing, cleaning, analysis, classification and clustering on Turkish Airlines (THY) flight data. The dataset includes THY flight information, airport coordinate data and additional country-related information. The analysis was conducted in a big data environment using Apache Hadoop & Hive, Apache Spark & PySpark.

## Tools

- **Apache Hadoop & Hive** - Distributed data storage, processing, and querying
- **Apache Spark & PySpark** - Data processing, analysis and machine learning
- **Pandas** - Data manipulation
- **Matplotlib** - Data visualization
- **PySpark ML** - Machine learning, classification and K-Means clustering

## Data Source and Features

The THY dataset was obtained from the **Data Engineer Path** course on the **Miuul** educational platform and consists of the following sections:

- **THY Flight Data:** Original and destination airports, flight type and duration.
- **IATA Airport Data:** IATA codes, airport names and geographical coordinates.
- **Country Data:** Countries and regions where airports are located.

## Data Processing and Analysis Steps

- **Data Loading and Merging:** THY, IATA and country data were combined.
- **Data Cleaning:** Missing and invalid data were filtered.
- **Exploratory Data Analysis (EDA):** The dataset was examined and statistical summaries were generated.
- **Visualization:** Flight density maps and trend analyses were conducted.
- **Machine Learning:**
    - **Clustering:** K-Means algorithm was applied to cluster flight data.
    - **Classification:** Flight data was categorized into specific groups.

## Results

This project demonstrates the application of data analysis and machine learning techniques on large datasets using Apache Hadoop & Hive, Apache Spark & PySpark. It provides valuable insights into flight grouping, passenger mobility trends and flight classification.

[Click here](notebooks/thy-analysis.ipynb) to explore the detailed analysis and visualizations.