# CMJ–Pitching Correlation Analysis

This folder contains Python notebooks for examining relationships between countermovement jump (CMJ) measurements and baseball pitching metrics.

The workflow processes CMJ and pitching data, matches records using athlete identifiers and dates, and calculates Pearson correlation coefficients by pitcher and pitch type.

## Notebooks

### `ORIGINAL_cmj_pitching_correlation.ipynb`

Preserves the initial correlation-analysis workflow, including data preparation, CMJ averaging, record matching, correlation calculations, and PDF report generation.

### `IMPROVED_cmj_pitching_correlation.ipynb`

Contains a later revision with additional data validation and reporting. Repeated CMJ trials are averaged by athlete and testing date, and individual pitching records are matched to CMJ measurements from the same athlete and calendar date.

The revised notebook also reports observation counts and checks for insufficient data when calculating correlations.

## Outputs

The workflow generates a PDF report containing correlation results organized by pitcher and pitch type.

The correlation coefficients describe linear relationships in the analyzed data. They do not establish causation.

## Data Availability

Research data and generated reports are not included to protect athlete privacy and research confidentiality. The notebooks require appropriately formatted input data to run.
