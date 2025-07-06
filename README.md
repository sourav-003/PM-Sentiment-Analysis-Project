# 🗣️ Sentiment Analysis of PM Narendra Modi's Speech (No Confidence Motion, 2023)

This project performs sentiment analysis on the speech delivered by **Prime Minister Narendra Modi** in the **Lok Sabha during the No Confidence Motion debate** in 2023.

📺 **Speech Source**: [Watch on YouTube](https://www.youtube.com/watch?v=WaRsrCPS0rg)  
📝 **Transcript**: Manually extracted and cleaned from the official government text (see `speech.txt`)

---

## 📌 Objective

The goal is to analyze the language and tone used in the Prime Minister's speech using Natural Language Processing (NLP) techniques. This involves:
- Breaking down the speech into individual words
- Cleaning and preprocessing the text
- Classifying words into **positive**, **negative**, or **neutral** sentiment
- Visualizing frequent sentiment words using charts and word clouds

---

## 🛠️ Tech Stack and Tools

- **Python 3.x**
- **NLTK** (for tokenization, stopword removal, lemmatization, sentiment scoring)
- **Matplotlib** (for static plots)
- **Plotly Express** (for interactive bar plots)
- **WordCloud** (for visual word clouds)
- **Jupyter Notebook**

---

## 📊 Methodology

1. **Text Preprocessing**  
   - Converted text to lowercase  
   - Removed punctuation and stopwords  
   - Applied lemmatization using `WordNetLemmatizer`

2. **Sentiment Classification**  
   - Used `SentimentIntensityAnalyzer` from NLTK (VADER)
   - Each word scored and labeled as:
     - Positive: compound score > 0.1  
     - Negative: compound score < -0.1  
     - Neutral: -0.1 ≤ score ≤ 0.1

3. **Visualization**  
   - Bar plots for Top 20 words in each sentiment category (positive, negative, neutral)
   - Word clouds to visually represent frequency-weighted sentiment words

---

## 📁 Project Structure

