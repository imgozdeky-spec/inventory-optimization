# Inventory Optimization and Demand Forecasting

## Project Overview

This project focuses on analyzing historical sales data and supporting inventory management decisions through data-driven methods.

The project combines demand analysis with classical inventory optimization techniques to determine appropriate inventory levels and replenishment decisions.

## Project Objectives

* Analyze historical product demand
* Calculate average and recent daily demand
* Estimate demand variability
* Determine safety stock levels
* Calculate reorder points
* Calculate Economic Order Quantity (EOQ)
* Support data-driven inventory planning

## Methodology

The project uses historical sales data to calculate key inventory management parameters.

### 1. Demand Analysis

Historical sales data is analyzed to identify average daily demand and recent demand trends.

### 2. Safety Stock

Safety stock is calculated based on demand variability, lead time, and the desired service level.

### 3. Reorder Point

The reorder point determines when a new inventory order should be placed.

### 4. Economic Order Quantity (EOQ)

EOQ is used to estimate an order quantity that balances ordering and holding costs.

## Technologies

* Python
* Pandas
* NumPy
* Matplotlib

## Project Structure

```text
inventory-optimization/
│
├── data/
│   └── sales_data.csv
│
├── src/
│   ├── data_analysis.py
│   ├── demand_forecast.py
│   └── inventory_optimization.py
│
├── outputs/
│
├── notebooks/
│
├── README.md
└── requirements.txt
```

## Key Outputs

The project aims to provide:

* Average daily demand
* Recent demand estimation
* Safety stock
* Reorder point
* Economic Order Quantity (EOQ)
* Demand visualization

## Assumptions

For demonstration purposes, the project uses a sample sales dataset and predefined inventory parameters such as lead time, ordering cost, and holding cost.

These parameters can be replaced with real company data for practical applications.

## Future Improvements

Future versions of the project may include:

* Machine learning-based demand forecasting
* Multi-product inventory optimization
* Dynamic safety stock calculation
* Seasonal demand analysis
* ABC inventory classification
* Interactive inventory dashboard
* Real-time inventory monitoring

## Purpose

This project was developed as a portfolio project to demonstrate practical applications of data analysis, inventory management, and industrial engineering methods using Python.
