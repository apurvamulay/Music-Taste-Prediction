# Music-taste-analysis
This project is done as a part of Data Science course taken as a part of Master of Science in Computer Science.
The project attempts to answer the question - Which user has more probability of liking a song given features of that song?
The Project consist of analysis as follows:
1. For class imbalance in dataset and tuning models to understand class imbalance:<br />
  1.1 Using hold out method to split train and test set as 70% and 30 % respectively<br />
  1.2 Using cross-validation with k=3<br />
2. For balanced dataset:<br />
  2.1 Using k-fold cross-validation with k=3<br />
  
  The features considered are features of the song received from spotify:
  'acousticness', 'danceability', 'energy', 'instrumentalness', 'liveness', 'loudness', 'speechiness', 'tempo', 'valence',   ‘popularity’<br>
  <br/>
  
  Following ML Models were used:<br/>
  1. l2 regularized logistic regression<br/>
  2. Decision tree classifier
  3. Random Forest
  <br/>
  Random Forest was selected for analysis as it provided AUC of 0.91, F1 score of 0.90 and accuracy of 91%
