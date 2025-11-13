# 🧠 GenAI & LLM Capstone Project — Text Preprocessing and Vectorization

This project is developed as part of the **Generative AI & LLM Course Capstone Project**.  
It focuses on **text preprocessing**, **EDA**, and the implementation of various **vectorization and embedding techniques** to prepare text data for machine learning and deep learning models.

---

## 📂 Dataset
- **Name:** Synthetic Rural Health Data  
- **File:** `synthetic_rural_health_data.xlsx`  
- **Description:** Contains information about patients, including symptoms and health conditions.  
- The text column (`symptoms`) was used for NLP preprocessing.

---

## 🎯 Project Objectives
1. Perform **Text Cleaning** (punctuation removal, stopword removal, stemming)
2. Conduct **Exploratory Data Analysis (EDA)**
3. Apply multiple **vectorization techniques:**
   - Bag of Words (BoW)
   - TF-IDF
   - Word2Vec
   - GloVe
   - BERT embeddings
4. Build and evaluate ML models on the processed data
5. Compare embedding methods based on model performance

---

## 🧹 Text Preprocessing Steps
- Lowercasing text  
- Removing punctuation, digits, and special characters  
- Removing stopwords  
- Stemming using NLTK Porter Stemmer  
- Creating a clean text column for further vectorization  

---

## 📊 Methods Implemented
| Technique | Library Used | Purpose |
|------------|--------------|----------|
| **Bag of Words** | `CountVectorizer` | Convert text to frequency matrix |
| **TF-IDF** | `TfidfVectorizer` | Capture word importance |
| **Word2Vec** | `gensim.models.Word2Vec` | Learn word embeddings |
| **GloVe** | Pretrained Embeddings | Generate vector representations |
| **BERT** | `transformers` | Contextual embeddings using transformer models |

---

## ⚙️ Tools & Libraries
- Python 3.10+
- Pandas, NumPy
- NLTK, re
- Scikit-learn
- Gensim
- Transformers (HuggingFace)
- Matplotlib, Seaborn

---

## 🏁 Results
- Vectorization and embedding methods successfully compared.
- Pretrained BERT embeddings produced the highest performance.

---

## 🚀 How to Run
1. Open in Google Colab  
2. Upload the dataset (`synthetic_rural_health_data.xlsx`)  
3. Run all cells sequentially  

---

## 👩‍💻 Author
**Mehvish Yousuf**  
B.Tech CSE | Sharda University  
Class Project
