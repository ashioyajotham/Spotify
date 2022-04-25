# Spotify

**********My journey to build a music recommender system*************************


Step 1: [Link to notebook](https://github.com/ashioyajotham/Spotify/blob/main/Spotify.ipynb)

# Spotify Analytics Dashboard

AIM
* To create an analytics dashboard to visualize my Spotify usage

Requirements
  * Spotify Developer Account
  * Tableau
  * Jupyter Notebooks

* I Gathered my Spotify data by logging into `Spotify` > `Privacy` then click download data (Usually you fill a request and it takes up to 30 days)
* I cleaned the data by removing the duplicates and filling missing values
* Create a Spotify developer account or if you have one already, create an application and obtain the `key` and `access` endpoints. We will need them for the `BASE_URL`
* Create a Tableau dashboard with the finished dataa and visualize how you want.

Here's my Tableau dashboard: https://public.tableau.com/app/profile/ashioyajotham/viz/spotify-viz/Dashboard1


*************** It's a work in progress. I plan to automate the dashboard to release a monthly report and also implement a recommender system *******************

CC: Anne Bode 
   https://towardsdatascience.com/spotify-api-audio-features-5d8bcbd780b2



Step 2: [Link to notebook](https://github.com/ashioyajotham/Spotify/blob/main/spotify-data-mining.ipynb)

# Extracting Features from Song Data

* In essence, we will mine "data" from Spotify API
* Spotify APi is very powerful that it is able to extract features such as `"danceability"` from songs and even score them. We can also derive a recommendation engine   from it

CC: Cameron Watts https://towardsdatascience.com/extracting-song-data-from-the-spotify-api-using-python-b1e79388d50

* You can also employ the Spotipy library but for this case we will build it "manually"




