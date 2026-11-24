<div align="center">

# 🏀 EDA Assignments: NBA All Elo

**Exploratory data analysis of ~111k rows of NBA game data (FiveThirtyEight's *NBA All Elo* dataset): data quality, distributions, outliers, transformations and bivariate relationships.**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C)
![seaborn](https://img.shields.io/badge/seaborn-4C72B0)

</div>

---

| Notebook | Topic |
|---|---|
| [A1](A1_YourLastName_EDA.ipynb) | **First look**: structure, types, missing values, duplicates, data-quality checks |
| [A2](A2_YourLastName_EDA.ipynb) | **Distributions, outliers and transformations**: points, Elo and margin of victory; mean vs median, IQR outliers, robust statistics, transformations |
| [A3](A3_YourLastName_EDA.ipynb) | **Bivariate EDA**: Pearson vs Spearman, nonlinear relationships, numerical vs categorical, correlation matrix, correlation ≠ causation |

The follow-up assignment, A4 (group comparisons and multivariate EDA), is in [university-coursework](https://github.com/AlisherKshtykenov/university-coursework/tree/main/exploratory_data_analysis/assignment04_groups_multivariate).

## Run

```bash
pip install -r requirements.txt
jupyter lab
```

The dataset is [`data/nbaallelo.csv`](data/nbaallelo.csv), from FiveThirtyEight under CC BY 4.0.

<sub>Course: Exploratory Data Analysis with Python.</sub>
