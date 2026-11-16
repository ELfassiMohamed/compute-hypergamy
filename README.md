# Compute Hypergamy — Machine Learning & Deep Learning Notebooks

A collection of Jupyter notebooks exploring **Machine Learning** and **Deep Learning** techniques for **Natural Language Processing (NLP)**, with a focus on sentiment analysis and text clustering (primarily on IMDb movie reviews).

## Contents

| Notebook | Description |
|----------|-------------|
| [`Bidirectional LSTM.ipynb`](Basic%20ML%20DL/Bidirectional%20LSTM.ipynb) | Bidirectional LSTM model built with TensorFlow / Keras for text classification. |
| [`Clustering.ipynb`](Basic%20ML%20DL/Clustering.ipynb) | Introduction to clustering as an unsupervised machine learning technique. |
| [`IMDb Sentiment Clustering (K-Means).ipynb`](Basic%20ML%20DL/IMDb%20Sentiment%20Clustering%20(K-Means).ipynb) | Unsupervised sentiment clustering on IMDb movie reviews using K-Means, TF-IDF, and sentiment indicators. |
| [`Deep Learning NLP RNN LSTM.ipynb`](Basic%20ML%20DL/Deep%20Learning%20NLP%20RNN%20LSTM.ipynb) | Deep learning NLP comparing SimpleRNN and LSTM (Long Short-Term Memory) models. |
| [`ML NLP Movie Review Classification.ipynb`](Basic%20ML%20DL/ML%20NLP%20Movie%20Review%20Classification.ipynb) | Machine learning classification of movie reviews using TF-IDF, BERT, Word2Vec embeddings with Logistic Regression and SVM. |
| [`RNN IMDB Sentiment.ipynb`](Basic%20ML%20DL/RNN%20IMDB%20Sentiment.ipynb) | Recurrent Neural Network (RNN) for IMDB sentiment analysis. |

## Topics covered

- **Recurrent networks:** RNN, LSTM, Bidirectional LSTM
- **Deep learning:** TensorFlow / Keras
- **Classical ML:** Logistic Regression, SVM, K-Means clustering
- **NLP:** TF-IDF vectorization, Word2Vec, BERT embeddings, fine-tuning
- **Applications:** Sentiment analysis, document clustering on IMDb movie reviews

## Requirements

The notebooks are designed to run in **Google Colab** (GPU/TPU) and use:

- Python 3
- pandas, NumPy
- scikit-learn
- TensorFlow / Keras
- Matplotlib, Seaborn
- TextBlob, VADER (sentiment)
- Transformers (BERT)

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/compute-hypergamy.git
   cd compute-hypergamy
   ```
2. Open any `.ipynb` notebook in [Google Colab](https://colab.research.google.com) or Jupyter.
3. If running in Colab, mount your Google Drive to access the dataset under `/content/drive/MyDrive/Colab Notebooks/Data`.

## License

This project is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
