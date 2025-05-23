# 💬 Sentiment Analysis on Bank BCA Customer Reviews

This project performs **sentiment analysis** on customer reviews related to **Bank BCA** using advanced **Natural Language Processing (NLP)** techniques. The goal is to uncover customer perceptions, identify common sentiments, and provide actionable insights to help improve banking services.

---

## ✨ Key Features

#### 📝 Text Preprocessing
- Lowercasing and punctuation removal  
- **Stemming** with [Sastrawi](https://github.com/sastrawi/sastrawi) (Indonesian stemmer)  
- Custom stopword removal (NLTK + additional list)

####  🤖 Fine-Tuned BERT Model
- Pretrained **IndoBERT** model from [Hugging Face Transformers](https://huggingface.co/)  
- Fine-tuned specifically for **Indonesian** customer reviews  
- Powered by `BertForSequenceClassification`

####  📊 Data Visualization
- Sentiment distribution charts  
- Word clouds to highlight frequently used terms

####  📈 Performance Metrics
- **Accuracy**: 92%  
- **Weighted F1-score**: 0.92  
- Also includes **precision** and **recall** for each class

####  Deployment

**Login Page**  
![Login Page](https://github.com/chellecia/BCA-Customer-Review-Analysis/blob/main/Login%20Page.png)

**Sentimen Page (Home Page)**  
![Sentimen Page](https://github.com/chellecia/BCA-Customer-Review-Analysis/blob/main/Sentiment%20Page.png)

**Result Page**  
![Result Page](https://github.com/chellecia/BCA-Customer-Review-Analysis/blob/main/Hasil%20Sentiment.png)


####  🚀 End-to-End Pipeline
From raw reviews to a deployed system:
- Preprocessing → EDA → Tokenization → Model Training → Evaluation → Deployment

---

## 📂 Project Workflow  
```mermaid
graph TD
    A[Raw Reviews] --> B[Text Cleaning]
    B --> C[EDA & Visualization]
    C --> D[Tokenization]
    D --> E[Model Training]
    E --> F[Evaluation]
    F --> G[Deployment]



 
