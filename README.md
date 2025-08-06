# Text Analysis of Political Speeches

This project explores the linguistic patterns, sentiment, and rhetorical strategies in U.S. presidential inaugural speeches using Python-based natural language processing (NLP).
The goal is to uncover differences in tone, content, and speaker style across four presidents—Clinton (1993), Bush (2001), Obama (2009), and Trump (2017)—and to apply both statistical and theoretical reasoning to interpret these findings.

Originally developed for a university assignment, this project has been extensively refined for inclusion in a professional portfolio.

---

## Project Scope

The analysis compares multiple speeches by:

* Cleaning and tokenizing text from raw transcript files
* Constructing a custom Bag-of-Words (BoW) model
* Calculating word frequencies and visualizing top terms
* Comparing speeches using cosine similarity (manual and TF-IDF-based)
* Performing sentiment analysis using the Bing Liu opinion lexicon
* Plotting sentiment progression across each speech
* Generating word clouds to highlight most frequent terms

---

## Technologies Used

* Python: pandas, nltk, re, matplotlib, seaborn, scikit-learn, wordcloud, plotly
* Jupyter Notebook

---

## Highlights

### Text Preprocessing

* Lowercasing, punctuation removal, and whitespace normalization
* Stopword removal using NLTK
* Stemming (Porter Stemmer)
* Custom function for building word frequency dictionaries by segment

### Frequency & Similarity Analysis

* Relative word frequency comparison
* Top 15 word comparisons per speech
* Cosine similarity comparisons:
* Manual implementation using word vector overlap
* Correlation matrix from TF-IDF document-term matrix
* Visualized similarity via heatmap

### Sentiment Analysis

* Used Bing Liu's sentiment lexicon (positive/negative word list)
* Assigned polarity to matched words
* Aggregated sentiment by 5% intervals across each speech
* Line plots to show sentiment progression

### Word Cloud Generation

* One word cloud per president
* Emphasized most frequent terms
* 2x2 subplot layout for side-by-side comparison

### Visual Outputs

* Grouped bar chart of top 20 word frequencies across speeches (Plotly)
* Sentiment progression over time (Matplotlib line plots)
* Heatmap of cosine similarity scores (Seaborn)
* Word clouds per president (WordCloud + Matplotlib)
