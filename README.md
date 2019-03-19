# Top-10-song-reccomendation-using-collaborative-filtering-and-KNN
Top 10 song recommendation to a particular user using collaborative filtering and KNN. 
Uses python pandas,sklearn
The Dataset consists of a user_id,listen_count,song_id,title,artist and song
A user-song collaborative filter table is made from this data (user_id vs song_id with each entry signifying the listen_count)
Fit the model using K-NN
Nearest neighbor for each users are calculated and all the songs listened to by these neighbors are found
Overall listen count of each song by neighbors is found
Top 10 songs most listened to songs are recommended
