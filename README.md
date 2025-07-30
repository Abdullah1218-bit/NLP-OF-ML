🧠 NLP for Machine Learning

In this section, I've completed a full NLP (Natural Language Processing) workflow for machine learning tasks.

✅ Steps Followed:

Text and Emotion Separation

Split the dataset into input Text and corresponding Emotion labels.

Label Encoding

Converted categorical emotions into numeric form using:

LabelEncoder from scikit-learn

or pandas.factorize()

Text Cleaning

Used the clean-text library — one of the easiest ways to clean text by:

Removing punctuation, emojis, digits, and URLs

Converting text to lowercase

Stopwords Removal

Applied the nltk (Natural Language Toolkit) library

Removed common stopwords like a, about, any, and, are, before, been, both, etc.

🧮 CountVectorizer

In the CountVectorizer folder:

Created sparse matrices representing word frequencies.

Demonstrated how to adjust matrix dimensions using ngram_range.

📊 TF-IDF (Term Frequency–Inverse Document Frequency)

In the TF-IDF folder:

Explained the difference between CountVectorizer and TfidfVectorizer.

TF-IDF helps reduce the impact of commonly used words and emphasizes informative ones.

🤖 NLP Model Project

In the Project folder:

Trained an NLP classification model using Multinomial Naive Bayes.

The pipeline includes preprocessing, vectorization, and model training.

