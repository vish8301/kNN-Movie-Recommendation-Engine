# kNN based Movie Recommendation Engine

## Overview
This project implements a simple movie recommendation engine using the k-Nearest Neighbors (kNN) algorithm. It's designed to recommend movies similar to a given movie, based on genres and IMDB ratings. This prototype serves as the backbone for a hypothetical movie recommendation website, similar to those used by Netflix or Hulu, but on a smaller scale.

**Data Source**: Utilizes a curated dataset of movies, including genres and IMDB ratings.
[IMDB Movies](https://github.com/ArinB/MSBA-CA-Data/raw/main/CA05/movies_recommendation_data.csv)


## Usage
- Load your dataset and preprocess the data if necessary.
- Initialize the kNN model with NearestNeighbors from scikit-learn.
- Fit the model with the movie dataset excluding identifiers like Movie ID and Movie Name.
- To find recommendations for a movie, create a feature vector for that movie and use the model to find the nearest neighbors.


## Setup and Installation
Ensure you have Python installed on your system. This project requires the following libraries:
- NumPy
- pandas
- scikit-learn

To install the necessary libraries:
```bash
pip install numpy pandas scikit-learn
