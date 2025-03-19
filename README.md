# Image-Caption-Generator

🖼 AI-Powered Image Caption Generator
A deep learning project that generates captions for images using CNN (ResNet50) for feature extraction and LSTM for text generation.

📌 Overview
This project combines computer vision and natural language processing (NLP) to generate meaningful captions for images.

🔹 CNN (ResNet50) extracts image features.
🔹 LSTM (Long Short-Term Memory) processes text and predicts captions.
🔹 Tokenization & Embedding for handling text data.
🔹 Keras & TensorFlow for deep learning.

🛠 Technologies Used
Python
TensorFlow / Keras
ResNet50 – Pre-trained CNN for image features
LSTM – Sequence model for text generation
Tokenization & Padding – NLP processing
Pandas, NumPy – Data handling
Matplotlib, PIL – Image processing
nltk – Text tokenization

🔍 How It Works?
1️⃣ Feature Extraction (CNN - ResNet50)
ResNet50 is a Convolutional Neural Network (CNN) trained on ImageNet.
It removes fully connected layers and extracts high-level features from images.
The extracted features are stored and used as input for the text model.

2️⃣ Caption Generation (LSTM)
LSTM (Long Short-Term Memory) is a type of recurrent neural network (RNN).
It learns contextual dependencies in text and predicts words sequentially.
The model takes image features + text sequence as input and predicts the next word.

3️⃣ Training Process
Tokenizes and encodes captions into sequences.
Uses one-hot encoding for the target words.
The LSTM model is trained with categorical cross-entropy loss.
