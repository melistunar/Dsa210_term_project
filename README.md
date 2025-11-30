# Dsa210_term_project
## Overview 
This project aims to explore how daily digital habits affect well-being and productivity. Screen time , especially in the evening, may affect sleep quality and focus. Also app categories (such as social media or creativity) may influence emotional and cognitive states. By analyzing my own daily data,  this project aims to understand the relation and change digital habits accordingly to be more healthy. 
 
## Motivation
Screen exposure, especially in the late hours may lead to poor sleep quality due to blue-light exposure. Emotional aspects such as mood and stress depends on the daily screen usage. Furthermore, screen time spent on diffeent categories is also important. Understanding the relationship with actual data to improve daily routines and increase personal productivity.

## Data Collection Plan
Data is collected daily for 30 days.
### Daily Collected Data
- Total screen time (in hours)
- Evening screen time
- App category usage (social media, entertainment, productivity)
- Sleep duration (in hours)
- Mood( rated daily from 1 to 5)
- Stress ( rated daily from 1 to 5)
- Focus (rated daily from 1 to 5)
### Derived Data 
- Productivity score, which will be calculated using focus, sleep duration and mood.
  Productivity = focus level * (0.5) + sleep * (0.3) + mood * (0.2)
- Evening screen ratio
- Social media ratio

## Hypothesis 
This project uses 4 hypothesis:
1. H1: Evening Screen Time & Sleep: Higher evening screen time is associated with the shorter sleep duration.
2. H2: Sleep & Productivity: Higher sleep hour leads to higher productivity score.
3. H3: Evening Screen Ratio & Next Day Focus: higher evening screen ratio leads to lower next day focus.
4. H4: App categories & Stress: Higher social media usage is associated with higher stress levels.

## Methodology
### Data Collection Plan 
Daily manual input collection.
### Data Cleaning
Verify missing values and detect outlier values
Calculate the derived variables
### Exploratory Data Analysis (EDA)
Calculating summary statistics (mean, median and standard deviation)
Data visualization (Histograms, Boxplots, Scatterplots)
### Hypothesis Testing 
Correlation tests(Pearson-Spearman correlations and p-Values for significance )
  
## Objective
- Analyzing the relation between screen habits and emotional states(mood, focus, stress)
- Investigate whether different app categories correlate with mood and stress
- Calculate a daily productivity score to evaluate how productivity is affected by sleep, mood and screen time
- Use findings to improve productivity and daily routines
