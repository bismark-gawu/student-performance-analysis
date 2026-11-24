# Student Performance Analysis

Exploratory data analysis of mathematics and Portuguese-language
student performance using Python, pandas, and Matplotlib.

## Project questions

- How are final grades distributed?
- How do average grades differ across weekly study-time groups?
- How do average grades differ across absence groups?

## Datasets

The data come from two secondary schools in Portugal.

| Dataset | Records | Columns |
|---|---:|---:|
| Mathematics | 395 | 33 |
| Portuguese language | 649 | 33 |

## Main findings

| Measure | Mathematics | Portuguese |
|---|---:|---:|
| Mean final grade | 10.42 | 11.91 |
| Median final grade | 11 | 12 |
| Most common final grade | 10 | 11 |
| Average grade with 0–10 absences | 10.47 | 12.01 |
| Average grade with over 10 absences | 10.15 | 10.65 |

Grades use a scale of 0–20. In both datasets, the 5–10 hours
weekly study group had the highest average final grade.

These comparisons describe each subject dataset separately.
Group differences may reflect other student characteristics.
The ten-absence cutoff was an exploratory analysis choice.

## Tools and skills

- Python and Jupyter Notebook
- pandas for inspection, filtering, grouping, and summaries
- Matplotlib for bar charts and scatter plots
- Interpretation of descriptive statistics and observed patterns

## Running the notebooks

1. Download the repository files.
2. Keep each CSV beside its corresponding notebook.
3. Open the notebooks in Jupyter with pandas and Matplotlib installed.
4. Restart the kernel and run all cells from top to bottom.

## Data source

Cortez, P. (2008). Student Performance [Dataset].
UCI Machine Learning Repository.

https://doi.org/10.24432/C5TG7T

The dataset is available under CC BY 4.0.
https://creativecommons.org/licenses/by/4.0/

## Author

Bismark Gawu
