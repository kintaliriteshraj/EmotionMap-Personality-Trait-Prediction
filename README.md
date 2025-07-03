# EmotionMap: Mapping Personality Traits through AI-Powered Sentiment and Behavioral Analysis

## 🧠 Overview
**EmotionMap** is an AI-powered NLP project that predicts personality traits using textual data. Built on the MBTI (Myers–Briggs Type Indicator) framework, this system integrates sentiment analysis and behavioral intent classification to map psychological patterns from language. It provides insights into how emotions and behaviors are reflected through words.

---

## 📁 Dataset
- **MBTI Dataset (`mbti_1.csv`)**  
  Contains 8,600+ posts labeled with MBTI personality types (e.g., INFP, ENTJ).
  - 16 MBTI types based on 4 dimensions:
    - Introversion (I) / Extraversion (E)
    - Intuition (N) / Sensing (S)
    - Thinking (T) / Feeling (F)
    - Judging (J) / Perceiving (P)

---

## 🧰 Tech Stack & Tools
- **Domain**: Natural Language Processing (NLP)
- **Language**: Python  
- **Libraries**:  
  - `scikit-learn`, `LightGBM`, `XGBoost`, `SVM`, `Logistic Regression`  
  - `TextBlob` for sentiment analysis  
  - `Transformers (DistilBERT)` for behavioral classification  
  - `TF-IDF`, `Sentence Embeddings` for feature extraction  
  - `Matplotlib`, `Seaborn`, `WordCloud` for visualization  

---

## 🔍 Features
- 📊 **Sentiment Score Prediction** (Positive, Negative, Neutral)
- 🤖 **Behavioral Intent Detection** (e.g., Anxiety, Joy, Anger)
- 🧬 **MBTI Personality Type Prediction**
- 📈 **Model Accuracy Comparison**
- 🌐 **Interactive GUI/Website**
- 📌 **Visualizations**: Bar Charts, Word Clouds, Heatmaps, Pie Charts

---

## 🚀 Model Pipeline
1. **Text Preprocessing**  
   - Tokenization, Stopword Removal, Lemmatization  
2. **Feature Engineering**  
   - TF-IDF, Sentence Embeddings (DistilBERT)  
3. **Sentiment Analysis**  
   - Using TextBlob  
4. **Behavioral Classification**  
   - Using DistilBERT fine-tuned for emotion classes  
5. **Personality Prediction**  
   - Using ML Models (XGBoost, LightGBM, SVM, etc.)
6. **Evaluation**  
   - Accuracy, Precision, Recall, F1-Score (with `zero_division=1`)

---

## 📊 Results
- Achieved 60-70% accuracy across multiple models.
- Balanced prediction through **class weighting**.
- Improved performance with ensemble voting and sentence embeddings.

---

## 📌 Future Work
- Fine-tune transformer models on MBTI data  
- Enhance web interface with real-time predictions  
- Add multilingual support for wider applicability

---

## 📬 Contact
Feel free to contribute or connect for collaboration!  
📧 **Email**: [riteshrajkintali@gmail.com]  
🔗 **LinkedIn**: [https://www.linkedin.com/in/ritesh-raj-kintali-69a182318/]  
🌐 **GitHub**: [https://github.com/kintali-Ritesh-raj]

---

