# Word frequency analysis of studies on consciousness

Project made fo Advanced Python for Cognitive Scientists classes at the University of Warsaw

## Author
- [Jan Opala](https://github.com/janopala)

## Aim of the project
The goal of the project was to analyze how different vocabulary is used in two distinct groups of scientific papers: neurobiological articleas about consciousness and studies on consciousness from experimental philosophy.

## Overview
I decided to extract textual data from 10 pdfs, 5 from each group. I downloaded pdfs for the project from external links, extracted texts from documents and began tokenization.
I used WordCloud library to visualize word frequency for each paper, for instance:

![cloud_text](https://github.com/JanOpala/consciousness-word-frequency-analysis/blob/main/screenshots_word_freq/cloud_text.png)

In order to see which words were representative for each group of texts as well as for all of them I calculated TF-IDF metric for each token and visualize lowest scored on the bar plots:

![tf_idf_neuro](https://github.com/JanOpala/consciousness-word-frequency-analysis/blob/main/screenshots_word_freq/tf-idf_neuro.png)
![tf_idf_philo](https://github.com/JanOpala/consciousness-word-frequency-analysis/blob/main/screenshots_word_freq/tf-idf_philo.png)
![tf_idf_all](https://github.com/JanOpala/consciousness-word-frequency-analysis/blob/main/screenshots_word_freq/tf-idf_all_low.png)
