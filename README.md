# Financial Month-End Closing Automation with AI-Assisted Reporting

## Business Impact

This project is designed to support financial month-end closing by reducing repetitive manual work.

It helps finance teams:

- Automatically consolidate Excel reports from multiple departments
- Standardize inconsistent column names and formats
- Detect abnormal records before reporting
- Generate AI-assisted financial summaries for faster review

The goal is not to replace finance staff, but to reduce manual data preparation time and allow staff to focus on review, judgment, and decision-making.
## Project Overview
This project simulates a financial month-end closing process and builds an automated workflow for financial data integration, anomaly detection, and AI-assisted reporting.

## Problem
Financial departments often need to consolidate multiple Excel reports from different departments. These files may have inconsistent column names, different formats, and potential data errors, making month-end closing time-consuming and error-prone.

## Solution
This project uses Python to:
- Batch read multiple Excel files
- Standardize inconsistent column names
- Merge data into a consolidated table
- Detect anomalies such as negative amounts, abnormal values, and non-current-month records
- Use Gemini API to generate an AI-assisted financial summary report

## Key Features
- Excel batch processing
- Column mapping and standardization
- Rule-based anomaly detection
- AI-assisted summary generation
- Exported Excel report with anomaly list and AI summary

## Tech Stack
- Python
- Pandas
- NumPy
- OpenPyXL
- Google Gemini API
- Google Colab

## Project Positioning
This project does not use AI to directly judge financial correctness. Instead, rule-based logic is used for anomaly detection, while AI is used to summarize the results for better readability.
