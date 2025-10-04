# First
EDA and feature engineering of spotify songs list
## Name Dataset Analysis Project
This project performs exploratory data analysis (EDA) and feature engineering on a dataset of names and IDs using Python and Jupyter Notebook. It's designed for beginners interested in learning data analysis step-by-step.

## Repo Structure
# text
project_task/
  ├─ project_task.ipynb        # Main notebook for loading data and analysis
  ├─ contentseparatednames.csv # Dataset file with IDs and FirstNames
  ├─ requirements.txt          # Python package dependencies
  └─ README.md                 # This file
## Prerequisites
Python 3.9+ recommended.
Required Python libraries:
        pandas, numpy, matplotlib.

## Setup
Clone the repo.

## Create and activate a Python virtual environment :

# text
python -m venv .venv
.\.venv\Scripts\activate           # Windows
source .venv/bin/activate          # Linux/macOS
pip install --upgrade pip
pip install -r requirements.txt

## Launch the Notebook
Install Jupyter if not already installed:
# text
pip install jupyter
Start Jupyter Notebook:
# text
jupyter notebook
Open project_task.ipynb and run all cells sequentially.

## What the Notebook Does
Loads a CSV file containing 100 rows of IDs and FirstNames.
Inspects data: views the first few rows, checks data types, missing values, and duplicate records.

## Creates new features:

Flags names that start with a vowel.
Calculates the length of each name.
Categorizes IDs into quartiles for grouping and analysis.
Provides summary statistics like most common names, ID range, and name length distributions.
Visualizes data to show trends and insights about the dataset.

## Results Highlights
Dataset has 100 entries and 3 columns: ID (int), FirstName (string).
Found 28 unique names, with "Sophia" being the most frequent.
Name lengths range from 2 to 7 characters.
About 17% names start with a vowel.
IDs range from 11314 to 95807.

## Tips for Beginners
If a cell doesn't show output, re-run it to regenerate tables and graphs.
Comments in the notebook explain each step and code snippet for easy understanding.
To add more Python packages, update requirements.txt.

