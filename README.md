EMGT 311 Final Project

This repository contains the code and analysis for my EMGT 311 Final Project. The project involves loading, cleaning, and analyzing experimental data from CSV files. The notebook demonstrates data preprocessing, feature engineering, and statistical modeling to evaluate patterns and outcomes related to the dataset.

Repository Contents

EMGT_311_Final_Project_code.ipynb
Jupyter Notebook containing all preprocessing, exploratory data analysis, and modeling steps.

/data/ (optional)
Placeholder folder for input CSV datasets. These files are not included in the repository but should be placed here when running the notebook.

Requirements

To run the notebook, you will need Python 3.9+ and the following packages:

pip install pandas numpy matplotlib seaborn scikit-learn


Additional packages (such as scipy, statsmodels, or notebook) may be required depending on your environment.

Usage

Clone this repository:

git clone https://github.com/<your-username>/EMGT_311_Final_Project.git
cd EMGT_311_Final_Project


Place the input CSV files in the data/ directory.

Open the notebook in Jupyter:

jupyter notebook EMGT_311_Final_Project_code.ipynb


Run the cells step by step to reproduce the analysis.

Project Overview

Data Import & Cleaning: The dataset requires skipping metadata rows (skiprows=5) during CSV loading.

Exploratory Data Analysis (EDA): Statistical summaries and visualization techniques are applied to understand distributions and correlations.

Feature Engineering: Rolling window features and transformations are generated for modeling.

Modeling & Evaluation: Machine learning models are trained and compared to assess predictive performance.

Results

The analysis highlights key trends and validates the use of feature extraction techniques in modeling outcomes. Final results and visualizations are included directly in the notebook.
