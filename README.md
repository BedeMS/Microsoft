# Microsoft Movie Analysis

![image.png](attachment:image.png)

## Overview

Original content creation is an opportunity that has offered breakthrough to individuals and big companies alike. The problem is that only a few of the films being created have a return that make it worthwhile to be longstanding in the industry. 


## Business Understanding

Our client, Microsoft, has identified this and would like to understand not only how to enter this field, but also make an effective mark on it. In this report, we analyze relevant data to provide insights on what films are doing their best and why. We will translate our findings into actionable recommendations on what films we believe should be made going forward for Microsoft Executives.

- What influences a movies success?
- Do successful movies have anything in common?
- What are some ways we can measure a success of a movie?


## Data Understanding

Based on the Data we collected, we have 2 datasets.

### Dataset #1
    "bom.movie_gross.csv.gz:
    - Focused on Financial Gross both domestically and foreign Gross.
    - A simple CSV file that contained 8 variables with Titles and Gross being the focus
       
### Dataset #2
    "im.db.zip"
    - Focused on Ratings and professionals (directors) who worked on the movies
    - This file was a SQL file that had tables connected by two main keys
        - The Movie
            or
        - The Professional

## Data Analysis

### Dataset #1
    - Domestic Sum - 96557293580.0
    - Foreign Sum - 152515914276.5
    - Analyzed Data based on gross
        - First Domestically Then Foreign Results were very different
        - Total Gross where data was avialable provided top movies
        

### Dataset #2
    - Used number of votes to indicate movies popularity and that coensided with the 
        results
    - The average rating of movies returned and CONFIRMED our results from our first
        dataset. 
            - Rating do go side by side with a movies gross

## Results

### Insight #1
    - All of the movies that are based on the dataset of gross have returned the
        best gross amounts mainly revolve around "Universes".

### Insight #2
    - Movies that have performed well financially and in terms of ratings with 
        high number of votes mostly revolve around UNIVERSES.

### Insight #3
    - DIRECTORS: who we've been able to match with the top performing movies also
        have a HIGH AVERAGE RATING on AT LEAST 1 movie (1 only if that’s what’s 
        available in the dataset)


├── code
│   ├── __init__.py
│   ├── data_preparation.py
│   ├── visualizations.py
│   └── eda_notebook.ipynb
├── data
├── images
├── __init__.py
├── README.md
├── Animal_Shelter_Needs_Presentation.pdf
└── animal_shelter_needs_analysis.ipynb