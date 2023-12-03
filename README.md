# CD-3A
s5724090 Collecting Data assignment 3a
## Analyzing anime; a notebook.

### Dataset 
The dataset I used is called Anime Dataset with Reviews by Marlesson on Kaggle. It contains 3 csv files: animes, profiles and reviews. I uploaded the dataset to the master branch.
Here is a list with columns per file, I do not include columns I deleted:
#### animes
* uid (the id of the anime)
* title (the title of the anime)
* synopsis (the synopsis of the anime)
* genre (the genres the anime is calssified under)
* aired (the timeframe in which it aired)
* episodes (the amount of episodes)
* members (the amount of members who have added it to their watchlist)
* popularity (popularity based on the amount of members who have added the anime to their watchlist)
* ranked (popularity according to the scores users gave it)
* score (average score given by users)
#### profiles
* profile (the profile name)
* gender (the gender, sometimes unknown, either Female, Male or non-binary)
* birthday (The date of birth sometimes unknown)
* favorites_anime (several of the users' favourite anime's)
#### reviews
* uid (the user id)
* profile (profile name)
* anime_uid (id of the anime)
* score (overall score given by user)
* scores (score for: Overall, Story, Animation and Sound) 
### Research questions
In the notebook in this repository, I posed the following questions:
* How many genres are there on My Anime List? And which genre has the most anime's?
* Is there a correlation between the amount of episodes and the popularity?
* Is there a difference between gender and voting behaviour?
### Source
The dataset is public domain and can be found [here](https://www.kaggle.com/datasets/marlesson/myanimelist-dataset-animes-profiles-reviews/data?select=profiles.csv).
