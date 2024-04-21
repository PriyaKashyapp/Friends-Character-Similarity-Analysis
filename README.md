# Friends-Character-Similarity-Analysis
This project explores the application of vector space models in natural language processing to quantify the similarity between characters from the popular TV show "Friends". By analyzing dialogue scripts, the project employs semantic analysis techniques to understand character interactions and similarities.
Key Features

    Semantic Analysis: Utilizes techniques like TF-IDF and cosine similarity to analyze character dialogues.
    Character Profiling: Builds semantic profiles for each main character to explore underlying patterns and relationships.
    Visualization: Includes visual representations of character similarities and clustering.
Technologies Used

    Python: Primary programming language
    Libraries: NLTK, sklearn, matplotlib, seaborn

Key Highlights

Data Pre-processing

    Tokenization, conversion to lowercase for normalization.
    Removal of stopwords, punctuation, non-alphabetic characters, and single letters.
    Expansion of contractions and lemmatization to ensure consistency and focus on meaningful words.

Feature Extraction and Transformation

    Utilization of n-grams to capture context and word order.
    Application of POS tagging and selective sentiment analysis.
    Implementation of TfidfVectorizer for converting text documents into a matrix of TF-IDF features.
    Use of SelectKBest with chi-squared for feature selection.

Model Training and Validation

    Extensive parameter search to optimize model configurations.
    Cross-validation to fine-tune model parameters and assess model performance across different setups.

Analysis of Results

    Evaluation of the similarity matrix to identify character relationships and dialogue similarities.
    Examination of the mean rank, cosine similarity, and accuracy across different stages of the project to measure performance improvements.
    
