# 📧 Spam Email Detection using LSTM

This project uses Natural Language Processing (NLP) and Deep Learning (LSTM) to classify emails as **spam** or **non-spam (ham)**. It’s built with TensorFlow and Keras, and demonstrates how to process text, tokenize data, use embedding layers, and train an LSTM model for binary classification.

---

## Features

- Preprocessing and tokenization of email text
- Word cloud visualization of spam vs. non-spam content
- Word embeddings using Keras `Embedding` layer
- LSTM for sequential context understanding
- Binary classification using a sigmoid output
- Accuracy and loss tracking using validation data

---

## Technologies Used

- Python 3
- TensorFlow / Keras
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn

---

## Model Architecture
- Input → Embedding Layer → LSTM Layer → Dense Layer (ReLU) → Dense Layer (Sigmoid) → Output

