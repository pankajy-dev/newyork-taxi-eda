# NYC Taxi EDA – Optimising NYC Taxis

Exploratory data analysis (EDA) of New York City yellow taxi trip records to assess taxi data and provide insights for better services.

## Objectives

- Clean and prepare the trip record data (missing values, outliers, invalid records).
- Analyse trip patterns by time (hour, day, month), location (pickup/dropoff zones), and distance.
- Study fares, tips, and payment types to understand revenue drivers.
- Derive recommendations to optimise taxi supply, routes, and pricing.

## Repository Contents

| File | Description |
|------|-------------|
| `EDA_Optimising_NYC_Taxis.ipynb` | Main Jupyter notebook with the full analysis |
| `Report.pdf` / `Report.odt` | Written report summarising findings and recommendations |
| `data_dictionary_trip_records_yellow.pdf` | Official data dictionary for yellow taxi trip records |
| `yearly_sampled_data.csv` | Sampled yearly trip data used for analysis |
| `dataset.zip` | Dataset archive |

## Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook or JupyterLab
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Run

```bash
git clone https://github.com/pankajy-dev/newyork-taxi-eda.git
cd newyork-taxi-eda
jupyter notebook EDA_Optimising_NYC_Taxis.ipynb
```

Ensure the data files (`dataset.zip` / `yearly_sampled_data.csv`) are available in the project root before running the notebook.

## Methodology

1. Data loading and sampling
2. Data cleaning and quality checks
3. Univariate and bivariate analysis
4. Time and location based analysis
5. Insights and recommendations

## Report

See [Report.pdf](Report.pdf) for the complete findings.

## Author

[pankajy-dev](https://github.com/pankajy-dev)
