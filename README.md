# TaDeR A New Task Dependency Recommendation for Project Management Platform

## Introduction
We propose an efficient task dependency recommendation algorithm to suggest tasks that may be dependent on a given task that the user has just created. To this aim, we propose an efficient feature engineering step and construct a deep neural network.

## Dataset
In this work, we use dataset saved at:
- https://www.dropbox.com/scl/fo/vhprytf3r5hqvilm2ukcp/h?rlkey=j5ht3ladgzhk8ecmknarayep2&dl=0

## Usage
To preproduct the result:
- Download all requirement packages.
- Main working directory must be "...\\TaDeR-A-New-Task-Dependency-Recommendation-for-Project-Management-Platform".
- Download dataset and put in main working directory
- Run notebook code/Preprocessing.ipynb to preprocess data (Optional)
- Run notebook code/Embedding/Get_GloVe_features.ipynb to save GloVe embedding data
- Run notebook code/Embedding/Get_FastText_features.ipynb to save FastText embedding data 
- Experiments:
  - Code for Training and Testing baselines is in folder code/Traditional approach
  - Code for Training and Testing to find best features is in folder code/Find best features
  - Code for Training and Testing to find best models is in folder code/Find best models   