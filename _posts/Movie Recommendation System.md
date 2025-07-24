---
title: "Movie Recommendation System"
layout: single
collection: projects
permalink: /projects/movie-recommendation-system/
---

## Problem

Build a content-based and collaborative filtering recommendation system to suggest movies to users based on preferences, history, and ratings.

## Approach

- Collected and cleaned movie metadata and user ratings from MovieLens  
- Built two models:
  - **Content-Based Filtering** using TF-IDF on genres, cast, and description  
  - **Collaborative Filtering** using matrix factorization  
- Developed a simple CLI to accept user input and return movie suggestions

## Tools

- Python (Pandas, Scikit-learn, Surprise)  
- Jupyter Notebook  
- MovieLens Dataset  

## Lessons Learned

- Differences in accuracy and complexity between filtering types  
- Challenges in cold-start and sparsity problems  
- How to fine-tune similarity metrics (cosine, Pearson)
