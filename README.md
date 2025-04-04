
# 🧠 Sentiment Analysis Pipeline with Web Scraping & Speech-to-Text  
A Multimodal NLP Framework for Real-Time Emotion & Opinion Mining  

![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)  
![License](https://img.shields.io/badge/License-MIT-lightgrey.svg)  
![Made With ❤️](https://img.shields.io/badge/Made%20with-❤️-red.svg)

---

## 📌 Overview  

This project demonstrates a powerful Natural Language Processing (NLP) pipeline that seamlessly integrates **speech recognition**, **web scraping**, and **machine learning-based sentiment analysis**. Whether analyzing real-time spoken data or extracting emotion from text-based web content, this project provides a modular and extensible framework for **opinion mining and affective computing**.

---

## 📂 Project Structure

| File | Description |
|------|-------------|
| `Dataset_Creation.ipynb` | Converts speech to text using the AssemblyAI API and saves transcripts with speaker identification. |
| `Web_scraping.ipynb` | Scrapes news articles, headlines, or website content for further text-based sentiment classification. |
| `Speech_Model_newnew.ipynb` | Handles full NLP pipeline including text cleaning, vectorization, dataset balancing with SMOTE, and sentiment model training. |
| `Final_use_model.ipynb` | Loads the trained model and applies it to new, unseen inputs (text or speech). |

---

## 🔍 Key Features  

- 🎙️ **Speech-to-Text Transcription**  
  → Converts audio files to text using [AssemblyAI](https://www.assemblyai.com/) with optional speaker diarization.

- 🌍 **Web Scraping Module**  
  → Pulls live text data from the web using `requests` and `BeautifulSoup`, enabling real-time sentiment monitoring.

- ✨ **Advanced Text Preprocessing**  
  → Includes tokenization, stopword removal, and lemmatization via NLTK.

- ⚖️ **Smart Dataset Balancing**  
  → Addresses class imbalance using `SMOTE` (Synthetic Minority Oversampling Technique).

- 🤖 **Machine Learning Models**  
  → Supports Logistic Regression, SVM, Naive Bayes, and more with cross-validation.

- 💾 **Model Persistence**  
  → Saves and loads trained models using `joblib` for efficient deployment and reuse.

---

## 🚀 Getting Started  

### 🔧 Installation

Clone this repository:

```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
```

Install dependencies via `requirements.txt`:

```bash
pip install -r requirements.txt
```

Or install manually:

```bash
pip install pandas numpy nltk scikit-learn imbalanced-learn matplotlib seaborn beautifulsoup4 requests
```

> 🗒️ Make sure to download necessary NLTK corpora (`stopwords`, `punkt`, etc.)

---

## 🛠️ Usage Guide  

### 1. **Transcribe Audio Files**  
Run `Dataset_Creation.ipynb` to convert audio into structured, labeled text.

### 2. **Scrape Web Content**  
Run `Web_scraping.ipynb` to collect external data for additional sentiment sources.

### 3. **Train the Sentiment Model**  
Use `Speech_Model_newnew.ipynb` for full preprocessing, vectorization, balancing, and model training.

### 4. **Predict New Sentiment**  
Use `Final_use_model.ipynb` to test your model on unseen samples or new recordings.

---

## 🧪 Example Applications

- 🎧 Call center emotion tracking  
- 🗞️ News sentiment analysis  
- 🎤 Interview tone analysis  
- 🔍 Public opinion monitoring  

---

## 📚 Dependencies

- `scikit-learn`
- `nltk`
- `imbalanced-learn`
- `beautifulsoup4`
- `requests`
- `matplotlib`, `seaborn`
- `joblib`

---

## 💡 Future Improvements

- Support for **video-based emotion recognition**
- Integration with **transformer models** (e.g., BERT, RoBERTa)
- Real-time deployment with **Streamlit** or **Flask**
- Multi-language sentiment support

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repo and submit a pull request. For major changes, please open an issue first to discuss your ideas.

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 💬 Contact

For questions or collaboration requests:  
📧 your.email@example.com  
🌐 [Your LinkedIn or Portfolio](https://yourwebsite.com)
