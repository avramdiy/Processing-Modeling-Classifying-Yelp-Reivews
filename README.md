# Processing-Modeling-Classifying-Yelp-Reivews

<p>Began by loading a subset of the 8-gigabyte Yelp Review Data<br>
  
Loaded NLTK 'punkt' and SpaCy to define a function to tokenize the document
Transformed text reviews into a document-term matrix
Trained a NearestNeighbors model to find the 10 most similar reviews
Applied same model to a fake review to identify reviews with cosine similarity
Applied GridSearchCV to optimize hyperparameters and predicted the star rating for a fake review
Extracted topics and word importance from an LDA model and visualized the top words for each topic using bar plots within Matplotlib
