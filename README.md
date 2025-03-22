# 📰 Fake News Detection

## Project Overview
This project is designed to detect **fake news** using a machine learning model. It leverages **Natural Language Processing (NLP)** techniques to classify news articles as **"Fake" or "Real"**. The user-friendly interface, built with **Gradio**, allows users to input news text and receive immediate predictions.

---

## Features
✔ **Interactive Text Input** – Users can input a news article's text directly into the web interface.  
✔ **Real-time Prediction** – The system predicts whether the news is fake or real, displaying results as percentages.  
✔ **Visual Indicators** – A **green checkmark ✅** for real news and a **red cross ❌** for fake news.  

---

## Tech Stack
- **Python** – Primary programming language.  
- **TensorFlow/Keras** – For building and training the **LSTM model**.  
- **NLP Techniques** – Tokenization, Word Embeddings, Sequence Padding.  
- **Gradio** – For creating an **interactive web interface**.  

---

## Model Description
The backend model is an **LSTM (Long Short-Term Memory) network**, trained on a comprehensive dataset of **fake and real news articles**. LSTMs are effective for text classification due to their ability to **retain contextual meaning** over long sequences.

### Model Training
1. **Dataset Preparation** – Cleaned and preprocessed news articles.
2. **Tokenization & Word Embeddings** – Converted text into numerical format using embeddings.
3. **LSTM Network** – Built and trained the model with an **80-20 train-test split**.
4. **Evaluation** – Achieved **high accuracy (above 95%)** in classification.

---

