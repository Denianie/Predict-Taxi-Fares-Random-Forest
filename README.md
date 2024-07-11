# Predict Taxi Fares with Random Forest

This repository contains the code and data for a project that predicts taxi fares in New York City using Random Forests. The analysis is performed using the R programming language.

## Project Structure

- `datasets/`: This directory contains the datasets used for analysis.
  - `fares.csv`
  - `manhattan.rds`
  - `maps.RData`
  - `nycamp.rds`
  - `taxi.csv`
  - `test.csv`
  - `trips.csv`
- `random_forests.ipynb`: The main notebook file where the analysis is performed.

## Objective

The objective of this project is to analyze a random sample of 49,999 New York taxi journeys made in 2013, using regression trees and random forests to build a model that can predict the locations and times when the biggest fares can be earned.

## Key Findings

- **Data manipulation and analysis**: Used various R packages such as `tidyverse` for data manipulation and cleaning.
- **Model fitting**: Applied Random Forests to predict taxi fares based on several features such as latitude, longitude, hour, weekday, and month.

## Installation

To run the notebook, you will need to have R installed along with the following packages:
- `tidyverse`
- `randomForest`

You can install these packages using the following commands in R:

```R
install.packages("tidyverse")
install.packages("randomForest")
