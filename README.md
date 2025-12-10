
# SKY-LEVEL SATISFACTION
ANALYZING KEY DRIVERS OF 
AIRLINE PASSENGER SATISFACTION


This project examines key drivers of airline passenger satisfaction using 103,904 survey responses that capture demographics, service ratings, and operational performance. After data cleaning, feature engineering, and exploration, the analysis compares satisfaction across customer types, cabin classes, age groups, and delay categories. Findings show that service experience—especially online boarding, in‑flight entertainment, seat comfort, and travel class—is the strongest positive influence on satisfaction. In contrast, longer departure and arrival delays substantially increase dissatisfaction, particularly beyond 30 minutes. Overall, the results suggest that improving digital touchpoints, enhancing onboard comfort, and minimizing delays are more critical for boosting satisfaction than passenger demographics.

## Instruction

**Requirements:**

- Python 3.9+
- Libraries: pandas, numpy, seaborn, matplotlib (pyplot)
Example installation:

*pip install pandas numpy seaborn matplotlib*

**Steps:**

1. Download the project ZIP file and extract all contents to a folder on your local drive

2. Ensure the file data.csv is saved in the same folder as the notebook.

3. Open the main notebook Group8_Final.ipynb in Jupyter Notebook, JupyterLab, or VS Code with Jupyter support.

4. Run the first code cell that imports the libraries:

import pandas as pd

import numpy as np

import seaborn as sns

import matplotlib.pyplot as plt

5. Run the cell that loads the dataset:

df = pd.read_csv('data.csv')

6. Execute the remaining cells in order to reproduce all EDA steps and visualizations (box plots, bar charts, pie charts, histograms, and heatmaps)
## Dataset Description
This project uses the publicly available Airline Passenger Satisfaction dataset from Kaggle (Teejmahal, 2020). The dataset contains 103,904 survey records with 25 variables describing passenger characteristics and ratings across multiple service aspects.
## Data Preparation
1. Missing Values in Arrival Delay is filled with the median
2. Unnamed Column removed
3. Neutral or Dissatisfied is treated as Dissatisfied for this analysis


## Feature Engineering
Description of derived variables and groupings:

1. Age bands (youth, young adults, adults, mature adults, seniors)

2. Distance categories (short, medium, long, very long)
3. Delay categories (no delay, short, medium, long, very long)
4. Ordered cabin classes (Economy, Eco Plus, Business).




## Exploratory Data Analysis and Visualizations

- Outlier Check (Box plots)
- Data distribution (histograms)
- Passenger characteristics (bar charts, pie charts)
- Relationships and correlations (heatmaps)
- Feature Importance (bar charts)


## Repository Structure

- **Data:** data.csv
- **Notebook:** Group8_Final.ipynb
- **Report:** Group 8 - Sky-Level Satisfaction.pdf
- **README:** README.md
- **Presentation Slides:** GROUP 8 MBAI 5300G.pptx

**Data Analysis:** 

Pandas,
Numpy,
Seaborn,
Pyplot

## Authors

- John de Guzman
> Exploratory Data Analysis (distribution and correlation), debugging, documentation, proofreading

- Elaine Bhel Lagman
> Exploratory Data Analysis (distribution and correlation), debugging, documentation, proofreading

- Renee Rae Santos
> Exploratory Data Analysis (data cleanup, outlier check and visualization), debugging, documentation, proofreading

- Hazal Turken
> Exploratory Data Analysis (feature importance and correlation), debugging, documentation, proofreading

