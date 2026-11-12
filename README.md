# SIADS521_Ass3
Assignment3-Nov_2026

This SIADS 521 project compares 12 quarters of SEC Form 13F filings for Third Point and ValueAct, from 2023 Q1 through 2025 Q4. The dashboard links a scatter plot, slope chart, paired bars, and a heatmap to show how reported share counts, portfolio weights, and holding ranks changed.

## Explore the project

- **Interactive dashboard** — Download `linked_holdings_dashboard.html` from the [results folder](results/) and open it in your browser. Use the **Manager** and **Ending quarter** dropdowns, then hover over a holding for details.
- **[Narrative notebook](Assignment3.ipynb)** — Research question, data preparation, visualization choices, findings, and AI use log.
- **[Supporting results](results/)** — Standalone HTML charts, CSV tables, and the [top-10 concentration chart](results/top10_concentration.png).


## Reproduce the analysis

Download or clone this repository, keeping both SEC filing folders beside `Assignment3.ipynb`. With Python 3.12, install the packages listed in `requirements.txt`:

```powershell
python -m pip install -r requirements.txt
```

Open the notebook, select that Python environment as the kernel, and run all cells. The export cell writes the dashboard and supporting files to `results/`. The filing indexes in each data folder link to the original SEC submissions.
