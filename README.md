# Python Basics for Data Analysis

This repository contains notebook-based teaching material for a beginner-friendly Python course taught by ELIXIR-EE for the ELIXIR-CZ node.

The course is designed for learners who are new to Python or still building confidence. It supports both classroom teaching and self-study, with explanations, runnable examples, and independent practice tasks.

## Course Structure

### Day 1 - Python Programming for Beginners

| Time | Session |
| --- | --- |
| 09:30 - 09:40 | Welcome and course overview |
| 09:40 - 11:40 | Hands-on session |
| 11:40 - 12:40 | Lunch |
| 12:40 - 14:10 | Hands-on session |
| 14:10 - 14:25 | Break |
| 14:25 - 15:25 | Hands-on session |

Notebook: [01_python_programming_basics.ipynb](01_python_programming_basics.ipynb)

### Day 2 - Data Visualisation and Data Handling with Python

| Time | Suggested focus |
| --- | --- |
| 09:30 - 11:30 | Pandas foundations: loading, inspecting, selecting, filtering, sorting, creating columns |
| 11:30 - 12:30 | Lunch |
| 12:30 - 14:00 | Pandas for analysis: missing values, merging, grouping, pivoting, reshaping |
| 14:00 - 14:15 | Break |
| 14:15 - 15:15 | Seaborn-first visual exploration, with Matplotlib for labels, layout, and figure control |

Notebooks:

- [02_tabular_data_with_pandas.ipynb](02_tabular_data_with_pandas.ipynb)
- [03_exploratory_visualisation_with_seaborn.ipynb](03_exploratory_visualisation_with_seaborn.ipynb)

## Preparation for the Next Course

These materials are intended to prepare participants for the next statistics course:

[bioinfocz/IMG-Statistics-in-Python-Course](https://github.com/bioinfocz/IMG-Statistics-in-Python-Course/tree/master)

After this course, learners should be ready to:

- read and run Jupyter notebooks
- write basic Python commands
- understand variables, core data types, loops, conditions, functions, files, and imports
- load CSV data into pandas
- inspect, filter, transform, group, and reshape DataFrames
- create clear exploratory plots with seaborn and adjust them with Matplotlib
- explain what each row, column, grouping, and plotted mark represents

## Data

The pandas and visualisation notebooks use `data/Islander_data.csv`, a small teaching dataset about memory scores in virtual participants.

Source: Ahn, Steve. *Memory Test on Drugged Islanders Data*. Zenodo, 2025. DOI: [10.5281/zenodo.15369169](https://doi.org/10.5281/zenodo.15369169). License: Creative Commons Attribution 4.0 International.

## Running Locally

Install the Python packages with:

```bash
python3 -m pip install -r requirements.txt
```

Then open the notebooks with Jupyter or VS Code. The notebooks also include Colab badges and can fall back to the public CSV URL if the local `data/` directory is unavailable.
