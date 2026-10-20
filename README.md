# IBM Applied Data Science Capstone

Predicting SpaceX Falcon 9 first-stage landing success using data collection, web scraping, data wrangling, exploratory data analysis, SQL, interactive visualization, and machine learning.

## Project Overview

This project follows the practical workflow of the IBM Applied Data Science Capstone. It investigates SpaceX Falcon 9 launches and prepares launch-related data for analysis and predictive modeling.

The project covers:
- Collecting launch data from the SpaceX API.
- Scraping historical launch information from Wikipedia.
- Cleaning and preparing datasets for analysis.
- Exploring launch patterns through visualizations and SQL queries.
- Visualizing launch-site locations and geographical relationships using Folium.
- Building and evaluating machine-learning classification models to predict first-stage landing outcomes.

## Repository Structure

```text
applied-data-science-capstone/
├── data/
│   ├── dataset_part_1.csv
│   ├── dataset_part_2.csv
│   ├── dataset_part_3.csv
│   ├── my_data1.db
│   └── spacex_web_scraped.csv
├── notebooks/
│   ├── jupyter-labs-spacex-data-collection-api.ipynb
│   ├── jupyter-labs-webscraping.ipynb
│   ├── labs-jupyter-spacex-Data wrangling.ipynb
│   ├── jupyter-labs-eda-sql-coursera_sqllite.ipynb
│   ├── edadataviz.ipynb
│   ├── lab_jupyter_launch_site_location.ipynb
│   └── SpaceX_Machine Learning Prediction_Part_5.ipynb
├── .gitignore
├── .python-version
├── README.md
└── requirements.txt
```

## Practical Labs

| Lab | Purpose |
|---|---|
| SpaceX API Data Collection | Retrieve launch data from the SpaceX API. |
| Web Scraping | Extract historical launch information from Wikipedia. |
| Data Wrangling | Clean, transform, and prepare the data. |
| Exploratory Data Analysis with SQL | Query and investigate launch records using SQLite. |
| Data Visualization | Explore relationships and patterns using Python visualizations. |
| Launch Site Location Analysis | Map launch sites and examine their geographical context with Folium. |
| Machine Learning Prediction | Train and evaluate classification models for landing-success prediction. |

## Technology Stack

- **Language:** Python 3.11
- **Data analysis:** pandas, NumPy
- **Data collection:** requests, web scraping with BeautifulSoup
- **Database:** SQLite
- **Visualization:** Matplotlib, Seaborn, Plotly, Folium
- **Machine learning:** scikit-learn
- **Development environment:** Jupyter notebooks and Visual Studio Code
- **Environment and package management:** uv

## Setup

### Prerequisites

- Python 3.11
- [uv](https://docs.astral.sh/uv/)
- Git
- Visual Studio Code with the Jupyter extension, or another Jupyter-compatible environment

### 1. Clone the repository

```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
cd applied-data-science-capstone
```

Replace the placeholder with the URL of your GitHub repository after publishing it.

### 2. Create the environment and install dependencies

```bash
uv python install 3.11
uv venv --python 3.11
uv pip install -r requirements.txt
uv pip install ipykernel
```

### 3. Open the notebooks

Open the repository in Visual Studio Code and select the Python interpreter from the project's `.venv` directory as the Jupyter kernel.

Start with the API data collection notebook and proceed through the labs in the order listed above.

## Data and Reproducibility

The `data/` directory contains the CSV datasets and SQLite database used by the project. The notebooks document the analysis workflow and contain the corresponding code and saved outputs where available.

Some data-collection steps depend on external services or web pages, whose availability and content can change. Re-running a notebook may therefore produce different results from its saved outputs.

## Project Objective

The central objective is to investigate which launch-related factors are associated with successful Falcon 9 first-stage landings and use historical data to build classification models for predicting landing outcomes.

Model performance should be assessed using the evaluation metrics and visualizations produced in the machine-learning notebook.

## Acknowledgements

This project was completed as part of the IBM Data Science Professional Certificate, specifically the Applied Data Science Capstone on Coursera.
