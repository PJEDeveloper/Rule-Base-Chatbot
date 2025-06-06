# Rule-Base-Chatbot
Chatbot

# 🤖 Rule-Based Conversational Chatbot (NLP with Wikipedia)

This chatbot is a lightweight, rule-based AI system that processes user input, detects greetings, and answers AI-related questions using real-time content scraped from Wikipedia. Built using classical NLP techniques with `TF-IDF`, `cosine similarity`, and `NLTK` lemmatization.

---

## 🔍 Overview

This chatbot can:
- Greet users using pattern matching
- Retrieve live AI-related content from [Wikipedia](https://en.wikipedia.org/wiki/Artificial_intelligence)
- Process natural language input and generate relevant responses
- Use `TF-IDF` similarity to identify the best-matching sentence from scraped text
- Simulate dialogue in a terminal-based loop

---

## 🧠 Key Features

- 🤝 Greeting response system with random reply generation
- 🧪 Tokenization, stopword filtering, lemmatization
- 📚 Real-time scraping of Wikipedia paragraphs
- 🧾 Cosine similarity on vectorized user inputs and paragraphs
- ❌ Graceful handling of unrecognized input
- 💬 Continuous dialogue until user exits

---

## 🗂 Project Structure

```
.
├── Rule_based_Conversational_Chatbot.ipynb   # Notebook version
├── Rule_based_Conversational_Chatbot.txt     # Full script version
```

---

## 🛠 Requirements

Install required libraries:

```bash
pip install nltk scikit-learn beautifulsoup4 lxml
```

Also ensure you have NLTK data:
```python
import nltk
nltk.download('punkt')
nltk.download('wordnet')
```

---

## 🚀 Running the Chatbot

In terminal or Python shell:
```bash
python Rule_based_Conversational_Chatbot.txt
```

In Jupyter Notebook:
```bash
Run all cells in Rule_based_Conversational_Chatbot.ipynb
```

---

## 💬 Example Dialogue

```
User: hey
AI Sciences: hello, how you doing

User: what is strong AI?
AI Sciences: strong AI is the representation of generalized human cognitive abilities in software...

User: thank you
AI Sciences: Most welcome
```

---

## 📚 Data Source

- Wikipedia: [Artificial Intelligence](https://en.wikipedia.org/wiki/Artificial_intelligence)
- Scraped on-the-fly using `urllib` + `BeautifulSoup`

---

## 📝 License

This project is licensed under the Apache 2.0 License.

---

> Created by Patrick Hill — AI Developer & NLP Practitioner  
> [LinkedIn](https://www.linkedin.com/in/patrick-hill-4b9807178/)
