Reference Links:
https://www.datacamp.com/community/tutorials/text-analytics-beginners-nltk 
https://www.datacamp.com/community/tutorials/simplifying-sentiment-analysis-python
https://www.datacamp.com/community/tutorials/stemming-lemmatization-python 


https://machinelearningmastery.com/bagging-and-random-forest-for-imbalanced-classification/
https://github.com/avaiyang/Movie-Rating-and-Prediction-Model
https://github.com/Yereya/Amazon-database/blob/master/Combining%20Review%20Text%20Content%20and%20User%20Similarity%20Matrix%20to%20Predict%20Review%20Rating.ipynb
https://www.kaggle.com/sherinclaudia/movie-rating-prediction
http://cs229.stanford.edu/proj2011/MehtaPhilipScaria-Predicting%20Star%20Ratings%20from%20Movie%20Review%20Comments.pdf


https://towardsdatascience.com/introduction-to-nlp-part-1-preprocessing-text-in-python-8f007d44ca96 
https://shravan-kuchkula.github.io/scrape_imdb_movie_reviews/#construct-a-dataframe 



DATA PRE-PROCESSING

•	Since the dataset has missing reviews for rating 5 and 6, I am working on retrieving those data from IMDB website using BeautifulSoup and IMDB API. This task is in progress.
•	Steps involved in cleaning the data: [Libraries used: nltk and pandas]
	o	Removing HTML tags like <br> using regex from the reviews
	o	Removing words with numbers
	o	Sentence tokenization for generating proper bigrams for negation features like “not good”
	o	Word tokenization of the entire review text by ignoring punctuations.
	o	Removing stop words from the tokenized words.
	o	Lemmatization on the tokenized words without stop words.

References:

1.	http://cs229.stanford.edu/proj2011/MehtaPhilipScaria-Predicting%20Star%20Ratings%20from%20Movie%20Review%20Comments.pdf
2.	https://towardsdatascience.com/introduction-to-nlp-part-1-preprocessing-text-in-python-8f007d44ca96
3.	https://stackoverflow.com/ 
