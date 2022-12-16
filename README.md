# Spotify-Data-Analysis

The goal of this project is to explore a dataset containing [Spotify's Weekly Top Song's](https://www.kaggle.com/datasets/yelexa/spotify200) from 2021/02/04 ~ 2022/07/14. 

Our main focus is to find the best possible model(s) to predict if a song will be classified as a top song or not.
We defined a top song as a song that has more than 325,000 streams, the top 25% of streamed songs.

The dataset contains audio features from [Spotify's API](https://developer.spotify.com/documentation/web-api/reference/#/operations/get-several-audio-features) that were used to test on the following models:

**Supervised Learning**
- Decision Tree Classifier
- KNN
- Gaussian Naive Bayes
- Random Forest Classifier
- Gradient Boosting

**Unsupervised Learning**
- KMeans Clustering

Preprocessing and all statistical methods used can be found [here](/SpotifyAnalysis.ipynb)
