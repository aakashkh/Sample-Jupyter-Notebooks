# 📓 Sample Jupyter Notebooks

A curated collection of Jupyter notebooks covering Python, data manipulation, visualization, and machine learning — companion notebooks to blog posts on [data-patterns.netlify.app](https://data-patterns.netlify.app).

---

## 🐍 Python Basics

| Notebook | Description |
|---|---|
| [Break, Continue and Pass in Python](python-basics/Break,%20Continue%20and%20Pass%20in%20Python.ipynb) | Loop control flow with break, continue, pass |
| [Exception-Handling](python-basics/Exception-Handling.ipynb) | try/except blocks, raising and handling exceptions |
| [String Interpolation](python-basics/String%20Interpolation.ipynb) | f-strings, format(), % formatting |
| [Return, scope, args and kwargs in function](python-basics/Return,%20scope,%20args%20and%20kwargs%20in%20function.ipynb) | Function scope, *args, **kwargs, return values |
| [Handling Duplicates in Python](python-basics/Handling%20Duplicates%20in%20Python.ipynb) | Finding and removing duplicates in lists and DataFrames |

---

## 🐼 Pandas

| Notebook | Description |
|---|---|
| [Indexing and Sorting a dataframe using iloc and loc](pandas/Indexing%20and%20Sorting%20a%20dataframe%20using%20iloc%20and%20loc.ipynb) | Label vs position-based indexing, multi-level sorting |
| [Filtering using mask and where in pandas](pandas/Filtering%20using%20mask%20and%20where%20in%20pandas.ipynb) | Boolean masks, `.where()`, `.mask()` for conditional filtering |
| [Functions using apply, applymap and map](pandas/Functions%20using%20apply,%20applymap%20and%20map.ipynb) | Applying functions element-wise and row/column-wise |
| [Combining and Reshaping DataFrames](pandas/Combining%20and%20Reshaping%20DataFrames.ipynb) | `merge()`, `concat()`, `melt()`, `pivot()`, `pivot_table()` — with pitfalls |

---

## 📅 Datetime

| Notebook | Description |
|---|---|
| [Business Days with Custom Holidays](datetime/Business%20Days%20with%20Custom%20Holidays.ipynb) | Computing business day counts with pandas `offsets` and `numpy.busday` |
| [Months between two dates](datetime/Months%20between%20two%20dates.ipynb) | Various approaches to calculate months between dates |

---

## 📊 Visualization (Seaborn)

Series of notebooks walking through different Seaborn chart types with real datasets.

| Notebook | Description |
|---|---|
| [Seaborn - Data Preparation and Timings](visualization/Seaborn%20-%20Data%20Preparation%20and%20Timings.ipynb) | Part 0 — Data prep for the visualization series |
| [Seaborn - Violin, Box and Line Plot](visualization/Seaborn%20-%20Violin,%20Box%20and%20Line%20Plot.ipynb) | Part 1 — Distribution plots |
| [Seaborn - Distribution Plot and Facet Grid](visualization/Seaborn%20-%20Distribution%20Plot%20and%20Facet%20Grid.ipynb) | Part 2 — Distribution and small multiples |
| [Seaborn - Donut Chart](visualization/Seaborn%20-%20Donut%20Chart.ipynb) | Part 3 — Donut/pie chart variants |
| [Seaborn - Heatmap, Lollipop and Scatter Plot](visualization/Seaborn%20-%20Heatmap,%20Lollipop%20and%20Scatter%20Plot.ipynb) | Part 4 — Heatmaps and lollipop charts |
| [Seaborn - Radar Chart](visualization/Seaborn%20-%20Radar%20Chart.ipynb) | Part 5 — Radar/spider charts |

---

## ⚡ Polars

| Notebook | Description |
|---|---|
| [Polars Data Types](polars/Polars%20Data%20Types.ipynb) | Understanding Polars' type system — Numeric, String, Temporal, Nested |
| [Polars vs Pandas Comparison](polars/Polars%20vs%20Pandas%20Comparison.ipynb) | Side-by-side code comparison: filtering, groupby, joins, performance |

---

## 🤖 Machine Learning

| Notebook | Description |
|---|---|
| [Ensemble Models Guide](machine-learning/Ensemble%20Models%20Guide.ipynb) | Decision Trees, Random Forests, XGBoost — practical implementation pipeline |

---

## 🔗 Related Links

- 📝 **Blog**: [data-patterns.netlify.app](https://data-patterns.netlify.app)
- 🐍 **Open any notebook in Google Colab**: Click a notebook above → use the Colab badge or copy the raw URL into [colab.research.google.com](https://colab.research.google.com)

---

## 🚀 Running Locally

```bash
git clone https://github.com/aakashkh/Sample-Jupyter-Notebooks.git
cd Sample-Jupyter-Notebooks
pip install jupyter pandas numpy seaborn polars scikit-learn xgboost
jupyter notebook
```
