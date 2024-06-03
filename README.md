# NBA Shooting Performance Analysis

## Summary
This repository contains analysis on shooting motions of NBA players, specifically answering the question on which habits and metrics improve the accuracy of the shot. The analysis has been conducted via Jupyter Notebook, which explores many interesing metrics from the dataset to not only showcase intricate details involved in Basketball, but also attempt to research good, bad and unaffecting habits to improve our shots! With these kinds of projects & datasets with abundant mathematical informaion, there are limitless research that could be done. As a passionate basketball player myself, I believe that further analysis on this question through Machine Learning & other technologies can help us improve the game and discover new secrets.

## Dataset
The dataset used in this project is called "NBA Player Shooting motions" (https://www.kaggle.com/datasets/matthewjohnson14/nba-player-shooting-motions), which was acquired through the Kaggle API. The dataset contains many files based on different factors like missed, made, contested shots and has detailed columns based on details of most NBA player's shots. 

## Table of Contents

### Clean & Wrangle File
This file essentially handles everything from retrieving the dataset to downloading it into a cleaned-csv file. 

1. Introduction
   - The main question
   - Motivation
   - Introduction to the dataset
2.  Importing Dataset
     - Using !kaggle, copy, mkdir commands to retrieve data from Kaggle
     - Extracting the zipfile
3. Data Wrangling
    - Reading the data
    - Merging tables & categorizing columns
    - Creating new columns: arc angle, ball-shifting
4. Data Cleaning
    - Handling NA values
    - Dropping unused columns
    - Handling duplicate rows

### SQL Analysis
Integrated SQL into Jupyter Notebook to carry out better analysis. The biggest advantage is that the syntax is convenient and quicker performance can be done via SQL whereas Python handled math-heavy jobs.
1. Thorough analysis via GROUP BY, JOIN, window functions (LEAD,LAG,RANK,DENSE_RANK), CTEs
2. Conclusion
   - What physical attributes make a better scorer?
   - Summary of all analysis done
3. References
     - Related resources & posts
