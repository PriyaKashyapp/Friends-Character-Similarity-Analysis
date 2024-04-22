# Friends-Character-Similarity-Analysis
This project explores the application of vector space models in natural language processing to quantify the similarity between characters from the popular TV show "Friends". By analyzing dialogue scripts, the project employs semantic analysis techniques to understand character interactions and similarities.

Key Features

    Semantic Analysis: Utilizes techniques like TF-IDF and cosine similarity to analyze character dialogues.
    Character Profiling: Builds semantic profiles for each main character to explore underlying patterns and relationships.
    Visualization: Includes visual representations of character similarities and clustering.
    
Technologies Used

    Python: Primary programming language
    Libraries: NLTK, scikit-learn (sklearn), matplotlib, seaborn, Pandas , Numpy 

Key Highlights

Pre-processing Enhancements

    Tokenization: Splits text into words and converts them to lowercase to normalize.
    
    Cleaning: Removes stop words, punctuation, non-alphabetic characters, and single letters.
    
    Lemmatization: Reduces words to their base form to unify various forms of the same word.
    
    Contractions: Expands shortened words to their full forms to maintain consistency.

Advanced Feature Extraction

    N-grams: Captures word order and context by extracting n-grams.
    
    POS Tagging: Identifies grammatical roles of words.
    
    Sentiment Analysis: Analyzes the sentiment of the text using TextBlob (not included in final results for optimization).
    
    Additional Features: Extracts other linguistic features and attempts gender prediction (not included in final results).

Matrix Transformation Techniques

    TF-IDF Vectorization: Transforms text documents into a matrix of TF-IDF features.
    
    Feature Selection: Utilizes SelectKBest with chi2 to select features based on the chi-squared statistic.

Dialogue Context and Scene Integration

    Data Structuring: Groups data by 'Episode' and 'Scene' to analyze dialogue context scene-by-scene.
    
    Character Analysis: Aggregates dialogue lines and counts for each character for detailed analysis.

Parameter Optimization

    Grid Search: Tests various combinations of parameters for TfidfVectorizer and SelectKBest to find the optimal setup.
    
    Performance Tracking: Compares performance metrics like mean rank and accuracy across configurations.

Similarity Matrix Analysis

    Comparison: Analyzes how characters' dialogues are similar or different using a similarity matrix.
    
    Character Insights: Identifies which characters have the most and least in common based on their dialogue patterns.


Conclusion

This analysis effectively utilizes NLP to delve into the dynamics of character interactions in "Friends," revealing insights into how characters relate through dialogue. Enhanced preprocessing, sophisticated feature extraction, and careful parameter tuning have significantly improved the model's ability to classify and understand character similarities.
