## Exploratory Data Analysis (EDA) of the MtCars Dataset Using Python
Overview
This project performs Exploratory Data Analysis (EDA) on the MTCars dataset using Python data science tools. The goal of the analysis is to explore vehicle performance metrics such as horsepower, fuel efficiency, engine displacement, and weight in order to understand patterns and relationships within the dataset.

The analysis focuses on data inspection, cleaning checks, statistical exploration, and identifying potential outliers that may influence further modeling or insights.

## Dataset

The dataset used in this project is the MTCars dataset, which contains technical specifications and performance metrics for 32 automobiles.

## Key Features in the Dataset
* Column	Description
* model	Car model name
* mpg	Miles per gallon (fuel efficiency)
* cyl	Number of cylinders
* disp	Engine displacement
* hp	Horsepower
* drat	Rear axle ratio
* wt	Weight of the car
* qsec	Quarter mile time
* Engine shape
* Transmission type
* gear	Number of forward gears
* carb	Number of carburetors
## Technologies Used

* Python

* Pandas

* NumPy

* Matplotlib

* Seaborn

* Jupyter Notebook

## Analysis Performed

The project includes the following data analysis steps:

1️⃣ Data Loading

The dataset is loaded using Pandas for analysis.

import pandas as pd
df = pd.read_csv("Mtcars.csv")

2️⃣ Dataset Inspection

Basic dataset structure and information are examined.

df.head()

df.info()

This helps understand:

number of rows and columns

data types

dataset structure

3️⃣ Duplicate Data Check

The dataset is checked for duplicate entries.

df.duplicated().any()

4️⃣ Missing Value Detection

Missing values are identified to ensure data quality.

df['hp'].isnull().sum()

5️⃣ Distribution Analysis

Skewness is examined to understand how values are distributed.

df['hp'].skew()

6️⃣ Outlier Detection

Outliers are inspected to identify extreme values that may affect analysis.
## Key Objectives

* Understand the structure of the dataset

* Detect missing or duplicate data

* Analyze variable distributions

* Identify outliers in numerical features

* Prepare the dataset for future machine learning or statistical modeling

## Project Structure
project-folder/
│
├── MTCARS.ipynb
├──  README.md
└──Mtcars.csv
👤 Author
Okereke Chinedu
