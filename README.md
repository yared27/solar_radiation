

# Solar Radiation Data Analysis

## Overview

This repository contains data analysis and visualizations for solar radiation datasets. The goal is to analyze and compare solar radiation data from different locations to help make informed decisions about investing in solar technology. The datasets include solar radiation measurements, temperature, wind speed, and other relevant environmental variables.

## Contents

- `notebooks/`: Jupyter notebooks for exploratory data analysis (EDA) and visualization.
  - `benin.ipynb`: EDA and analysis for Benin dataset.
  - `sierraleone.ipynb`: EDA and analysis for Sierra Leone dataset.
  - `togo_dapaong.ipynb`: EDA and analysis for Togo dataset.
  
- `scripts/`: Python scripts for data processing and visualization.

- `requirements.txt`: Python dependencies for the project.

- `.gitignore`: Git ignore file to exclude files from version control.

- `.streamlit/`: Streamlit configuration for dashboard development.

- `app/`: Contains the Streamlit dashboard application files.
  - `main.py`: Main script for the Streamlit application.
  - `utils.py`: Utility functions for data processing and visualization.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/solar_radiation.git
   cd solar_radiation
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Run Jupyter Notebooks**:
   - Navigate to the `notebooks/` directory.
   - Open the desired notebook using Jupyter Notebook:
     ```bash
     jupyter notebook
     ```

2. **Run Streamlit Dashboard**:
   - Navigate to the `app/` directory.
   - Run the Streamlit application:
     ```bash
     streamlit run main.py
     ```

## Data Analysis

- **Exploratory Data Analysis (EDA)**:
  - Summary statistics of solar radiation and related variables.
  - Data quality checks for missing values, outliers, and incorrect entries.
  - Time series analysis to observe patterns and trends over time.
  - Correlation analysis between solar radiation components and temperature measures.
  - Wind and temperature analysis for understanding their impact on solar radiation.
  - Histograms and Z-score analysis for data distribution and anomaly detection.
  - Bubble charts to explore complex relationships between variables.

- **Data Cleaning**:
  - Handling missing values and anomalies in the dataset.





