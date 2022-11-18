# Alessandro Cortese - Portfolio
## M.Sc. in Data Science student @ UniTN

## [Project 1: Exploratory Data Analysis and Visualization of Renewable Energy Consumption in the EU](https://github.com/alescortes/european-energy-consumption)
- Analysis of a Eurostat dataset about renewable energies in the EU. 
- Created different types of visualizations (choropleth maps, bar charts, waffle charts, lineplots, ...) to gather insight from the data.
- Python libraries used: pandas, geopandas, matplotlib, seaborn

## [Project 2: Big Data System to optimize the delivery of goods in the city of Milan](https://github.com/alescortes/food-delivery_bdt2022)
- Developed a Big data system to generate orders to a food delivery service and to match a set of delivery men to deliver such orders. 
- The system includes a MongoDB database to store the deliverymen, the pending orders, and the processed orders and a MQTT queue which acts as a buffer in the data ingestion phase.
- Distances are calculated using Openrouteservice API.
- The result of the program is a flask dashboard which displays a map and a series of analytics about the orders.
- Code is packaged using docker

## [Project 3: Content-Based Image Retrieval System]
- *Work in progress*
- A comparison of different feature extractor methods for CBIR
- Used both standard Computer Vision techniques (ORB, SIFT, SURF) and Deep Learning (VGG16).
- Python libraries used: OpenCV, scikit-image, Tensorflow.

## [Project 4: Fake news classifier using Natural Language Processing](https://github.com/alescortes/fake-news-classifier)
- Used SVM and Random Forest to  to classify political statements from the LIAR dataset (n = 12792) as fake news or not.
- Compared different models (bag-of-words with tf-idf, word2vec, doc2vec) to create embeddings from text.
- Python libraries used: pandas, scikit-learn, NLTK, gensim.

## [Project 5: Investigating the impact of the pandemic on music consumption]
- Used topic modelling and LDA on lyrics from songs before and after the pandemic.
- Compared logistic regression, boosted trees and random forest classifiers to distinguish between songs before and after the pandemic based on their audio features.
- Used Spotify API to retrieve audio features and Genius API to scrape lyrics.
- R libraries used: ggplot2, tidymodels, tm, topicmodels, caret, gbm, tree, randomForest.
- Will upload this soon hopefully
