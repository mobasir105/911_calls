# 911_calls


dataset  https://www.kaggle.com/datasets/mchirico/montcoalert/code



911 Calls Data Analysis
This project analyzes Emergency (911) Calls data for Montgomery County, PA, using Python and Jupyter Notebook. The dataset includes all emergency calls (Fire, Traffic, EMS) and provides insights into call distributions, frequent locations, and other trends.

Dataset
Source: Provided by montcoalert.org
Shape: 663,522 rows × 9 columns
Columns:
lat: Latitude
lng: Longitude
desc: Description of the Emergency Call
zip: Zipcode
title: Title (type of emergency)
timeStamp: Date and time of the call (YYYY-MM-DD HH:MM:SS)
twp: Township
addr: Address
e: Dummy variable (always 1)
Notebooks
The main analysis is in 911_calls.ipynb.
It includes:

Data loading and overview
Data cleaning and exploration
Visualization of top zip codes and townships by call volume
Statistical summaries
Quick Stats
Top 5 zip codes by call count: 19401, 19464, 19403, 19446, 19406
Top 5 townships: LOWER MERION, ABINGTON, NORRISTOWN, UPPER MERION, CHELTENHAM
Requirements
Python 3
pandas
numpy
matplotlib
seaborn
Jupyter Notebook
Install requirements using:

bash
pip install pandas numpy matplotlib seaborn
Usage
Clone this repository:
bash
git clone https://github.com/mobasir105/911_calls.git
cd 911_calls
Open the Jupyter Notebook:
bash
jupyter notebook 911_calls.ipynb
Run all cells to reproduce the analysis.
Acknowledgements
Data provided by montcoalert.org
