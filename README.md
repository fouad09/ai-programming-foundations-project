# AI Programming Foundations Project

## Project Description

This project explores the 2019 New York City Airbnb listings dataset using Python and Jupyter Notebook. It loads the data, audits and cleans data-quality problems with reusable functions, and examines how nightly prices differ by borough and room type. Results are presented in three labeled visualizations and a written interpretation.

## What I Built

- `data_workflow.ipynb`: a top-to-bottom workflow covering ingestion, data-quality audit, cleaning, exploratory analysis, visualizations, and a written summary
- Reusable cleaning functions and an exploratory analysis function, each with a docstring
- Three Matplotlib and Seaborn visualizations with titles and labeled axes
- `module_summary.pdf`: the written report with citations
- `requirements.txt`: the pinned package versions created with `pip freeze`

## Dataset

The project uses the [New York City Airbnb Open Data (AB_NYC_2019)](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data) dataset from Kaggle. The file `AB_NYC_2019.csv` (48,895 rows and 16 columns) is included in this repository.

## How to Run the Project

These steps were tested with Python 3.11.

1. Create and activate a virtual environment from the project folder:

   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```

   On Windows, activate it with `.venv\Scripts\activate` instead.

2. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Open `data_workflow.ipynb` in VS Code (with the Python and Jupyter extensions) and select the `.venv` kernel. To use the browser instead, run `pip install notebook` and then `jupyter notebook data_workflow.ipynb`.

4. Run all cells from top to bottom. The notebook reads `AB_NYC_2019.csv` from the project folder, so open the project folder as your working directory.
