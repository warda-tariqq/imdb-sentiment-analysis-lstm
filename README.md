# 🎬 IMDB Sentiment Analysis with LSTM

This project performs binary sentiment classification on the IMDB movie reviews dataset using an LSTM-based deep learning model built with TensorFlow.

## 📁 Files
- `imdb_sentiment_lstm.ipynb`: Main notebook with all code
- `IMDB Dataset.csv`: Dataset used (50K movie reviews)


## 🚀 Features
- Data cleaning and preprocessing
- Tokenization and padding
- LSTM with dropout and L2 regularization
- Accuracy visualization
- Model saving for later use

## 🛠 How to Run
1. Clone this repo or download the notebook
2. Open the notebook in Google Colab or Jupyter
3. Upload the IMDB dataset (`IMDB Dataset.csv`)
4. Run all cells to train and evaluate the model

## 📊 Results
- **Training Accuracy:** ~94%
- **Validation Accuracy:** ~88%

This version improves generalization by reducing overfitting using regularization techniques.

## 🔮 Future Improvements
- Use pre-trained embeddings like **GloVe**
- Add **Bidirectional LSTM** layers
- Fine-tune **transformer models** like **BERT**

## 📌 Dataset Source
[IMDB 50K Dataset on Kaggle](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)

