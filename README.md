# Keyword_extraction_using_NLP
This project demonstrates how to extract keywords from raw text using three popular NLP techniques:

- 🔢 **TF-IDF (Term Frequency-Inverse Document Frequency)**
- 🧠 **RAKE (Rapid Automatic Keyword Extraction)**
- 🔗 **TextRank (Graph-based ranking algorithm)**

Developed entirely in **Google Colab** using Python and `nltk`, `rake_nltk`, `sklearn`, and `networkx`.
## 🚀 Project Objective

To compare different keyword extraction methods and understand how each performs on a sample corpus of text. This is useful for applications in:

- Search engine optimization
- Summarization tools
- Content classification
- Information retrieval

---

## 📊 Methods & Workflow

1. **Data Input:** Raw text string (manually input).
2. **Preprocessing:** Tokenization, stopword removal.
3. **TF-IDF:** Extracts top words based on statistical frequency.
4. **RAKE:** Extracts keyword phrases based on word co-occurrence and frequency.
5. **TextRank:** Builds a graph of words and uses PageRank to find the most relevant ones.

---

## 🛠️ Libraries Used

- `nltk`
- `rake_nltk`
- `sklearn`
- `networkx`
- `matplotlib`

---

## 📓 Notebook

---

## ✨ Output

Each method extracts a ranked list of keywords from the same input text.  
This helps visually and practically compare how different techniques interpret "importance."

---

