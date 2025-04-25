# Movie Review Sentiment Analysis 🎬

This project demonstrates a basic **Sentiment Analysis** model using the `movie_reviews` dataset from the **NLTK** library. It classifies movie reviews as either **positive** or **negative** using **Naive Bayes** and **CountVectorizer**.

---

## 📂 Dataset

The dataset used is `movie_reviews` from the NLTK corpus, which contains 2,000 labeled movie reviews (1,000 positive and 1,000 negative).

---

## ⚙️ Tech Stack

- Python 🐍
- NLTK
- scikit-learn (sklearn)
- Pandas
- CountVectorizer (for text feature extraction)
- Multinomial Naive Bayes (for classification)

---

## 🚀 How It Works

1. **Load and preprocess data** from the NLTK corpus.
2. **Vectorize** the text using `CountVectorizer`.
3. **Train** a `MultinomialNB` model.
4. **Evaluate** it using accuracy score.
5. **Predict** sentiment of new movie reviews.

---

## 📈 Accuracy

The model achieves an accuracy of around **85–90%** on the test set (may vary slightly due to shuffling and train/test split).

---

## 🧪 Example Prediction

```python
Review: "The movie was awesome!" -> Sentiment: pos  
Review: "It was a boring movie." -> Sentiment: neg
