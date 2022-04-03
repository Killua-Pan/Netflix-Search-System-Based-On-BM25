# Netflix-Search-System-Based-On-BM25
Netflix Moive/TV Show recommondation system by DM25
# Problem Statement and Approach.
Technology has changed the way people live their everyday lives. It's present in almost everything you do, from how you communicate to how you perform your day-to-day tasks. Just like it has for a lot of other industries, technology has completely changed the film/TV Show industry – from the ways they get made, to how they are edited, to the ways audiences watch them. However, sometimes by just seeing the name of the movie/TV Show we are not able to know what that movie/TV Show is talking about. In other words, we are not able to use the keywords to look up a movie/TV Show we’ve interested.

So the scope of this project will be using various information retrieval techniques, by given any keywords, finding the most relevant movie/TV Show on Netflix。

# Dataset
The data set used is Kaggle Netflix Movies and TV Shows[1]

This dataset (source: Kaggle) contains information of almost 8000 Netflix movies and shows. The column are list below:
-	Type: ‘Movie’ or ‘TV Show’
-	Title: Title of Movie or TV Show
-	Director: Directors of Movie or TV Show
-	Cast: Main actors or casts
-	Country: Country where the Movie/TV Show made
-	Date_added: The date when the Movie/TV Show released
-	Release_year: Year of the Movie/TV Show released
-	Rating: TV Rating of the movie / show
-	Duration: Total Duration - in minutes or number of seasons
-	Listed_in: TV Show/Movie genre 
-	Description：Description of the movie(Which we mainly used)
We will use the description as our documents to search the query we received and return the title of the TV Show/Movie which are related For example: the query is about: ‘I want to look at the TV Show/Movies about murdered’ the model are able to return: Hello Brother, Peppermint.


[1] Kaggle Netflix Movies and TV Shows dataset : https://www.kaggle.com/shivamb/netflix-shows![image](https://user-images.githubusercontent.com/90529914/161431842-08fe9916-f8c9-4c5c-85aa-97fcf085d6b2.png)
