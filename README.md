# 💬 Sentiment Analysis on Bank BCA Customer Reviews

This project performs sentiment analysis on customer reviews related to **Bank BCA** using **Natural Language Processing (NLP)** techniques. The goal is to uncover customer perceptions, identify common sentiments, and provide actionable insights to help improve banking services.

---

## ✨ Key Features

- ✅ Preprocessing and cleaning of unstructured review text  
- 🤖 Sentiment classification using a pretrained **BERT** model from Hugging Face  
- 📊 Data visualization to highlight trends and insights  
- 📈 Evaluation using **accuracy**, **precision**, **recall**, and **F1-score**  
- 🚀 End-to-end pipeline from data cleaning to model deployment

---

## 📂 Project Workflow  
![Workflow](https://github.com/chellecia/BCA-Customer-Review-Analysis/blob/main/FLowchart.png)

---

### 1. Data Loading & Preprocessing
- Load review dataset
- Clean and normalize text:
  - Lowercasing, punctuation removal
  - Stemming using **Sastrawi**
  - Stopword removal (custom + NLTK)
- Label mapping: assign sentiment classes (e.g., positive, neutral, negative)
- Split data into **training, validation, and test sets** (80:10:10)

---

### 2. Exploratory Data Analysis (EDA)
- Visualize distribution of sentiments and review lengths  
- Generate word clouds to identify dominant words  
  ![Word Cloud](https://github.com/chellecia/BCA-Customer-Review-Analysis/blob/main/word%20cloud%20BCA.png)

---

### 3. Tokenization
- Tokenize text using **`BERT tokenizer`** from Hugging Face Transformers  
- Pad and truncate sequences to match model input size  

---

### 4. Model Building
- Fine-tune **`BertForSequenceClassification`** for sentiment classification  
- Define training pipeline using `Trainer` and `TrainingArguments`

---

### 5. Model Training & Evaluation
- Train model with training and validation sets  
- Evaluate model using:
  - Accuracy
  - Precision
  - Recall
  - F1-score  
  ![Classification Report](https://github.com/chellecia/BCA-Customer-Review-Analysis/blob/main/Classification%20report.png)

---

### 6. Deployment
**Login Page**
![https://github.com/chellecia/BCA-Customer-Review-Analysis/blob/main/Login%20Page.png)

 **Sentimen Page** 
![https://github.com/chellecia/BCA-Customer-Review-Analysis/blob/main/Sentiment%20Page.png)

**Result Page**
![https://github.com/chellecia/BCA-Customer-Review-Analysis/blob/main/Hasil%20Sentiment.png)

 
