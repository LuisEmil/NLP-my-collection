# NLP-my-collection
A collection of Natural Language Processing (NLP) projects in Python, showcasing text preprocessing, sentiment analysis, and other NLP tasks.

# 📝 Current Projects
## 1. Basic Lexicon Extractor
Lexicon-based approach to classify text as positive, negative, or neutral. Automatic word extraction and preprocessing from a Twitter dataset.
It automatically extracts words appearing in positive and negative samples and removes words that appear in both (neutral words).
### Key features:
- Preprocesses text (cleans, lowercases, tokenizes)
- Builds positive and negative word sets from labeled data
- Removes overlapping (neutral) words
- Prints lists of sentiment-specific words

## 2. Basic Lexicon Counter
Lexicon-based approach to classify text as positive, negative, or neutral. Automatic word counter and preprocessing from a Twitter dataset.
It creates frequency-based word counters for both sentiments and can use them to classify new sentences.
### Key features:
- Counts word frequencies using collections.Counter
- Keeps all words (no neutral removal)
- Shows top positive and negative words
- Includes a simple rule-based sentiment classifier
