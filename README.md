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
  - Traditional approach's code is in folder code/Traditional_approach
  - To find best combinations of features: code/Find_best_features.ipynb
  - To find best models with different time filters: code/Find_best_GloVe_models.ipynb and code/Find_best_FastText_models.ipynb 
  - add_feature = None means no time features applied, add_feature = 1 means using only Cre_cre feature, add_feature = 1 means using only Cre_up feature, and add_feature = 3 means using both.
  - time_filter_days is set 60 as default.