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
Checked for missing values.
Converted numeric values into correct format.
Calculate the derived variables(Productivity Score and Ratios).
### Exploratory Data Analysis (EDA)
Calculating summary statistics (mean, median and standard deviation).
Histograms to examine the distribution of numerical variables and identify potential skewness.
Scatter plots to visualize the relationship for each hypothesis.
Correlation matrix and heatmap to get an overall view of lineer relationships among the variables.
### Hypothesis Testing 
Pearson correlation is used for hypothesis testing. 
Significance level α = 0.05 is used.
For each hypothesis:
  - H0(Null Hypothesis): No lineer relationship exists.
  - H1(Alternative Hypothesis): A lineer relationship exists.
Hypothesis are tested by comparing p-values to the significance levels.  
## Objective
- Analyzing the relation between screen habits and emotional states(mood, focus, stress)
- Investigate whether different app categories correlate with mood and stress
- Calculate a daily productivity score to evaluate how productivity is affected by sleep, mood and screen time
- Use findings to improve productivity and daily routines
## Results
### H1:Evening Screen Time & Sleep
- Result: No correlation observed, fail to reject H0.
- There is not sufficient evidence to say that evening screen time is significantly associated with sleep duration.
### H2:Sleep & Productivity
- Result: No correlation observed, fail to reject H0.
- There is not sufficient evidence to say that sleep duration is significantly related to productivity score.
### H3: Evening Screen Ratio & Next Day Focus
- Result: No correlation observed, fail to reject H0.
- There is not sufficient evidence to say that a higher evening screen ratio is significantly associated with lower focus levels.
### H4: App categories & Stress
- Result: No correlation observed, fail to reject H0.
- There is not sufficient evidence to say that increased social media usage is significantly associated with higher stress levels.

## Machine Learning Application
In addition to the exploratory data analysis and hypothesis testing, a supervised machine learning approach was applied to the dataset. The task was formulated as a regression problem, where the objective was to predict the daily productivity score based on other features(sleep, focus, evening screen ratio,social media ratio). Multiple lineer regression was selected due to the continuous nature of the target variable and the limited size of the dataset. The model was trained using a traian-test split and evaluated using Mean Squared Error(MSE) R² score. Model coefficients were analyzed to interpret the influence of different features on productivity.
This machine learning component is intended to demonstrate the application of supervised learning methods on behavioral data rather than to build a high-accuracy predictive system.








