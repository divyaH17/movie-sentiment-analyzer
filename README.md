# movie-sentiment-analyzer
# 🎬 Movie Review Sentiment Classifier (LSTM)

## 🧠 Project Overview
This project uses **Deep Learning (LSTM)** to analyze the sentiment of IMDb movie reviews.  
It predicts whether a review is **Positive 😊** or **Negative 😞** based on the text content.

Built entirely using **TensorFlow** and **Keras**, this project demonstrates text preprocessing, neural network training, and evaluation for Natural Language Processing (NLP).

---

## 🎯 Objectives
- Build an LSTM-based model to classify sentiments of movie reviews.
- Learn text preprocessing techniques (tokenization, padding).
- Train and evaluate a neural network using TensorFlow/Keras.
- Maintain version control and documentation using Git and GitHub.

---

## ⚙️ Tech Stack
| Category | Tools |
|-----------|--------|
| Programming Language | Python 3.10+ |
| Framework | TensorFlow, Keras |
| Libraries | NumPy, Matplotlib |
| IDE | Google Colab / PyCharm |
| Dataset | IMDb Reviews (Keras built-in) |
| Version Control | Git + GitHub |

---

## 📚 Dataset
- **Source:** IMDb movie reviews dataset (Keras built-in)
- **Training samples:** 25,000  
- **Testing samples:** 25,000  
- **Classes:** Positive (1), Negative (0)  
- **Words used:** Top 10,000 most frequent words  

---

## 🧩 Model Architecture
| Layer | Type | Description |
|--------|------|-------------|
| 1 | Embedding | Converts word indices to dense vectors |
| 2 | LSTM | Captures sequence and context information |
| 3 | Dense (Sigmoid) | Outputs probability of sentiment (0–1) |

**Loss Function:** Binary Crossentropy  
**Optimizer:** Adam  
**Metrics:** Accuracy  

---

## 🚀 How to Run the Project

### 🧮 1. Clone this repository
```bash
git clone https://github.com/divyaH17/movie-sentiment-analyzer.git
cd movie-sentiment-analyzer
