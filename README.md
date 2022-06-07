# IRProject
Information Retrieval System
Backend:python language & flask lib
Frontend: Angular Framework

This system is capable of adding text documents in a specific field and the ability to
query natural language textually for information within these files..

System architecture:
First of all we have two data set(CICI.CACM)
For more Info about dataset visit this site=>https://www.pragmalingu.de/docs/guides/data-comparison
Divide the dataset into a document based on the number of paragraphs into paragraphs
Text Preprocessing for each document
Stemming words using nltk
Accessing irregular verbs using nltk
Access different expressions using en_core_web_sm,sm
Correcting wrong words using autocorrect
translate queries using googletrans
Accessing names by different written representation methods using turtle,numpy
Indexes of Documents using  sklearn.metrics.pairwise
Match the query with the content using sklearn.metrics.pairwise

Search interface in order to query and see results
