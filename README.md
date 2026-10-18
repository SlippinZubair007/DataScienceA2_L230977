# Data Science Assignment 2 — Cleaned EDA Datasets

Roll Number: 23L-0977  
Version: v1.0  
Publication Date: 18 October 2026

## Overview

This repository contains two cleaned datasets prepared for Exploratory Data Analysis (EDA) in Data Science Assignment 2.

The datasets were examined for missing values, duplicates, inconsistent formatting, invalid numerical values, and unusual observations. Cleaning decisions were documented, and additional features were created to support further analysis.

## Dataset 1: Netflix Titles

Original Source: https://www.kaggle.com/datasets/shivamb/netflix-shows

Cleaned File: `23L_0977_A2_netflix_cleaned.csv`

Records: 8,807

Cleaning and preprocessing:
- Handled missing descriptive information using "Unknown".
- Corrected three misplaced movie duration values.
- Converted valid addition dates.
- Created separate movie duration and TV show season count variables.
- Created year and month features from addition dates.
- Created country count, genre count, and release-to-addition gap features.
- Retained plausible unusual observations rather than deleting them automatically.

No original titles were removed.

## Dataset 2: Supermarket Sales

Original Source: Supermarket Sales CSV provided by the course instructor.

Cleaned File: `23L_0977_A2_supermarket_cleaned.csv`

Records: 1,000

Cleaning and preprocessing:
- Checked missing values and duplicate transaction identifiers.
- Checked categorical consistency and branch-city relationships.
- Verified the financial calculations.
- Converted date and time columns.
- Added Month, Month_Name, Weekday, and Hour features.
- Retained plausible numerical outliers.

No original transactions were removed.

## Version History

### v1.0 — 18 October 2026

Initial public release of both cleaned datasets, prepared for Data Science Assignment 2.

## Reuse Notes

The Netflix dataset contains multi-valued country and genre fields that may require further encoding.

The Supermarket Sales dataset contains several mathematically related financial columns. These should be handled carefully during correlation analysis and predictive modelling.

Both datasets are provided for educational analysis and future coursework.