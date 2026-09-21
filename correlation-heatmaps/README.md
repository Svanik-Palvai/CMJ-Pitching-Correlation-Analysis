# CMJ–Pitching Correlation Heatmaps

This folder contains Python notebooks for generating correlation matrices and heatmaps from CMJ and pitching data.

The analysis groups pitchers by the percentage of their recorded pitches classified as fastballs, then generates separate correlation matrices for fastballs, changeups, sliders, and curveballs within each pitcher group.

## Notebooks

### `ORIGINAL_cmj_pitching_heatmaps.ipynb`

Preserves the initial heatmap workflow, including its original data-cleaning, pitcher-grouping, and visualization procedures.

### `IMPROVED_cmj_pitching_heatmaps.ipynb`

Contains a later revision with additional input validation, updates to data processing and pitcher classification, and more accurate reporting of generated files.

## Outputs

When sufficient data is available, the notebooks generate PNG heatmaps and Excel files containing correlation coefficients. The number of outputs depends on which pitcher-group and pitch-type combinations have enough observations.

The heatmaps describe correlations in the analyzed records. Repeated pitch observations from the same pitcher should not be interpreted as independent athlete-level measurements.

## Data Availability

Research data and generated results are not included to protect athlete privacy and research confidentiality. The notebooks require appropriately formatted input data to run.
