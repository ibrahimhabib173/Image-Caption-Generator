
# 🖼️ Image Caption Generator using Deep Learning

## 📌 Overview
This project focuses on building an **AI-powered image captioning system** capable of generating human-like descriptions for input images. By combining **Computer Vision** and **Natural Language Processing (NLP)**, the model learns to extract visual features from images and map them to meaningful textual captions.

---

## 🎯 Objectives
- Generate accurate and descriptive captions for images provided by users.
- Leverage **CNNs** for feature extraction and **LSTM networks** for language modeling.
- Explore **figurative/semantic captioning**, not just literal object recognition.
- Provide a step toward bridging the gap between **vision** and **language understanding**.

---

## 📊 Dataset
- The dataset consists of **~8,000 different images**.
- Each image has **3–5 textual captions** describing its content.
- Captions were preprocessed (stopword removal, lemmatization, tokenization, lowercasing, cleaning).
- Images were processed through a **VGG16 CNN** pretrained model to extract deep visual features.

---

## ⚙️ Methodology

### 🔹 Preprocessing
- **Text:** Stopword removal, lemmatization, tokenization, special character cleaning.
- **Images:** Feature extraction using **VGG16 CNN**.

### 🔹 Model Architecture
- **Encoder:** CNN (VGG16) for visual feature extraction.
- **Decoder:** LSTM (Long Short-Term Memory) for sequence generation.
- **Word Embedding:** Learned vector representation of captions.
- **Activation Functions:** ReLU (hidden layers), Softmax (output layer).
- **Optimizer:** Adam.
- **Regularization:** Dropout layers to reduce overfitting.

### 🔹 Training
- Dataset split into training & testing sets.
- During training, the model learns to align extracted features with caption text.

### 🔹 Testing
- Inference stage: input image → extracted features → generated caption based on learned mappings.

---

## 🛠 Technologies Used
- **Programming Language:** Python
- **Frameworks & Libraries:** TensorFlow, Keras, Pandas, NumPy, Pickle, Tqdm
- **Computer Vision:** CNN (VGG16 pretrained)
- **NLP & DL:** LSTM, RNN, Word Embeddings

---

## 📈 Results
- Successfully generated descriptive captions for test images.
- Demonstrated the integration of **Computer Vision + NLP** in a unified deep learning pipeline.
- Model performance improved with preprocessing and dropout, reducing overfitting.

---

## 🚀 Future Work
- Expand dataset to improve accuracy and handle diverse image contexts.
- Experiment with **Transformer-based models** (e.g., BERT, Vision Transformers).
- Add support for **multilingual captions**.
- Deploy as a **web or mobile application** with a user-friendly interface.

---

## 👨‍💻 Team Members
- Ibrahim Mousa El Sayed Habib
- Hazem Refai Mohamed Refai (Team Leader)
- Khaled Ahmed Slama Eldifrawy
- Eslam Khaled Soliman Gad
- Ahmed Samer Eid Abdulhamid
- Radwa Walied Rabie Gad
- Rawda Walied El Bassiouni
