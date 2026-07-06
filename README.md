# Customer Value Segmentation and CLV Analysis

## Overview

This project analyses customer lifetime value (CLV) and behavioural segmentation using retail transaction data.

The objective is to identify high-value customer segments and translate purchase behaviour into actionable marketing recommendations.

## Business Problem

Retailers need to understand which customers generate the greatest long-term value, what behaviours define them, and how similar high-value prospects can be identified earlier.

## Data

The analysis uses household-level retail transaction data and demographic segmentation data.

Main files:
- `transaction_data.csv`: household-level transaction records
- `hh_demographic.csv`: household demographic segmentation
- `Dummyhumby_CLV.ipynb`: Python analysis notebook

### Dataset

The original transaction dataset is not included in this repository due to file size limitations.
Please refer to the official dunnhumby "The Complete Journey" dataset for the original data.

## Methods

- Data cleaning and aggregation
- Customer Lifetime Value calculation
- Purchase frequency analysis
- Average basket value analysis
- Recency and behavioural segmentation
- High-value customer profiling

## Repository Structure

```text
.
├── Dummyhumby_CLV.ipynb
├── transaction_data.csv
├── hh_demographic.csv
└── README.md
