---
layout: default
---

## [Computational analysis of Twitter discourse surrounding the protests in Iran](https://github.com/alescortes/digital-social-data)
- Project for the Digital Social Data course at the University of Trento.
- Collected and cleaned 500K Tweets over the span of three weeks using _rtweet_.
- Employed text mining, topic modelling and sentiment analysis techniques to gather insight on the protest movement
- R libraries used: ggplot2, janitor, dplyr, tm, quanteda, topicmodels, syuzhet, stm
- _Will upload the code soon hopefully..._

Take a look at the report [here](https://raw.githubusercontent.com/alescortes/digital-social-data/main/Cortese_Digital_Social_Data_Report.pdf).

Some visualizations of the analysis:

Top 15 self-reported user locations:   
![dsd_Rplot_locations](../imgs/dsd_Rplot_locations.png) 

Map of the actual geolocated tweets:
![dsd_rplot_map](../imgs/dsd_rplot_map.png)

A simple word network which can be useful to see the most common word bigrams in the whole corpus:

![dsd_word_network](../imgs/dsd_word_network.png)

Sentiment analysis showing the prevalence of anger, fear and sadness over the analyzed time span:

![dsd_anger_sadness_fear_time](../imgs/dsd_anger_sadness_fear_time.png)

Employing [Structural Topic Model](https://www.structuraltopicmodel.com/) (STM) to show how the topics of the Twitter 
discourse surrounding the protests evolve over time:

![dsd_Rplot_stm_weeks](../imgs/dsd_Rplot_stm_weeks.png)


[back](./portfolio.md)