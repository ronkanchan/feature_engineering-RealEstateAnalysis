# 📊 Exploratory Data Analysis (EDA) Project - Real Estate Analysis

## 🚀 Introduction

Welcome to the Real Estate Analysis EDA project!
While searching for the dream house, the buyer looks at various factors, not just at the height of the basement ceiling or the proximity to an east-west railroad. Using the dataset, find the factors that influence price negotiations while buying a house. There are 79 explanatory variables describing every aspect of residential homes in Ames, Iowa

## 🥅 Objective

- Understand working with the dataset and performing analysis
- Assess the data for key insights  
- Identify variables that influence property Sales Price  

## 📁 Data Source

The raw data resides in the `data/raw` folder. It includes customer info, product details, purchase history, and more. To understand the data attributes, check the [Data Dictionary](data/raw/data_dictionary.pdf) provided in the same folder.

## 📖 Project Guide

If you're new here, check out the comprehensive [Project Guide](feature_engineering_real_estate_analytics.pdf) to get a rundown of goals, data structure, and analysis approach.

## 📂 Folder Structure

Here's how the project is organized:

- `data/`: Raw and processed data files.
  - `raw/`: Raw data (PEP1.csv) from the Real Estate Analysis database.
- `notebooks/`: Jupyter notebook for data analysis and visualization.
  - `Feature Engineering - Real Estate Analysis.ipynb`: Notebook with combined EDA and visualizations.

## 🛠️ Installation

To reproduce the analysis:

1. Clone this repository.
2. Access the `notebooks` folder and open the notebook.
3. Launch Jupyter Notebook and run each cell.

## 📊 Findings

After the EDA, some insights emerged:

1. Out of 79 variables, only 5 variables have a linear correlation with Sale Price
2. "OverallQual", "TotalBsmtSF", "GrLivArea", "GarageCars" and "GarageArea" are significant variables influencing property Sales Prices
