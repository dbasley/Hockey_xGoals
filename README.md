Rmd file

Uses the hockeyR library to pull pbp data from 2016-2023

Preprocess data to only include even strength 5v5 shot attempts.

First fits logistic regression to shot attempts.

Next fits multi-level model with player and goalie effects.

Sums all of individual player xGoals across shots

Sums all of individual goalies xSaves across shots
