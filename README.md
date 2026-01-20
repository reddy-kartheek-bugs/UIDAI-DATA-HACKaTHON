# UIDAI Aadhar Data Analysis

## Project Overview

This project involves the analysis of Aadhar data, focusing on enrolment, biometric, and demographic trends across various states and districts in India. The goal is to derive insights from the UIDAI datasets to understand coverage, updates, and demographic distributions.

## Files Description

The repository contains the following key files:

- **`step1.ipynb`**: Jupyter notebook containing the initial steps for data loading, cleaning, and preliminary analysis.
- **`step3.ipynb`**: Jupyter notebook focusing on deeper analysis, including detailed visualizations and statistical breakdowns.
- **`dataset_stats.md`**: A markdown file providing a statistical summary of the datasets used, including file counts, structures (headers), and line counts.
- **`plots/`**: A directory containing generated plots and charts visualizing the analysis results (e.g., maintainability, migration trends).

## Dataset Information

The analysis is based on three main categories of data:

1.  **Aadhar Biometric Data**: Contains information on biometric updates (age groups 5-17, >17).
2.  **Aadhar Demographic Data**: Contains information on demographic updates (age groups 5-17, >17).
3.  **Aadhar Enrolment Data**: Contains information on new enrolments (age groups 0-5, 5-17, >18).

> [!IMPORTANT]
> **Note on CSV Files**
>
> The raw CSV data files used in this analysis are **NOT** included in this repository.
>
> **Reason**: The CSV files are extremely large in size, which makes them unsuitable for hosting on GitHub due to storage and bandwidth limitations.
>
> **How to Run**: To run the notebooks (`step1.ipynb`, `step3.ipynb`), you must obtain the datasets separately and place them in a directory named `datasets/` at the root of this project. Ensure the file structure matches the descriptions in `dataset_stats.md`.
