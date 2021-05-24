# Irony recognition
Code and data for my 3rd year thesis "Distributional semantic models in sarcasm and irony detection in blogs". HRU HSE, Moscow 2021.

#### Jupyter notebook files:  
- Pikabu parser.ipynb - code used for collecting posts from Pikabu.ru
- Creating feature dataframes.ipynb - code used for calculating feature values for further classification (train and test corpora)
- Feature distribution and models.ipynb - example visualizations of feature distribution + building and assessing logreg models

#### Data folder:  
- raw_texts.csv - raw texts parsed from Pikabu.ru *(warning: strong language)*
- train_corpus.csv - annontated corpus for training models (8 956 sentences)
- test_corpus.csv - annontated corpus for assessing models (100 sentences)
- train_features.csv - balanced training corpus with features (2 002 sentences)
- test_features.csv - unbalanced test corpus with features (100 sentences)
- test_classification_results.csv - sentence text, predictions and true labels for 100 test sentences
