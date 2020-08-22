# Movie_recommendation_system

Movie recommendation engine using collabrative filtering.

A recommendation engine for movies is created and top 3 unseen movies are suggested to the users based on the ratings given by other users of similar interests.

# Libraries used:
1. Pandas
2. Matplotlib
3. scikit learn - surprise 

# Tasks evolved:
1. Datas were imported and cleaned for data analysis process.

2. Number of unique movies and users were calculated and sparsity of the data was determined.

3. Unique rating distributions bar graphs are plotted.

4. Dimentionality reduction : Rarely rated movies and rarely rated users were filtered to improve the model performance.

5. Train set and prediction set is created . The prediction set contains user-item pair where ratings for certain movies was missing in train set.

6. The model is trained by using surprise package , where a SVD model was created to build a recommendation system .

7. Predict ratings for all user-item pairs that are not in the training set and then to finally Recommend top 3 movies to all users based on predictions.

