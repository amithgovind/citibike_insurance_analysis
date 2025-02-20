# CitiBike Data Analysis Project

## Overview
This project analyzes CitiBike rental data to identify potential collaboration opportunities with insurance companies. The analysis includes patterns in bike usage, accident data correlation with NYPD traffic data, and risk assessment models.

## Project Structure
```
citibike-analysis/
├── data/              # Data directory
│   ├── raw/          # Original, immutable data
│   └── processed/    # Cleaned and processed data
├── notebooks/        # Jupyter notebooks
│   └── exploratory/  # Exploratory data analysis
├── src/             # Source code
│   ├── data/        # Data processing scripts
│   ├── analysis/    # Analysis modules
│   └── visualization/# Visualization code
├── reports/         # Generated analysis reports
│   └── figures/     # Generated graphics
└── requirements.txt # Project dependencies
```

## Setup Instructions

1. Clone the repository
```bash
git clone https://github.com/[username]/citibike-analysis.git
cd citibike-analysis
```

2. Create and activate virtual environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies
```bash
pip install -r requirements.txt
```

4. Download data
- Download CitiBike data from: [CitiBike System Data](https://ride.citibikenyc.com/system-data)
- Place the downloaded files in the `data/raw` directory

## Data Sources
- CitiBike trip data (2023)
- NYPD traffic accident data

## Analysis Pipeline
1. Data preprocessing and cleaning
2. Exploratory data analysis
3. Risk assessment modeling
4. Insurance collaboration opportunity analysis

## Running the Analysis
1. Process raw data:
```bash
python src/data/data_processing.py
```

2. Run analysis notebooks in `notebooks/exploratory/`

## Results
Analysis results and visualizations can be found in the `reports` directory.
