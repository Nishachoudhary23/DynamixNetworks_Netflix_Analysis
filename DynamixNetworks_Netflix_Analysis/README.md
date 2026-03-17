# Netflix Movies & TV Shows Analysis using Python, EDA, Visualization, and Machine Learning

# Overview

This project performs Exploratory Data Analysis (EDA) on the Netflix Movies & TV Shows dataset to understand patterns in Netflix’s content library.

The analysis explores different aspects of the dataset such as:

distribution of movies and TV shows

release trends over the years

top content-producing countries

popular genres

rating distribution

In addition to EDA, machine learning models are applied to classify whether a title is a Movie or a TV Show based on selected features.

# Dataset

The dataset contains information about movies and TV shows available on Netflix.

# Main Columns

show_id – Unique identifier for each title

type – Movie or TV Show

title – Name of the content

director – Director of the title

cast – Main actors/actresses

country – Country of production

date_added – Date when content was added to Netflix

release_year – Year the content was released

rating – Age rating (PG, TV-MA, etc.)

duration – Duration of movie or number of seasons

listed_in – Genre categories

description – Short summary of the content

# Dataset Source

The dataset used in this project is available on Kaggle:

Netflix Movies & TV Shows Dataset
https://www.kaggle.com/datasets/shivamb/netflix-shows

# Project Workflow

The analysis was performed in the following steps.

1 Data Cleaning

Handled missing values in columns such as director, cast, country, and rating

Removed duplicate records

Converted date_added to datetime format

Extracted additional features such as year_added and month_added

2 Feature Engineering

Additional variables were created to improve analysis:

year_added – year when the content was added to Netflix

month_added – month of content addition

duration_num – numeric duration extracted from the duration column

3 Exploratory Data Analysis

Several visualizations were created to explore patterns in the dataset.

Movies vs TV Shows

Analysis of the distribution of movies and TV shows available on Netflix.

Content Release Trend

Visualization of how Netflix content has changed over time.

Top Content-Producing Countries

Identified countries that contribute the most content to Netflix.

Genre Distribution

Explored the most common genres present on the platform.

Rating Distribution

Analyzed audience ratings to understand the types of content available.

# Machine Learning Analysis

As an advanced analysis step, machine learning models were applied to classify content type.

-- Models Used

Logistic Regression

Random Forest Classifier

--Features Used

release_year

duration_num

country

year_added

Categorical variables were encoded using Label Encoding and One-Hot Encoding.

The dataset was split into training and testing sets for model evaluation.

# Model Evaluation

The models were evaluated using:

Accuracy Score

Confusion Matrix

Classification Report

Feature importance was also visualized to identify which variables contributed most to the predictions.

# Key Insights

Netflix contains significantly more Movies than TV Shows.

United States and India contribute a large portion of Netflix content.

Drama and International genres are among the most common.

Netflix content increased significantly after 2015.

Machine learning models were able to classify content type based on selected features.

# Tools and Technologies

Python
Pandas
NumPy
Seaborn
Matplotlib
Scikit-learn

# Conclusion

This project demonstrates practical skills in data cleaning, exploratory data analysis, visualization, and machine learning using a real-world dataset. The analysis provides insights into Netflix's content distribution and trends over time.