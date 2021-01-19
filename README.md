# Fake-News

Files pertaining to the Fake News project for University of Montana last fall. For discerning fake news articles about politics from real articles, gradient tree boosting and logistic regression performed well although the gradient tree boosting (which performed the best) took considerably more time. Adding parts-of-speech tags (grouped into 3-grams which gave best results) offered marginal improvement if any over using words only. TF-IDF vectorization (scaling word counts and 3-gram counts for parts of speech for a single document by counts across all documents) markedly improved performance of k-nn methods but provided only slight improvement if any for other algorithms.

Summary details are at the end of the "combotfidf" file.
