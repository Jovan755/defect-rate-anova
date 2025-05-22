# Defect-Rate Analysis of Three Production Lines

**Tools** : IBM SPSS  Dataset size : The workbook contains 25 rows × 2 columns of production-line defect data. Column A lists defect type; Column B stores number of defects

## Problem  
Which production line has a statistically higher defect rate
## Method  
1. One-way ANOVA to test overall difference  
2. Tukey HSD post-hoc for pairwise comparison

## Results  
* **F = 5.29**, **p = 0.023** – significant difference  
* Model A defect rate ≈ **10 pp** higher than Models B & C

![ANOVA table](images/anova_table.png)  
![Tukey HSD](images/tukey_plot.png)

## Recommendation  
Redesign or process adjust Line A; projected 30 % defect reduction.

## Reproduce  
Download `data/defects.xlsx`, open `notebooks/anova_repro.ipynb`, run all cells (Python 3.11).


