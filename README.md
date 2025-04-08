# Data 712 - Homework 8 

## Overview

This assignment builds on a previous analysis (Assignment 6) using the **Diabetes Health Indicators Dataset** from Kaggle [@teboul2023]. The analysis focuses on modeling the number of **mentally unhealthy days** (`ment_hlth`) and investigates how individual characteristics—such as **high blood pressure**, **age**, and **physical activity**—relate to mental health outcomes.

Assignment 8 emphasizes **clear presentation**, **citation practices**, and the use of **automated and reproducible tables** using R packages such as:

- `modelsummary` (for regression model tables)
- `tinytable` (for summary statistics)
- `distill` (for polished HTML reports)
- `Zotero` and `BibTeX` (for references)

## Files in This Repository

- `Assignment 8.Rmd`: The R Markdown document containing the full analysis.
- `Assignment 8.html`: The rendered report in HTML format using `distill::distill_article`.
- `Diabetes Health Indicators.csv`: The dataset used for the analysis (original from Kaggle).
- `references.bib`: The bibliography file generated with Zotero and used for in-text citations.
- `README.md`: This file.

## Key Methods

- **Poisson and Negative Binomial models** were fitted to account for overdispersion.
- Regression results were displayed using `modelsummary` with markdown formatting.
- Summary statistics were presented using `datasummary_skim()` from `tinytable`.
- The report was styled with the `cerulean` theme for clarity and visual appeal.

## Summary of Findings

- Physical activity is strongly associated with **fewer** mentally unhealthy days.
- High blood pressure is linked to **more** mentally unhealthy days.
- Age showed a small but significant negative association.
- The **Negative Binomial model** was better suited due to overdispersion, as confirmed in prior assignments.

## Citation

The dataset was obtained from Kaggle:

> Alex Teboul. *Diabetes Health Indicators Dataset*. Kaggle. 2023.  
> https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset

## RPubs Link
https://rpubs.com/data-jesse/1294640
