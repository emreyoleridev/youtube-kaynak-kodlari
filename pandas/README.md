# pandas 3 — Zero to Pro, in 1 video

Source code for the pandas 3 course on the channel. Each notebook is one part of the video and runs on its own (parts 2+ start with a setup cell that repeats the earlier steps).

| # | Notebook | What it covers |
|---|----------|----------------|
| 01 | [Why pandas?](01_why_pandas.ipynb) | What pandas is, checking your version, and one display setting before we load the data. |
| 02 | [Series & DataFrame](02_series_dataframe.ipynb) | The two building blocks of pandas: a single labeled column, and a table made of them. |
| 03 | [Reading Data & First Look](03_reading_data.ipynb) | Loading a real dataset straight from a URL, then the first checks we run on every new dataset. |
| 04 | [Selecting Rows & Columns](04_selecting.ipynb) | Picking only the columns and rows we need: [] for columns, loc by label, iloc by position. |
| 05 | [Filtering Rows](05_filtering.ipynb) | Keeping only the rows that match a condition: masks, & and |, isin, between, query and the new filter. |
| 06 | [Missing Data](06_missing_data.ipynb) | Counting the empty cells, then filling or dropping them: isna, fillna and dropna. |
| 07 | [Text & Dates](07_text_dates.ipynb) | Cleaning text columns with .str, and turning written dates into real dates with to_datetime and .dt. |
| 08 | [New Columns](08_new_columns.ipynb) | Making new columns from old ones: plain column math, assign with pd.col, and why apply is slow. |
| 09 | [Sorting](09_sorting.ipynb) | Putting rows in order with sort_values, and the quick way to the top or bottom n: nlargest and nsmallest. |
| 10 | [groupby & Pivot Tables](10_groupby_pivot.ipynb) | Splitting the table into groups and summarizing each one: groupby, agg with named results, and pivot_table. |
| 11 | [merge & concat](11_merge_concat.ipynb) | Joining two tables on a shared column with merge (inner and left), and stacking tables with concat. |
| 12 | [Quick Plot](12_quick_plot.ipynb) | Turning a column into a chart in one line with pandas' built-in plot. |
| 13 | [Saving: CSV & Parquet](13_saving.ipynb) | Saving the clean table, then reading it back: CSV forgets the types, Parquet keeps them. |
| 14 | [pandas 3 Pitfalls](14_pandas3_pitfalls.ipynb) | Old habits that break in pandas 3: chained assignment, inplace=True, and checking for object text columns. |
| 15 | [Mini Project: 3 Questions](15_mini_project.ipynb) | Putting it all together: three real questions about Netflix, each answered in one line. |

## Requirements

- Python 3.10+
- `pip install -U pandas pyarrow matplotlib`

The notebooks were run with pandas 3.1.1.

## Dataset

Netflix titles from [TidyTuesday](https://github.com/rfordatascience/tidytuesday/tree/master/data/2021/2021-04-20) (2021-04-20). Part 3 reads it straight from the URL, so no download is needed.
