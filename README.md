# Multi-Criteria Decision Analysis (MCDA) for Model Evaluation
## Overview
### This Python script performs a Multi-Criteria Decision Analysis (MCDA) to evaluate and rank different models based on a specified criterion. The code utilizes pandas, numpy, and matplotlib libraries to handle data, perform numerical operations, and create visualizations.
## Features
### Data Input: The script takes in a sample dataset containing model names and their corresponding scores on a specific criterion ('Similarity' in this case).
### Normalization: The 'Similarity' scor
### Weighted Decision Matrix: Weights are assigned to criteria, and a weighted decision matrix is calculated based on the normalized data and assigned weights.
### Ideal and Negative-Ideal Solutions: The script identifies the ideal and negative-ideal solutions by maximizing and minimizing the weighted normalized matrix, respectively.
### Euclidean Distances: Euclidean distances from each model to the ideal and negative-ideal solutions are calculated.
### Closeness Scores: Closeness scores are determined by normalizing the distance to the negative-ideal solution relative to the sum of distances to both ideal and negative-ideal solutions.
### Ranking: Models are ranked based on their closeness scores.
### Visualization: The script generates a horizontal bar chart to visually represent the rankings of the models.
## Results
### The script prints out a table displaying the original data, closeness scores, and model rankings. Additionally, a bar chart is generated to visually represent the rankings of the models.
