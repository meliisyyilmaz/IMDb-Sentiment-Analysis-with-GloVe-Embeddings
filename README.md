# IMDb-Sentiment-Analysis-with-GloVe-Embeddings


A small side project that turned into a deep dive into classic NLP.  
I built a sentiment analysis model using the IMDb movie reviews dataset — combining tried-and-true techniques with a few modern tweaks to keep it clean, fast, and generalizable.

## 🧠 Project Highlights

- Dataset: IMDb (25,000 labeled movie reviews)
- Preprocessing: manual cleaning (HTML tag removal, lowercasing, etc.)
- Embeddings: Pretrained [GloVe](https://nlp.stanford.edu/projects/glove/) (100-dimensional, frozen)
- Architecture:
  - Bidirectional LSTM (because context matters)
  - Dropout for regularization
  - EarlyStopping (because we like to stop while we're ahead)

## 📈 Results

- ✅ ~84% validation accuracy  
- ✅ Smooth, stable training  
- ✅ No transformers, just efficient deep learning done right

<p align="center">
  <img src="assets/imdb_training_plot.png" alt="Training Accuracy and Loss" width="600">
</p>
