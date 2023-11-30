# Wildfire Risk Assessment Project

## Project Overview
This project leverages Canada's open-source forest wildfire data with two primary objectives:

### Objectives
1. **Predict the Cause of Forest Fires**:
   - Many forest fires have unknown causes. We've developed a machine learning model that predicts the cause of a fire (Human or Lightning) based on historical fire data and temperature data.

2. **Predict the Probability of Fire Occurrence**:
   - Our model can also predict the likelihood of a fire occurring at a specific latitude, longitude, and day of the year. This prediction is based on a voxel approach.

## Code Structure

### Data Files
- `forest_fire.txt`: Contains raw data about forest fire incidents.

### Jupyter Notebooks
- `data_cleaning.ipynb`: Notebook detailing data cleaning and pre-processing steps.

### Directories and Models
- `Prong1_Predicting_Unknown_Fires`: 
   - Contains models and scripts for predicting the causes of fires with unknown origins.

- `Prong2_Predicting_Fire_Probability`:
   - Houses models and scripts for calculating the probability of fire occurrences at specific locations and times.
