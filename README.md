# 💙 EmpathyBot  
**Sentiment-Driven Chatbot with Advanced RAG and Few-Shot Prompt Engineering**

---

## 📌 Overview  
EmpathyBot is a prototype chatbot that:  
- Detects **emotions** in user messages using a pre-trained DistilBERT model.  
- Retrieves **empathetic responses** from a response corpus using **RAG (FAISS + SentenceTransformers)**.  
- Uses **few-shot prompt engineering** to make responses more natural.  
- Provides a simple **Streamlit interface** for real-time chat.  

⚠️ **Disclaimer:** *This bot is not a therapist; please seek professional help for serious issues.*  

---

## 🚀 Features  
- Emotion detection for **9 emotions**:  
  *sadness, joy, anger, fear, love, surprise, disgust, optimism, neutral*  
- Multiple empathetic response templates per emotion.  
- Retrieval-Augmented Generation (RAG) for scalable, context-aware replies.  
- Streamlit-based web UI with chat history.  
- Ready-to-deploy on **Streamlit Cloud** or with **ngrok** for Colab demos.  

---

## 🧠 Models Used  
- **Emotion Detection:** [`bhadresh-savani/distilbert-base-uncased-emotion`](https://huggingface.co/bhadresh-savani/distilbert-base-uncased-emotion)  
- **Embeddings (RAG):** [`sentence-transformers/all-MiniLM-L6-v2`](https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2)  

---

## 📊 Dataset  
- **Emotion Dataset:** [tweet_eval → emotion](https://huggingface.co/datasets/cardiffnlp/tweet_eval)  
- **Responses Corpus:** Custom empathetic templates expanded to **9 emotions** (≈ 60 responses).  

---

link of the demo:
https://drive.google.com/drive/folders/1ia6gARmi0S169AWk8qF3zLlSD6FORM7U?usp=sharing
