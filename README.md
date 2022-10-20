# Introduction
Anime recommendator using simple data analysis ideas. For its creation, the information provided by user ratings has been used. A clustering-based approach has been used.

![alt text](https://gcdn.lanetaneta.com/wp-content/uploads/2022/05/Shonen-Jump-Chart-revela-cuando-su-mayor-manga-obtuvo-animes.jpg)



# Data
The data used were obtained from the kaggle website. They are located in the data folder in this repository.

# Content 

## anime.csv

- anime_id : myanimelist.net's unique id identifying an anime.
- name : full name of anime.
- genre : comma separated list of genres for this anime.
- type : movie, TV, OVA, etc.
- episodes : how many episodes in this show. (1 if movie).
- rating : average rating out of 10 for this anime.
- members : number of community members that are in this anime's "group".

## rating.csv

- user_id : non identifiable randomly generated user id.
- anime_id : the anime that this user has rated.
- rating : rating out of 10 this user has assigned (-1 if the user watched it but didn't assign a rating).
