# Medical Text Classification System Using NLP and Deep Learning

## 📌 Project Overview

The **Medical Text Classification System** is an NLP and Deep Learning-based project designed to automatically categorize unstructured healthcare queries into predefined medical categories.

The system processes informal medical queries and classifies them into five categories:

- Symptoms
- Diseases
- Diagnosis
- Medications
- Treatments

It aims to support healthcare platforms, medical chatbots, and telemedicine applications by organizing patient queries and helping route them to the appropriate doctors or departments.

**Note:** This system is designed only for text classification and does not provide medical diagnosis or medical advice.

## 🎯 Objectives

- Automatically classify health-related text queries.
- Process unstructured and informal medical language.
- Apply NLP techniques for text preprocessing and normalization.
- Use deep learning and contextual text representations for classification.
- Reduce manual query categorization and improve response efficiency.

## ⚙️ Technologies Used

- Python
- Natural Language Processing (NLP)
- Deep Learning
- BERT (Bidirectional Encoder Representations from Transformers)
- LSTM / Bi-LSTM
- CNN
- TF-IDF
- Word2Vec
- Machine Learning Libraries

## 🔍 Methodology

1. **Data Collection:** Collect medical queries from healthcare-related datasets.
2. **Data Preprocessing:** Clean text by removing unnecessary symbols, URLs, punctuation, and noise.
3. **Text Normalization:** Apply tokenization and normalization techniques.
4. **Feature Extraction:** Represent text using TF-IDF, Word2Vec, and BERT embeddings.
5. **Model Training:** Train deep learning models for medical text classification.
6. **Model Evaluation:** Evaluate using accuracy, precision, recall, and F1-score.
7. **Prediction:** Classify new medical queries into the appropriate category.

## 🧠 Model Architecture

The proposed system uses BERT-based contextual representations and deep learning classification techniques.

BERT processes medical queries using bidirectional contextual learning. The extracted representation is passed through classification layers to predict the appropriate medical category.

## 💡 Example

**Input:**
"I have a headache and fever for 2 days. What medicine should I take?"

**Expected Output:**
- Category: Symptoms / Medications

## 🚀 Applications

- Healthcare platforms
- Medical chatbots
- Telemedicine applications
- Online healthcare support systems
- Medical query routing systems

## 🔮 Future Enhancements

- Multilingual medical query classification.
- Improved classification using advanced transformer models.
- Integration with real-time healthcare applications.
- Expansion of medical query categories.
- Improved performance using larger medical datasets.

## 👩‍💻 Author

**Shaik Nawaziya**

B.Tech – Computer Science and Technology

Madanapalle Institute of Technology & Science (MITS)

## 📄 Disclaimer

This project is developed for educational and research purposes. It classifies medical text queries and is not intended to replace professional medical advice, diagnosis, or treatment.
