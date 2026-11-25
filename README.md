# AI Programming Foundations Project

## Project Description

This project explores the 2019 New York City Airbnb dataset using Python and Jupyter Notebook. It loads and cleans listing data, calculates exploratory statistics, examines patterns by borough, and presents the results through visualizations and a written interpretation.

## What I Built

- Reusable data-cleaning functions
- Summary statistics, grouped analysis, and correlation checks
- Three Matplotlib and Seaborn visualizations
- A written summary of insights, assumptions, and limitations

## Dataset

The project uses the [New York City Airbnb Open Data (AB_NYC_2019)](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data) dataset. The included file is `AB_NYC_2019.csv`.

## How to Run the Project

1. Create and activate a Python virtual environment:

   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```

2. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Open `data_workflow.ipynb` in VS Code or start Jupyter:

   ```bash
   jupyter notebook data_workflow.ipynb
   ```

4. Run all cells from top to bottom. The notebook reads `AB_NYC_2019.csv` from the project root, performs the cleaning and analysis, and displays the visualizations.
