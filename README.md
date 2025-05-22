# Elevate-labs-project
This project tackles fake news detection using Natural Language Processing (NLP) and machine learning. Using a Kaggle dataset of real and fake news articles, the text is preprocessed and vectorized with TF-IDF. A Passive Aggressive Classifier is trained, achieving about 93% accuracy. A Flask-based web app allows users to input news text and receive real-time authenticity predictions. Future plans include integrating deep learning models like LSTM and BERT, detecting satire and clickbait, and developing a browser extension for on-site news verification.

# How it works
1. Dataset Preview
 
2. Dataset Preprocessing
   
3. Vectorization
   
4. Logical Regression - Model Training. The dataset is fairly large and balanced.
Fake and real headlines/articles use noticeably different word patterns—TF-IDF captures that well.
Logistic Regression is a strong linear classifier for high-dimensional sparse text.

5.Interpretability - LIME and SHAP. SHAP- Each bar shows how much a particular word (feature) contributes to the model’s output
The longer the bar, the more important that word is in making predictions
Beeswarm Plot tells positive and negative impact as well, LIME- LIME is Local Interpretable Model-Agnostic Explanations
It explains one prediction at a time by creating a simpler model around that instance
Hence, it shows what features influenced it the most
It’s perfect to understand why a particular article was predicted fake or real 
