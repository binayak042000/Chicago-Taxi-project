# Chicago-Taxi-project

This is a personal project which is a model to predict the total revenue earned on a particular taxi route in Chicago at a particular time.
The data set used for this project was taken from reliable sources.
From the data set , I used trip start time , miles travelled , time taken ,number of companies serving the pickup zip code, pickup zip code and dropout zip code .
Also I introduced few more features like Downtown which says whether a particular zip code is of Downtown Chicago or not because from  analysis I found most of the taxi rides were from Downtown so that can play an essential role in determining the fare.
Another feature introduced was whether a particular zip code was famous for tourists or not . Since tourists would travel a lot to these places , it can affect the fare.
I used Linear Regression , SVM , Ridge Regression ,Random Forest and Decision Tree algorithms.
Finally I chose Decision Tree to create the final model as with that I could achieve a R-square score of approximately 0.91.
Since the original code I was using is not in a well structured way which can be attributed to the fact that I had to edit and add sections multiple times to improve R2 score , I have put the essential parts of my original code and combined them in the notebook given here for readers to view.
