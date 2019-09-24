# Data_Visualization

This notebook creates a wordcloud image using the kaggle wine review dataset. This notebook parses the "description" text field within the
data set via a pandas dataframe and joins each word into a list which is passed as an argument into the wordcloud object. The notebook 
also creates a list of "stopwords" (i.e. common words such as: the, a, etc) from a stopword file, which is passed as an argument when 
creating the wordcloud object. 
