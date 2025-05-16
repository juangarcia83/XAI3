# XAI3 - Partial Dependence Plots (PDP)

This repository contains the solution to Exercise 5 of the Explainable AI (XAI) module, focused on model-agnostic methods to interpret machine learning models.

## Objective

To apply Partial Dependence Plots (PDP) using a Random Forest model trained on the bike rental (`bike_rental.csv`) and house pricing (`kc_house_data.csv`) dataset to predict the number of bike rentals (`cnt`) and house price (`price`), and to analyze the influence of selected features.

## Contents

- `code/`: R scripts to generate the PDPs
- `report/`: Final report with plots and interpretations
- `figures/`: Generated plots

## Summary of Tasks

- **1D PDP (Task 1 and 3)**: Plots were generated to examine the individual effect of variables such as temperature, humidity, wind speed, and day index on bike rental predictions, as well as number of bedrooms, bathrooms and floors, and living area on house pricing predictions.
- **2D PDP (Task 2)**: A heatmap was created to analyze the joint effect of temperature and humidity using `geom_tile()`, including rug plots to show input density.


## Methodology

A random sample of the dataset was used to reduce computational cost. The `randomForest`, `pdp`, and `ggplot2` packages were used for modeling and visualization.

## Version Control and Backup

Git was used for version control, and GitHub serves as backup storage, as required by the assignment.
