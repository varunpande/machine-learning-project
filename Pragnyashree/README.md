
This part of the Project consists of Naive Baye's implementation for estimating IMDB ratings of comments using NLP. Each process has been described below.

DATA PRE-PROCESSING:

1. Since the dataset has missing reviews for rating 5 and 6, data from ratings 4 and 7 were divided and assigned to missing ratings.
2. Steps involved in cleaning the data: [Libraries used: nltk and pandas]
	a.Removing HTML tags like <br> using regex from the reviews
	b.Removing words with numbers
	c.Sentence tokenization for generating proper bigrams for negation features like “not good”
	d.Word tokenization of the entire review text by ignoring punctuations.
	f.Removing stop words from the tokenized words.
	g.Lemmatization on the tokenized words without stop words.

TRAINING THE MODEL:

Sklearn's Naive Bayes model is used for training the model and testing the model's accuracy. Hyperparameter tuning is also performed by modifying alpha values.

CONCLUSION:
Naive Bayes performed best among the other two models KNN and Random Forest with least mean squared error of 9.65. This project can be used to calculate missing ratings against comments in IMDB movie reviews

References:

1. http://cs229.stanford.edu/proj2011/MehtaPhilipScaria-Predicting%20Star%20Ratings%20from%20Movie%20Review%20Comments.pdf
2. https://towardsdatascience.com/introduction-to-nlp-part-1-preprocessing-text-in-python-8f007d44ca96
3. https://stackoverflow.com/ 
4. https://www.datacamp.com/community/tutorials/text-analytics-beginners-nltk 
5. https://www.datacamp.com/community/tutorials/simplifying-sentiment-analysis-python
6. https://www.datacamp.com/community/tutorials/stemming-lemmatization-python 
7. https://machinelearningmastery.com/bagging-and-random-forest-for-imbalanced-classification/
8. https://github.com/avaiyang/Movie-Rating-and-Prediction-Model
9. https://github.com/Yereya/Amazon-database/blob/master/Combining%20Review%20Text%20Content%20and%20User%20Similarity%20Matrix%20to%20Predict%20Review%20Rating.ipynb
10.https://www.kaggle.com/sherinclaudia/movie-rating-prediction
11.http://cs229.stanford.edu/proj2011/MehtaPhilipScaria-Predicting%20Star%20Ratings%20from%20Movie%20Review%20Comments.pdf
12.https://towardsdatascience.com/introduction-to-nlp-part-1-preprocessing-text-in-python-8f007d44ca96 
13.https://shravan-kuchkula.github.io/scrape_imdb_movie_reviews/#construct-a-dataframe 
