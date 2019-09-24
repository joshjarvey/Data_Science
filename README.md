# WordCloud Project

This notebook creates a wordcloud image using the kaggle wine review dataset. It parses the "description" text field within the data set via a pandas dataframe and joins each word into a list which is passed as an argument into the wordcloud object. The notebook also creates a list of "stopwords" (i.e. common words such as: the, a, of, etc.) from a stopword file, which is passed as an argument when creating the wordcloud object. Lastly, the notebook creates a numpy array from an image file, transforms the pixel color value to create a hard boundary outline, which is also passed to the wordcloud object as the masked argument to provide "shape" to the wordcloud.

Finally, the wordcloud object is displayed on the canvas using the matplotlib.pyplot library.

*** All credit goes to Duong Vu from DataCamp: https://www.datacamp.com/community/tutorials/wordcloud-python *** 
*** Kaggle dataset can be located here: https://www.kaggle.com/zynicide/wine-reviews ***
