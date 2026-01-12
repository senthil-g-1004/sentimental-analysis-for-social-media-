# AI-Based Sentiment Analysis Dashboard

An interactive web application built using **Streamlit** that performs sentiment analysis on text data using **NLTK’s VADER** algorithm and generates AI-driven insights using **LLaMA (Groq API)**.

---

## 🚀 Features

- Upload CSV files containing textual data
- Perform sentiment analysis (Positive, Negative, Neutral)
- Compute compound sentiment scores using VADER
- Visualize sentiment distribution with charts
- Generate AI-based insights using LLaMA via Groq API
- Simple and user-friendly web interface

---

## 🧠 How It Works

1. User uploads a CSV file containing a `text` column  
2. VADER analyzes each text and assigns sentiment scores  
3. Sentiments are classified based on compound score thresholds  
4. Sentiment distribution is visualized using a pie chart  
5. LLaMA model provides high-level insights on overall sentiment  

---

## 🛠️ Tech Stack

**Python | Streamlit | NLTK (VADER) | Pandas | Matplotlib | Seaborn | LangChain | Groq LLaMA**

---

## 📂 CSV File Format

The uploaded CSV file must contain a column named:

```text
text
