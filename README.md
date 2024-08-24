# Coffee Shop Sales Predictive Analysis

## Table of Contents

- [Overview](#overview)
- [Dataset Details](#dataset-details)
- [Data Preparation](#data-preparation)
- [Exploratory Analysis](#exploratory-analysis)
- [Model Building](#model-building)
- [Evaluation Metrics](#evaluation-metrics)
- [Scenario Analysis](#scenario-analysis)
- [Loss Mitigation Strategies](#loss-mitigation-strategies)
- [Conclusion](#conclusion)
- [Tools and Technologies Used](#tools-and-technologies-used)
- [Requirements](#requirements)
- [Acknowledgements](#acknowledgements)

## Overview

This project involves analyzing and predicting sales and profit margins for a coffee shop using Databricks, PySpark, and Spark SQL. The goal is to preprocess the data, conduct exploratory analysis, build predictive models, and visualize sales trends and profit margins.

## Dataset Details

The dataset comprises sales transactions for a coffee shop, including:

- `transaction_id`: Unique identifier for each transaction.
- `transaction_date`: Date of the transaction.
- `transaction_time`: Time of the transaction.
- `transaction_qty`: Quantity of items sold.
- `store_id`: Identifier for the store location.
- `store_location`: Location of the store.
- `product_id`: Identifier for the product.
- `unit_price`: Price per unit of the product.
- `product_category`: Category of the product.
- `product_type`: Type of product.
- `product_detail`: Detailed description of the product.

## Data Preparation

Data preparation steps include:

- **Handling Missing Values**: Identifying and addressing null values.
- **Correcting Inconsistencies**: Standardizing categorical data (e.g., converting to lowercase).
- **Calculating Revenue and Cost**: Computing total revenue and cost for each product.
- **Feature Engineering**: Creating new features such as profit margins and monthly sales.
- **Encoding Categorical Variables**: Using StringIndexer and VectorAssembler for machine learning.

## Exploratory Analysis

Exploratory analysis involves:

- **Visualizations**: Bar and line plots to analyze revenue, profit/loss, and sales trends.
- **Trend Analysis**: Monthly sales and revenue trends over time.
- **Store Performance**: Comparing performance across different store locations.

## Model Building

The project uses the following model:

- **Random Forest Regressor**: To predict profit margins based on features such as transaction quantity, unit price, and product category.

## Evaluation Metrics

Model performance is evaluated using:

- **Root Mean Squared Error (RMSE)**
- **R-squared (R2)**

## Scenario Analysis

Simulations are performed with different scenarios to predict profit/loss under varying conditions.

## Loss Mitigation Strategies

The analysis revealed no loss-making products. All products show a positive profit margin.

## Conclusion

The project successfully demonstrated the process of analyzing coffee shop sales data and predicting profit margins using Databricks, PySpark, and Spark SQL. The insights gained provide a basis for improving sales strategies and making informed decisions.

## Tools and Technologies Used

- **Databricks Community Edition**: Platform for development and execution of Spark jobs.
- **Apache Spark**: Unified analytics engine for large-scale data processing.
- **PySpark**: Python API for Spark, used for big data processing and machine learning.
- **Spark SQL**: Component for querying data using SQL.
- **Matplotlib**: Library for visualizing data.

## Requirements

- Python 3.6+
- PySpark
- Databricks Community Edition

## Acknowledgements

Thanks to the [InternnCraft](https://www.linkedin.com/company/internncraft) platform for the opportunity to work on this project. Special thanks to the data community for their resources and support, and to Databricks for providing the platform.
