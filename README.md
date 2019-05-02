# flamenco-topicmodeling
Additional material about flamenco analisys using NLP Topic Modelling

Scores files:
* file: puntuaciones2.desg.csv

Best model:
* file: resultTopics__dict_tfidf_s-3_d2-1.0__lda_nt3_np1(000).txt
* Dictionary union of 1-grams, 2-grams, 3-grams
* Filter of words with only 1 count
* Bag of words: TF-IDF
* 3 topics

Best NMF model (keeping size words of best dictionary):
* file: resultTopics__dict_freq_s-3_d1-0.5__nmf_nt3_np1(001).txt
* Filter of words with only 1 count
* Bag of words: frequency count
* 3 topics

Best LSI model (keeping size words of best dictionary):
* file: resultTopics__dict_tfidf_s-3_d4-0.5__lsi_nt3_np1(002).txt
* Filter of words with count below 4 and above 50% of corpus
* Bag of words: TF-IDF
* 3 topics

Best LDA model with 10 topics:
* file: resultTopics__dict_freq_s-3_d2-1.0__lda_nt10_np1(001).txt
* Same dictionary best model
* Filter of words with count below 2
* Bag of words: Frequency count
* 10 topics

