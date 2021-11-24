# Music-genre-classification

In this project basically I have to classify songs into different genres, by applying ANN, on the dataset. for those 4 different sequential models were made and compared. 
Whole project was in python and was done in Kaggle.
WORK FLOW: - 
•	Intro of data
  Total of 10 genre (blue, rock, disco, country) were present of which 1000 songs of each were there,
  60 features of each song were present like means variance of (rms, chrome shift, spectral centroid etc.)
•	Train, dev, test- 70:20:10
•	Modes: Sequential models were created and are trained according to it. Modification was done in models.
  Model 1: 4 layer model, 70 epochs and adam optimizer was used.
  Model 2: 5 layer model, dropout (20) percentage, 100 epochs and adam optimizer was used.
  Model 3: 5 layer model, dropout (20) percentage, 700 epochs and sgd optimizer was used.
  Mode 4: 5 layer model, dropout (30) percentage, 500 epochs and rmsprop optimizer was used.

Final test set accuracy 92.44
