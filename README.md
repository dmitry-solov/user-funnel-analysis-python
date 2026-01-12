# User Behavior and Funnel Analysis (Python)

## Overview
This project focuses on exploratory data analysis and funnel analysis using event-based user data.
The goal is to analyze user behavior across different funnel steps and understand how users progress through sessions.

The project is designed as a practical exercise in data analysis, with an emphasis on data preparation, metric calculation and exploratory insights.

## Dataset
Source: Kaggle (event-level dataset)

The dataset contains user interaction events collected over time.
Each record represents a specific user action associated with a session and timestamp.

## Analysis Workflow

### 1. Load and Inspect the Data
- Loaded the dataset using pandas
- Inspected data structure, data types and missing values

### 2. Clean and Preprocess
- Cleaned and transformed raw data
- Handled missing and inconsistent values
- Prepared session-level structures for analysis

### 3. Funnel Conversion Rates
- Defined funnel steps based on user events
- Calculated conversion rates between funnel stages
- Identified drop-off points within the funnel

### 4. Event Distribution Over Time
- Analyzed event frequency over time
- Explored temporal patterns in user activity

### 5. Session Funnel Breakdown
- Analyzed funnel progression at session level
- Evaluated how users move through the funnel within individual sessions

## Tools and Technologies
- Python
- pandas
- matplotlib
- seaborn

## Notes
This project focuses on analytical workflow and metric calculation rather than business decision-making.
It serves as a demonstration of data cleaning, exploratory data analysis and funnel analysis skills.
