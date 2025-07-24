## Introduction 
The Film Junky Union, is a community for classic film enthusiast, is creating a method to filter and classify movie critiques in order to identify unfavorable reviews. 

Purpose: 
1. Train a model to identify and classify reviews.
2. F1 score of at least 0.85.

## Data 
Data description: 

tconst: unique id for each movie in the IMDb database 

title_type: type or category of the title 

primary_title: primary title of the movie 

original_title: original title of the movie 

start_year: year of release 

end_year: year when the movie ended 

runtime_minutes:duration of the movie in minutes 

is_adult: binary indicator indicating wheather movie is classified as adult

genres: genres associated with the movie 

average_rating:average rating given to the movie 

votes:number of votes the movie received 

rating:ratings provided in the review 

sp:Sentiment polar (positive,neutral) 

ds_part: part of the dataset (train/test) 

idx:identifcation for the data point 

Feature:
review: moview review in text 

Target
pos: binary indicator indicating sentiment polarity of the review

## Libraries Used 
Math, Numpy, Pandas, RE, OS,SYS, Matplotlib, Seaborn, Scikit-Learn, NLTK, SpaCy, TQDM

## Table of Contents 
1. Introduction
2. Data Exploration
3. Data Preprocessing
4. EDA
5. Model Training
6. Reviews
7. Model Testing
8. Conclusion 
