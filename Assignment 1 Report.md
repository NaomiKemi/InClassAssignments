For one of two chosen tasks, I picked Task 1 which sorted out the song collection 
audio features, features that were set by spotify’s API documentation. Task one 
explored my selected collections that were filled with 2023 R&B hits. Many of 
the features I was unsure about, sorting out the songs by audio features, allow 
me to understand what they represent. I picked 3 different audio features: 
danceability, duration, and speechiness. I limited the amount of songs in the 
track to 10 as there were over 150 songs in the playlist. To examine if i will 
focus on Spotify description for danceability to see how well this code helps to 
sort out my playlist in regards to my chosen feature.

Danceability describes how suitable a track is for dancing based on 
musical elements including tempo, rhythm stability, beat strength, and 
overall regularity. A value of 0.0 is least danceable and 1.0 is most danceable. 
The song that scored the highest “CKay - love nwantiti (ah ah ah)” with a score 
0.727 and lowest of the 10 listed tracks was ‘Future-wait for u (feat drake and tems)”.
When listening to the songs individually I heard that CKay’s track had a faster tempo
than Future’s track, Future’s track was more melodic and the tempo was slower to suit
the type of beat of the song. I believe the recommendation was fully correct. The 
feature that I was quite unsure about speechiness, Futures track wait for u scored 
highest with 0.34, tracks with this score is described as tracks containing both 
music and speech, even though there was part of the songs that follow with the melody,
there a few parts when future rapped over the singing parts instead rapping along to 
beat. I believe the initial playlist flowed better than when I used the audio features
for example danceability is a subjective measure, different songs appeal to different 
audiences depending on preference.

The second task I chose was Task 2 which investigated which songs on the playlist 
that sound similar to each out. I will examine my first subset of features: 
' danceability', 'energy', 'key','loudness'. I listened to the weeknd - out of time
and Baby Keem - 16 as the cosine similarity was 0.925796. After listening to the song I
believe the songs are highly similar when comparing the listed subset features. My second
subset of features were: 'valence', 'energy', 'speechiness','liveness'.  The similarity
was much lower so I looked back at the first task to why this occurred, though the songs
have similar figures in most features but it starts to differ at speechiness, liveness 
and valence probably causing the similarity to decrease massively to 0.378456.
