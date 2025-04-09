# Data Quality Toolkit

Welcome to the **Data Quality Toolkit** repository! Here you’ll find:

1. A **comprehensive Jupyter Notebook** demonstrating a reusable framework to assess and improve the quality of your datasets.  
2. A **YouTube video** that walks you through these methods in detail—perfect if you’d like a more visual, step-by-step explanation.

This toolkit focuses on six key dimensions of data quality—**Accuracy**, **Completeness**, **Uniqueness**, **Consistency**, **Timeliness**, and **Validity**—giving you a thorough overview of potential issues in your data and how to address them.

---

## Contents

1. **[Notebook](DataQualityChecker.ipynb)**: A hands-on guide with code samples for each data quality dimension.  
2. **YouTube Video**: Covers the concepts and demos featured in the notebook.

---

## Features

- **Completeness**: Identifies how many values are missing (null/NaN) and calculates the percentage of missing records per column.  
- **Uniqueness**: Flags duplicate rows or records (optionally, based on select columns).  
- **Validity**: Checks formatting and ranges (e.g., regex for emails, numeric limits for height).  
- **Accuracy**: Verifies real-world plausibility (e.g., checking if height is in a realistic range).  
- **Consistency**: Compares related fields (like `Age` vs. `DateOfBirth`) to identify logical mismatches.  
- **Timeliness**: Ensures records are up-to-date by comparing `LastUpdated` to a threshold date.

---

## Requirements

- **Python 3.7+**  
- [**pandas**](https://pandas.pydata.org/) (for data manipulation)  
- [**numpy**](https://numpy.org/) (for numerical operations)  
- **datetime** (standard Python library)

You can install the external dependencies using:

```bash
pip install pandas numpy

## How to Use

**Clone the Repository**:
   ```bash
   git clone https://github.com/david-ikenna-ezekiel/data-quality-toolkit.git
   cd your-repo-name
