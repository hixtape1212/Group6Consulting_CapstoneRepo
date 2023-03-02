# Group 6 Consulting 
## Computing Vision Movie Studio Analysis 
![logo](logo.png)

* [***Project Overview:***](#project-overview) The overall project goal and approach.
* [***Navigation Instructions:***](#navigating-the-repo) Guidance for how to navigate the repo.
* [***Data Science Steps:***](#data-science-steps) Summary of the steps our team took to arrive at our recommendation.


# Relevant Files

* [***Jupyter Notebook:***](Group6-MovieAnalysis.ipynb) Here's the link to our teams Jupyter Notebook. This notebook will walk through our analysis.
* [***Presentation:***]() Here's the link to our teams presentation. It includes our recommendations and analysis findings.


# Project Overview

Our team was tasked with helping Computing Vision startup their own movie studio. The firm hasn’t had a lot of experience in the movie industry, and wanted our firm to run the analytics, and recommend what types of films to create as well as give Computing Vision a good idea of what to expect when opening their new studio. 

# Navigating the Repo
In this repo you will find the following: 
-	This ReadMe.md file
-	Jupyter Notebook – Contains all relevant code used for our data analysis.
-	PowerPoint.pptx – This is the presentation of our analysis and findings.

What is not contained in this repo:
-	Data File – Our team used a collection of different sources, some to big to be put on this repository. The 2 files our team used were the IMDB SQL database as well as The Numbers csv. With that being said, the data files that we used were in path 'data/*'.


# Data Science Steps
Below is a list of steps that our team took as well as the corresponding description. Since our task was to discover what types of films to create as well as give the firm an idea of what to expect, we based our search around a central metric (Return-on-Investment) to help the firm realize as much return as possible. This included analysis on ROI by genre, rating, and overall production budgets effects on outcome.

### Data Gathering and Cleaning
To start our team conducted EDA on all the source files to identify those which seemed to be the best for our approach to analysis. We were especially looking for files that contained movie names, genres, revenue, and costs. We settled on two of the datasets:
-	IMDB SQLite database (data/im.db)
-	The Numbers Movie Budgets dataset (data/tn.movie_budgets.csv)

Combined they both contained the necessary information that we needed. The Numbers included gross revenue worldwide, domestic, and a product budget which our team considered cost. IMDB contained information on genre as well as additional attributes if we needed to get more granular. Altogether, the two datasets were combined on movie titles. 

Domestic gross, worldwide gross, and production budget were cleaned to be integers, and a column for ROI calculated as (Worldwide Gross – Production Budget) / Production Budget, was added to the dataset. Duplicate movie titles were dropped, and we now had a workable data set to run analysis from. 

### Genre Analysis and Hypothesis Test


### Diminishing Returns Based off Budget


### RunTime Confidence Intervals
