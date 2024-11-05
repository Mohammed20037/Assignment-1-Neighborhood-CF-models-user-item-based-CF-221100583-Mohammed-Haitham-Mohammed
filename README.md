# Assignment-1-Neighborhood-CF-models-user-item-based-CF-221100583-Mohammed-Haitham-Mohammed


# AIE425 Intelligent Recommender Systems
## Assignment #1: Neighborhood Collaborative Filtering (CF) Models

This repository hosts the implementation and analysis of Neighborhood Collaborative Filtering (CF) models, both user-based and item-based, as part of the AIE425 Intelligent Recommender Systems course. The focus of this project is to investigate the effectiveness of two similarity measures—Cosine Similarity and Pearson Correlation—in generating accurate recommendations. The models leverage user ratings from the TMDb API to predict preferences and suggest relevant items to users.

## Project Structure

- data/: Directory containing scripts to fetch and store data from the TMDb API.
- src/: Python scripts for processing data, computing similarities, and making predictions.
- notebooks/: Jupyter notebooks for exploratory data analysis and results visualization.
- docs/: Documentation files explaining the methodology and findings.
- tests/: Test cases for automated testing of the application functions.

## Features

- *Data Collection*: Script to automatically fetch data using the TMDb API, focusing on high-quality movie data.
- *Data Processing*: Utilities to clean and preprocess the fetched data into a suitable format for analysis.
- *Similarity Computation*: Implementation of both Cosine Similarity and Pearson Correlation to measure similarities.
- *Rating Prediction*: Algorithms to predict user ratings based on similar users/items.
- *Recommendation Generation*: System to generate and provide Top-N recommendations to users.
- *Performance Evaluation*: Analysis comparing the effectiveness of the implemented similarity measures.
