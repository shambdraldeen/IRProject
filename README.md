# IRProject
Information Retrieval System
Backend:python language & flask lib
Frontend: Angular Framework,

This system is capable of adding text documents in a specific field and the ability to
query natural language textually for information within these files..

<System architecture>
1-First of all we have two data set(CICI.CACM)
For more Info about dataset visit this site=>https://www.pragmalingu.de/docs/guides/data-comparison
2-Divide the dataset into a document based on the number of paragraphs into paragraphs
3-Text Preprocessing for each document
4-Stemming words using nltk
5-Accessing irregular verbs using nltk
6-Access different expressions using en_core_web_sm,sm
7-Correcting wrong words using autocorrect
8-translate queries using googletrans
9-Accessing names by different written representation methods using turtle,numpy
10-Indexes of Documents using  sklearn.metrics.pairwise
11-Match the query with the content using sklearn.metrics.pairwise

Finally💕Search interface in order to query and see results
