# Sports Predictor

The purpose of this project will be to predict the outcome of regular season NBA games, given the historical performance of a team up until that point in the season.  It makes use of the NBA games dataset which can be found [here](https://www.kaggle.com/nathanlauga/nba-games), and is a bit of a personal project that is a work-in-progress at the moment.  

Basic EDA and data cleaning is performed in `Data_Cleaning.ipynb`.  `LUT_Generator.ipynb` is used to generate look-up tables for each teams' cumulative stats at every point in each season.  This is then used in `Data_Wrangling.ipynb`, to add these stats in for each game in the `games` dataset.  They act as the features for modelling.  As mentioned above, this project is a work-in-progress, and so right now it is at the point where I have started training models, and I am getting test accuracies that are slightly better than dummy models which predict either the mode or the team with the higher winning percentage.
