# Movie-Review-Prediction

### Movie Review Prediction using Multinomial Naive Bayes and Multivariate Bernaulli Event Model

##### Given some reviews of movies and their classes as 1 and 0 where 1 denotes a positive review whereas 0 denotes a negative review, the task is to predict class of a new review.

##### Defining a getCleanReview() function which accepts a review, convert it to all lower case, convert it into tokens using tokenizer, remove all stopwords from it and in the last use PorterStemmer() to get a clean review.

#### Vectorization:

##### 1. Making a vocabulary of all words that occur in all reviews.

##### 2. Then, marking that words (actually their frequencies) wherever they occur and forming a matrix.

#### Prediction:

##### Then, using MultinomialNB and Multivariate Bernoulli Naive Bayes to predict the class of X_test.
