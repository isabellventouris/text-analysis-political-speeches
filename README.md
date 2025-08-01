# Text Analysis of Political Speeches

This project explores the **linguistic patterns and sentiment** embedded in a set of U.S. presidential speeches using Python-based natural language processing (NLP).
The goal is to uncover **differences in tone, content, and rhetorical strategy** across speakers—and to apply theoretical reasoning to interpret those findings.

Originally developed for a university assignment, this project has been refined for inclusion in a professional portfolio.

---

## Project Scope

The analysis compares multiple speeches by:

* Cleaning and tokenizing the text
* Calculating word frequencies
* Comparing speeches using statistical metrics like cosine similarity
* Conducting sentiment analysis with a lexicon-based method
* Visualizing patterns using word clouds and sentiment plots

---

## Technologies Used

* Python: `pandas`, `nltk`, `scikit-learn`, `wordcloud`, `matplotlib`
* Jupyter Notebook

---

## Highlights

### Text Preprocessing

* Lowercasing, punctuation removal
* Optional stemming
* Stopword removal

### Frequency & Similarity Analysis

* Relative word frequency comparison
* Cosine similarity between speeches
* TF-IDF vectorization

### Sentiment Analysis

* Used **Bing Liu's opinion lexicon**
* Assigned positive/negative polarity at word level
* Calculated average sentiment over time

### Sentiment Visualization

* Static `matplotlib` plots
* Sentiment progression per speech
* Color-coded lines with speaker labels

### Word Cloud Generation

* Created per speaker
* Visual emphasis on most frequent terms

---

## Future Extensions

* Interactive visualizations using `plotly`
* Topic modeling (e.g., LDA)
* N-gram analysis (phrases and collocations)
* Advanced sentiment techniques (e.g., negation handling)
