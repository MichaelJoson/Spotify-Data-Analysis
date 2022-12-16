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

# Top genres

![image](https://user-images.githubusercontent.com/98543433/208058510-056df47f-5a0d-43f9-80f1-977bab3eb049.png)

# Correlation map of features:

![image](https://user-images.githubusercontent.com/98543433/208057348-210bcafd-08e3-4971-bf01-41b8e25a829d.png)

# Decision Tree:

![image](https://user-images.githubusercontent.com/98543433/208058208-376147a1-16f3-456b-8252-225b157dfcfc.png)

# Accuracies of classifiers:

![image](https://user-images.githubusercontent.com/98543433/208057763-4c64b005-e30a-4bc7-8569-52ad8b71f31d.png)

# Times of classifiers (*note: gradient boosting time too large to be shown (21.55 mins)*):

![image](https://user-images.githubusercontent.com/98543433/208057838-e7ee775f-225e-4eea-b9d2-7450632d2432.png)
