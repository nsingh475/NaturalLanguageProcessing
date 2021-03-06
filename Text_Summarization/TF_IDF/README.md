# TF-IDF text summarization

Term Frequency – Inverse Document Frequency (TF-IDF) belongs to the extractive text summarization approach.
It is a measure that assigns weights to a word in a document based upon the frequecncy of its occurence.

Intuition behind TF-IDF:
1. If a word appears frequently in a document, then it should be important and we should give that word a high score. 
2. If a word appears in too many other documents, it’s probably not a unique identifier, therefore we should assign a lower score to that word.

TF(w) = (Number of times term w appears in a document) / (Total number of terms in the document)
IDF(w) = log_e(Total number of documents / Number of documents with term w in it)

TFIDF(w) = TF(w) * IDF(w)


#### Some useful links for TF-IDF:
1. https://towardsdatascience.com/text-summarization-using-tf-idf-e64a0644ace3
2. https://medium.com/@acrosson/summarize-documents-using-tf-idf-bdee8f60b71

