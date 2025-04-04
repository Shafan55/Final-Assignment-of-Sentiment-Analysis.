pip install -r requirements.txt
# or install manually:
pip install pandas numpy nltk scikit-learn imbalanced-learn matplotlib seaborn beautifulsoup4 requests



# 🧠 Sentiment Analysis Pipeline with Web Scraping & Speech-to-Text

This project is a complete NLP pipeline that takes in raw audio files and text content (via web scraping), processes them, and performs sentiment classification using machine learning. It integrates text preprocessing, dataset balancing, and model training all in one place.

---

## 📁 Project Structure

| File | Description |
|------|-------------|
| `Datset_Creation.ipynb` | Transcribes audio files using AssemblyAI and saves speaker-attributed text. |
| `Web_scracping.ipynb` | Scrapes web content (e.g., headlines or articles) for sentiment analysis. |
| `Speech_Model_newnew.ipynb` | Preprocesses and trains a sentiment classification model with dataset balancing using SMOTE. |
| `Final_use_model.ipynb` | Loads the saved model and performs predictions on new data. |

---

## 🔧 Features

- 🔊 **Speech-to-Text** using AssemblyAI API with speaker labels.
- 🌐 **Web Scraping** using `requests` and `BeautifulSoup`.
- 🧹 **Text Preprocessing**: tokenization, stopword removal, lemmatization (NLTK).
- ⚖️ **Dataset Balancing** using `SMOTE` to handle class imbalance.
- 🤖 **Model Training**: SVM, Naive Bayes, Logistic Regression, etc.
- 💾 **Model Saving & Reuse** with `joblib`.

---

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
