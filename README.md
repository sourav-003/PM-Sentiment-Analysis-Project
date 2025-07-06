# 🗣️ Sentiment Analysis of PM Narendra Modi's Speech (No Confidence Motion, 2023)

This project performs sentiment analysis on the speech delivered by **Prime Minister Narendra Modi** in the **Lok Sabha during the No Confidence Motion debate** in 2023.

📺 **Speech Source**: [Watch on YouTube](https://www.youtube.com/watch?v=WaRsrCPS0rg)  
📝 **Transcript**: Extracted from official sources — see `speech.txt`.

---

## 📌 Objective

The objective is to analyze the **sentiment polarity** (positive, negative, neutral) of PM Modi's speech using NLP techniques. The project:
- Tokenizes and cleans the speech text
- Scores individual words using VADER sentiment analysis
- Categorizes words into sentiment buckets
- Visualizes high-frequency words across sentiment types

---

## 🛠️ Tech Stack and Tools

- **Python 3.x**
- **NLTK**: Tokenization, stopwords, lemmatization, VADER sentiment analysis
- **Matplotlib**: Static plots
- **Plotly Express**: Interactive visualizations
- **WordCloud**: Visual word frequency clouds
- **Jupyter Notebook**: Code development and execution

---

## 📊 Methodology

1. **Text Preprocessing**
   - Removed punctuation
   - Converted text to lowercase
   - Tokenized into words
   - Removed English stopwords
   - Applied lemmatization with `WordNetLemmatizer`

2. **Sentiment Analysis**
   - Used NLTK's `SentimentIntensityAnalyzer` (VADER)
   - Each word was scored and labeled as:
     - Positive: compound score > 0.1
     - Negative: compound score < -0.1
     - Neutral: -0.1 ≤ compound score ≤ 0.1
   - Calculated overall average sentiment

3. **Visualization**
   - Top 20 frequent words for each sentiment category (positive, negative, neutral)
   - Bar plots using Plotly
   - Word clouds using Matplotlib

---

## 📁 Project Structure

    Sentiment Analysis/
    ├── speech.txt                  # Transcript of the speech
    ├── link.txt                    # YouTube link to the original speech
    ├── Sentiment Analysis.ipynb    # Jupyter notebook with full analysis
    ├── positive_plot.png
    ├── negative_plot.png
    ├── neutral_plot.png
    ├── sentiment_wordclouds.png
    ├── positive_wordcloud.png
    └── README.md                   # Project documentation

---

## 📈 Key Insights

- The **overall sentiment** of the speech was **neutral to positive**.
- Most frequent words in the **positive category** were related to development, trust, progress, and youth.
- Negative sentiment words appeared when criticizing the opposition or discussing sensitive national issues.
- Word clouds and bar plots provided intuitive visualization of speech tone.

---

## ✅ Future Enhancements

- Sentence-level sentiment tracking to analyze speech tone progression
- Named Entity Recognition (NER) to extract named topics and people
- Timeline-based sentiment comparison with other political leaders
- Topic modeling to uncover latent themes (e.g., LDA)

---

## 📬 Contact

**Sourav Kumar**  
📧 Email: souravmail003@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/sourav-kumar-5814341b8)

---

> ⚠️ *This analysis is for educational and research purposes. It does not promote or oppose any political ideology.*
