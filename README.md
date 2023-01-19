# IMDB-Rating-Analysis

Data Set
This is originally the dataset for the week 4 project of the course Linear Regression and Modeling by Duke University on Coursera.

The data set is comprised of 651 randomly sampled movies produced and released before 2016.

Some of these variables are only there for informational purposes and do not make any sense to include in a statistical analysis. It is up to you to decide which variables are meaningful and which should be omitted. For example information in the actor1 through actor5 variables was used to determine whether the movie casts an actor or actress who won a best actor or actress Oscar.

You might also choose to omit certain observations or restructure some of the variables to make them suitable for answering your research questions. For example, certain variables should be converted to be categorical.

When you are fitting a model you should also be careful about collinearity, as some of these variables may be dependent on each other.

title: Title of movie
title_type: Type of movie (Documentary, Feature Film, TV Movie)
genre: Genre of movie (Action & Adventure, Comedy, Documentary, Drama, Horror, Mystery & Suspense, Other)
runtime: Runtime of movie (in minutes)
mpaa_rating: MPAA rating of the movie (G, PG, PG-13, R, Unrated)
studio: Studio that produced the movie
thtr_rel_year: Year the movie is released in theaters
thtr_rel_month: Month the movie is released in theaters
thtr_rel_day: Day of the month the movie is released in theaters
dvd_rel_year: Year the movie is released on DVD
dvd_rel_month: Month the movie is released on DVD
dvd_rel_day: Day of the month the movie is released on DVD
imdb_rating: Rating on IMDB
imdb_num_votes: Number of votes on IMDB
critics_rating: Categorical variable for critics rating on Rotten Tomatoes (Certified Fresh, Fresh, Rotten)
critics_score: Critics score on Rotten Tomatoes
audience_rating: Categorical variable for audience rating on Rotten Tomatoes (Spilled, Upright)
audience_score: Audience score on Rotten Tomatoes
best_pic_nom: Whether or not the movie was nominated for a best picture Oscar (no, yes)
best_pic_win: Whether or not the movie won a best picture Oscar (no, yes)
best_actor_win: Whether or not one of the main actors in the movie ever won an Oscar (no, yes) – note that this is not necessarily whether the actor won an Oscar for their role in the given movie
best_actress_win: Whether or not one of the main actresses in the movie ever won an Oscar (no, yes) - note that this is not necessarily whether the actresses won an Oscar for their role in the given movie
best_dir_win: Whether or not the director of the movie ever won an Oscar (no, yes) – note that this is not necessarily whether the director won an Oscar for the given movie
top200_box: Whether or not the movie is in the Top 200 Box Office list on BoxOfficeMojo (no, yes)
director: Director of the movie
actor1: First main actor/actress in the abridged cast of the movie
actor2: Second main actor/actress in the abridged cast of the movie
actor3: Third main actor/actress in the abridged cast of the movie
actor4: Fourth main actor/actress in the abridged cast of the movie
actor5: Fifth main actor/actress in the abridged cast of the movie
imdb_url: Link to IMDB page for the movie
rt_url: Link to Rotten Tomatoes page for the movie

Research Question:
Q1) Oscar win actor/actress or director influence the overall performance or rating of the movie or not? OR
Is an Oscar winning actor or actress in the cast associated with a better rating (in the context of multiple
regression)?

Q2) Are Critics and Audience ratings close to each other or not. if not, are the critics ratings biased? OR
Is critics’ rating associated with audience’s rating, in the context of regression model with other potential
predictors.

Q3) Create additional variable ‘Oscar’ with a class “yes or no” to identify whether an movie has won atleast
one Oscar award and create a model with other variable. Check if there is any significant difference after
adding ‘Oscar’ in the model with other variable or not?

Q4) Create additional variable ‘movie_score’ which is a combination of imdb_rating & audience_score to
check if they add more weightage to the response variable ‘imdb_rating’?

Q5) Insights about movies characteristics with reference to title_type, mpaa_rating or genre.

Q6) Predicting imdb_rating. Show sample test case.
