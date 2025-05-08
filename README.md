# 🧠 Ontology-Enhanced Subreddit Classifier

An intelligent text classification system that leverages semantic ontologies to categorize Reddit posts into appropriate subreddits, along with detailed and transparent explanations.

---

## 🚀 Overview

This project implements a **hybrid approach** to text classification by combining traditional machine learning techniques with a rich semantic ontology. The system classifies Reddit posts into five major categories:

- 🖥️ Technology  
- 🔬 Science  
- 🎮 Gaming  
- 🏋️ Fitness  
- 🎬 Movies

It also provides clear justifications for its decisions.

---

## 🔑 Key Features

### 🧱 Semantic Ontology Framework
- Hierarchical knowledge representation
- Includes categories, subgroups, concepts, and synonyms

### 🔁 Multi-method Approach
- Combines **TF-IDF**, **graph-based features**, and **word embeddings**

### 💬 Explainable Classifications
- Transparent, interpretable results
- Visual and textual evidence showing which terms influenced decisions

### 🖥️ Interactive Interface
- Real-time classification
- Displays reasoning paths and ontology references

### 🤖 BERT Enhancement (Optional)
- Alternative implementation using **BERT** for improved semantic understanding and context-aware classification

---

## 📦 Technologies Used and Dependencies

- NetworkX for ontology graphs
- spaCy and NLTK for NLP
- torch(for BERT variant)
- Streamlit or Gradio (for interface)
- Python 3.7+
- pandas, numpy, matplotlib
- gensim (Word2Vec)


---

## 📂 Dataset

Reddit posts scraped or sourced from categorized datasets for:
- Technology
- Science
- Gaming
- Fitness
- Movies

---

## 📈 How It Works

1. **Preprocessing**: Clean and tokenize Reddit post content.
2. **Feature Extraction**:
   - Graph-based semantic features via ontology lookup
   - Optional: Contextual embeddings with BERT
3. **Classification**: Hybrid model (SVM, Logistic Regression, or BERT-based) determines the subreddit.
4. **Explanation Generation**: Highlights ontology paths and word importance contributing to prediction.

## 📜 License

This project is licensed under the MIT License.

---

## 🤝 Contributing

Pull requests are welcome! If you’d like to contribute, please open an issue or contact the maintainer.

---



