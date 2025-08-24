# Fifa_data_massaging_notebook.ipynb

This notebook applies “data massaging” techniques to fifa_eda.csv.

What it covers

Explore: head(20), tail(5), sample(10), describe(), dtypes.

Clean: Convert Value, Wage, Release Clause from strings like €120K / €45M to numeric.

Engineer: Create Years Playing from Joined.

Filter & Sort: Players with Nationality == "Mexico" and order by Release Clause.

Aggregate: groupby('Joined') to get number of players per year.

Visualize: Bar chart of players per year.
