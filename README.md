# Chart Recommender
Python library that implements [From data to viz](https://www.data-to-viz.com/)'s chart recommendation rules.

# Usage

## Command-line interface (CLI)

Run `recommend.py`

```bash
python recommend.py
```

This uses `data.xlsx` file and recommends few charts as an output:

```bash
{'chart_list': ['lollipop', 'bar_plot', 'circular_bar_plot', 'treemap', 'circlepack']}
```

It runs `initiate()` function which uses two columns `ID` (categorical column with unique observations/values) and `c1` (numeric column) to recommend charts.

## As a service

```py
import recommend

recommend.initiate('')
```

# TODO

## CLI tool

- [ ] Accept Google spreadsheet URL as input
- [ ] Accept local data file as input
- [ ] Accept a subset of columns

## Contributions

- Bhanu Kamapantula <bhanu.kamapantula@gramener.com>
- Tejesh <tejesh.p@gramener.com>
- Pragnya Reddy <pragnya.reddy@gramener.com>

