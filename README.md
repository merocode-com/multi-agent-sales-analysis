# Sales Analysis

A **multi-agent** project for sales analysis.

> ⚠️ **Work in progress** — this project is under active development and not yet complete.

## Overview

This project uses a multi-agent approach to analyze sales data, surfacing trends,
insights, and reporting from raw sales datasets.

## Dataset

This project uses the **Coffee Sales** dataset from Kaggle.

- **Source:** https://www.kaggle.com/datasets/ihelon/coffee-sales
- **Author:** ihelon
- **License:** [CC0 1.0 (Public Domain Dedication)](https://creativecommons.org/publicdomain/zero/1.0/) — free to use without restriction or attribution
- **Location in repo:** `data/coffee-sales/`
- **Description:** Transaction-level records of coffee vending-machine sales —
  date/time, payment type, product (coffee name), and amount per sale.

Files:

| File | Columns | Rows |
|------|---------|------|
| `index_1.csv` | `date`, `datetime`, `cash_type`, `card`, `money`, `coffee_name` | 3,636 |
| `index_2.csv` | `date`, `datetime`, `cash_type`, `money`, `coffee_name` | 262 |

> Note: `index_2.csv` has no `card` column (it includes cash transactions).

To refresh the data from source, download it from the Kaggle link above
(a free Kaggle account is required) and place the file(s) in `data/coffee-sales/`.

## Project Structure

```
multi-agent-sales-analysis/
├── data/
│   └── coffee-sales/   # Coffee Sales dataset (index_1.csv, index_2.csv)
├── notebooks/          # Jupyter notebooks for exploration and analysis
├── .gitignore
└── README.md
```

## Tech Stack

- Python
- Jupyter Notebook

## License

- **Code** in this repository is licensed under the [MIT License](LICENSE)
  © 2026 Amira Ghoneim and Merocode.
- **Data** in `data/coffee-sales/` comes from Kaggle and is released under
  [CC0 1.0 (Public Domain)](https://creativecommons.org/publicdomain/zero/1.0/),
  free to use without restriction or attribution.

## Status

🚧 WIP — components, agents, and documentation are still being built out.
