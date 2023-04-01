---
layout: default
---

## [Fake news classifier using Natural Language Processing](https://github.com/alescortes/fake-news-classifier)
- Group project for the Natural Language Processing course at the University of Twente, the Netherlands.
- Used SVM and Random Forest to classify political statements from the LIAR dataset (n = 12792) as fake news or not.
- Compared different models (bag-of-words with tf-idf, word2vec, doc2vec) to create embeddings from text.
- Performed hyperparameter tuning and feature importance.
- Repeated the analyses adding metadata (context, party affiliation of the speaker, state)
- Employed error analysis to get insight behind the predictions.
- Python libraries used: pandas, scikit-learn, NLTK, gensim.

You can take a look at the report [here](https://raw.githubusercontent.com/alescortes/fake-news-classifier/main/NLP_Project_Group16.pdf). 
The images refer to the Random Forest model with mixed unigram and bigram tf-idf embeddings, plus metadata.

|             Confusion matrix              |  Feature importance|
|:-----------------------------------------:|:-------------------------:|
| ![nlp_conf_mat](../imgs/nlp_conf_mat.jpg) | ![nlp_feat_imp](../imgs/nlp_feat_imp.jpg)|



[back](./portfolio.md)