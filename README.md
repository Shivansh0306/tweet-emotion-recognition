# Tweet Emotion Recognition

A deep learning–based NLP project that identifies emotions expressed in tweets using a Bidirectional LSTM model.

![Model Architecture]<img width="2816" height="1377" alt="image" src="https://github.com/user-attachments/assets/6f7d0b24-b135-4c27-b1e2-f48304a5641c" />


---

## Overview

Social media text is noisy and unstructured, making emotion detection challenging.  
This project converts raw tweets into structured emotional categories using a neural network–based pipeline.

---

## Emotions Classified

- Sadness  
- Love  
- Joy  
- Surprise  
- Anger  
- Fear  

---

## Methodology

1. **Text Preprocessing**
   - Remove URLs, user mentions, and special characters  
   - Clean and normalize text  

2. **Tokenization & Padding**
   - Convert words into numerical sequences  
   - Pad sequences to a fixed length  

3. **Deep Learning Model**
   - Embedding layer for word representation  
   - Bidirectional LSTM for context understanding  
   - Dense layer for feature extraction  
   - Softmax activation for multi-class emotion prediction  

---

## Tech Stack

- Python  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  
- Jupyter Notebook  

---

## Project Structure

```text
tweet-emotion-recognition/
│
├── notebooks/
│   └── Copy_of_Tweet_Emotion_Recognition_Learner7.ipynb
├── assets/
│   └── architecture.png
├── data/
├── src/
├── requirements.txt
├── README.md
└── .gitignore
