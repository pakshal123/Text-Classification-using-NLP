# Data Mining for Business - Memetracker Data Analysis

## Project Overview

This repository contains the code, documentation, and results of the "Analyzing the Memetracker Data" project undertaken for the course BUDT758T - Data Mining for Business.

### Team Members

- Pakshal Shah
- Sreerag Mahadevan Cheeroth




### Original Work Statement

We, the undersigned, certify that the actual composition of this proposal was done by us and is original work.

| Contact Author | Typed Name | Signature          |
| -------------- | ---------- | ------------------ |
| Pakshal Shah | Pakshal Shah | (Signature) |


## Executive Summary

In this project, we thoroughly analyzed the Memetracker dataset, consisting of around 96 million records. Our focus was on extracting and interpreting "Quotes" using a text mining process to understand the sentiment polarity of information sources over time. We visualized the data through a network diagram, providing insights into the interconnections between positive and negative domains.

## Data Description

The dataset used for this project was obtained from Stanford, covering the period from August 2008 to April 2009. The original dataset can be found [here](https://snap.stanford.edu/data/memetracker9.html).

## Research Questions

- What is the distribution of sentiment labels (neutral, positive, negative) in the Memetracker dataset?
- How does the sentiment of quotes vary over different months in 2008?
- What are the top domains associated with positive and negative sentiment?

## Methodology

### Data Cleaning and Pre-processing

We utilized Python for data cleaning due to the dataset's size. We removed rows without a "Q" value and performed text pre-processing, including lowercasing, punctuation removal, and sentiment analysis using the TextBlob library.

### Visualization and Interpretation

We visualized the results through histograms and scatter plots, observing trends in sentiment distribution and its correlation with word count.

## Results and Findings

- Due to computational limits, we analyzed a subset of 500,000 rows, revealing trends in sentiment distribution.
- Sentiment analysis for August, October, and December 2008 showcased varying proportions of neutral, positive, and negative quotes.
- Domains like "43things.com" and "blog.myspace.com" were prominent in both positively and negatively labeled quotes.

## Conclusion

Despite computational challenges with the massive dataset, we successfully categorized domains based on sentiment and computed sentiment scores for online quotes. Future work involves using database queries for more accurate findings.

## Appendix

(Any additional information or supplementary materials)

## Grading Notes

- Technical quality of the work.
- Interestingness and originality of the project.
- Ambitiousness of the project.
- Effectiveness of presentation.
- Quality of writing and visual presentation.

## Peer Evaluations

(Peer evaluations to be submitted on Canvas within two days after the presentation)

