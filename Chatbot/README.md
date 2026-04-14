# Basic Chatbot

## 📌 Description

This is a simple **NLP-based chatbot** built using Python.  
It uses Natural Language Processing techniques like tokenization and stemming to understand user input and respond using predefined patterns stored in `data.py`.  
The chatbot is rule-based and does not use machine learning models.

---

## ✨ Features
- Handles user greetings (hello, hi, hey, etc.)
- Responds to farewells (bye, good night, etc.)
- Supports small talk conversations
- Answers basic questions
- Uses NLP techniques (tokenization + stemming)
- Randomized responses for natural interaction
- Fallback response for unknown inputs

---

## 🛠️ Technologies Used
- Python 🐍
- NLTK (Natural Language Toolkit)
- Porter Stemmer (for word normalization)
- Random module

---

## ▶️ How to Run

1. Clone the repository
2. Navigate to the project folder:
```
cd Chatbot
```
3. Install required library:
```
pip install nltk
```
4. Run the chatbot:
```
python chatbot.py
```

---

## 🔮 Future Improvements

- Add Machine Learning-based responses 🤖
- Use advanced NLP (lemmatization instead of stemming)
- Improve accuracy using TF-IDF or cosine similarity
- Add GUI using Tkinter or web interface (Flask/HTML)
- Add speech recognition and voice response 🎤
- Store chat history in a database

