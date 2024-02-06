# Text-Mining-and-NLP

In this task we will demonstrate our text mining and linguistic skills to deduce insights about the Star Wars movie scripts. We are provided with a collection of script dialogue between characters for the first three movies (episodes 4-6) also known as The Original Trilogy. We are also provided with Word Cloud Masks for us to make use of. Check the list of libraries and tutorial articles at the end of this document.
Our tasks: “Do. Or do not. There is no try.” — Yoda

1. Find the characters with most dialogue in each of The Original Trilogy (episodes IV, V, VI).
2. Plot the number of dialogues according to character for each of the episodes (i.e. plot the above findings).
3. Add a new column “episode” to the three datasets (to distinguish between the three episodes) and concatenate them into one dataset.
4. Discover the Frequency Distribution of words in The Original Trilogy.
5. Create a Frequency Distribution plot of the most repeated words in The Original Trilogy.
6. Perform text-mining operations to prepare our dataset for further textanalysis. (Use the NLTK library) a. Convert to lower case, word tokenization, removing stopwords, lexicon normalization (lematization)…etc. b. Add the resulting array list to the dataset as a new column “new_script”.
7. Repeat steps 4 & 5 but this time check the frequency distribution of the “new_script”.
8. Use Word Clouds to visually represent the most repeated words for Darth Vader and Yoda. (use the provided wordcloud masks, make one word cloud for each character)
9. Discover the most repeated words and the most relevant words in The Original Trilogy script. Remember: Bag of Words just creates a set of vectors containing the count of word occurrences in the document, while the TF-IDF model contains information on the more important words and the less important ones as well.
10. Perform a sentiment analysis on the movie script. In python, sentiment analysis libraries for quick solutions are rare while in R, there are many such libraries. Check out ttps://pypi.org/project/sentic/ which provides a solution compatible with Python (or any other library we prefer). In Python we will find that the most common way to perform sentiment analysis is done by means of a Naïve Bayes Classifier, where we build the model (but we are not necessarily required to build one, we choose the way we want to do it). In the Star Wars universe, the Sith (like Darth Vader or Emperor Palpatine) are associated with negative feelings such as anger, fear, hate, etc. Conversely, the Jedi (like Luke Skywalker or Yoda) teach its followers to not give in to feelings of anger toward other lifeforms, which would help them resist fear and prevent them from falling to the Dark Side of the Force. According to our sentiment analysis done previously, do we notice differences between the Dark Side characters and the Light Side characters? Explain our insights!

