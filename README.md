📌 Capstone Project 1 — Car Dataset Analysis

Samsung Innovation Campus — AI Track


🎯 Project Overview

This project analyzes a large car dataset to understand the most important factors affecting car prices, such as:

Horsepower

Number of cylinders

Fuel type

Vehicle size

Model year

City & Highway MPG

The project includes:

Full data cleaning

Handling missing values & duplicates

Outlier detection & correction

Feature engineering

Data visualization

Insights & final conclusions

📂 Project Files
File	Description
Final_Project.ipynb	Full analysis notebook with visualizations
SIC_Capstone_Presentation.pdf	Project slide deck
requirements.txt	Dependencies for running the notebook
data/	(Optional) Dataset used
🧹 Data Cleaning Summary

715 duplicate rows removed

Missing values filled using:

Mode → Engine Fuel Type

Median → Engine HP

Zero → Engine Cylinders for electric cars

Dropped Market Category due to high missing rate

Applied log transformation on MSRP to manage outliers

Corrected unrealistic values in city/highway MPG

📊 Key Insights

American manufacturers like Chevrolet and Ford dominate car production counts

Bugatti has the highest average MSRP across all manufacturers

Electric cars show extremely high fuel efficiency values

Best value-for-money cars:

Many 90s luxury sedans

Chevrolet Camaro 2015

Worst value-for-money cars:

Maybach Landaulet

Acura ILX Hybrid

🛠 Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

📦 Requirements

To install all dependencies, run:

pip install -r requirements.txt


Dependencies included:

pandas

numpy

matplotlib

seaborn

🚀 How to Run

Install required libraries:

pip install -r requirements.txt


Open the notebook:

jupyter notebook


Run all cells in order.