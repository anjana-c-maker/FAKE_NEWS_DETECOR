

# **📰 Fake News Detection Using LSTM**  

## **📌 Project Overview**  
This project focuses on detecting **fake news articles** using **Natural Language Processing (NLP) and Deep Learning**. The model is trained on a dataset containing **real and fake news articles** and classifies them based on textual content.  

## **📂 Dataset**  
The dataset consists of two files:  
- **Fake.csv** → Contains fake news articles  
- **True.csv** → Contains real news articles  

Each file includes:  
- **Title** → News headline  
- **Text** → Full news article content  
- **Subject** → News category  
- **Date** → Publication date  

## **🔧 Installation & Setup**  
1️⃣ Install the necessary libraries (TensorFlow, Keras, NLTK, Pandas, Scikit-learn, etc.).  
2️⃣ Download the dataset and place it in your working directory.  
3️⃣ Run the preprocessing script to clean the text and prepare it for training.  

## **📌 How It Works**  
- **Preprocessing:**  
  - Remove special characters and numbers  
  - Convert text to lowercase  
  - Remove stopwords  
  - Tokenize words and convert them into numerical sequences  

- **Model Architecture:**  
  - Uses **LSTM (Long Short-Term Memory) networks** for sequential text analysis  
  - Embedding layer converts words into numerical vectors  
  - LSTM layers capture long-term dependencies in text  
  - Final classification layer outputs whether the news is **real or fake**  

## **🚀 Model Training & Evaluation**  
- The model is trained on labeled **fake and real news articles**.  
- It is evaluated based on **accuracy, precision, recall, and F1-score**.  
- The **confusion matrix** helps visualize correct and incorrect predictions.  

## **📊 Performance Metrics**  
- **High accuracy (98-99%)** in detecting fake news.  
- The classification report provides insights into precision and recall for both real and fake news.  
- The confusion matrix shows how many articles were classified correctly or incorrectly.  

## **🛠️ Fake News Prediction**  
- Once trained, the model can analyze a new article and predict whether it is **real or fake**.  
- It processes the text and assigns a probability score to determine authenticity.  

## **📌 Next Steps & Improvements**  
✅ Improve accuracy using **Bidirectional LSTMs or Transformer-based models** (BERT, GPT).  
✅ Implement **attention mechanisms** to focus on important words in a news article.  
✅ Deploy the model as a **web application** using **Flask or Streamlit**.  
✅ Integrate with **fact-checking APIs** to validate sources dynamically.  

## **📜 License**  
This project is open-source and can be used for educational and research purposes.  

