# Geographical Understanding of Twitter Health Topics Using Topic Modeling 🩺🌍

### A machine learning-based approach to analyze health-related topics from Twitter data, providing insights into global health trends.

---

## 📋 Overview

With the growing prevalence of health-related discussions on Twitter, this project explores the use of **Natural Language Processing (NLP)** and **Topic Modeling Algorithms** to identify and analyze trends in global health topics. By leveraging unstructured tweet data, the project extracts and visualizes insights, enabling a better understanding of public health discourse.

---

## 🔍 Key Features
- **Real-Time Data**: Extracts live tweets using the **Twitter API**.
- **Advanced Preprocessing**: Implements techniques like tokenization, stop-word removal, and lemmatization.
- **Topic Modeling**: Uses **Latent Dirichlet Allocation (LDA)** for clustering and identifying key topics.
- **Visualization**: Generates word clouds and topic distributions for easy interpretation.
- **Custom Query**: Allows users to input location and query terms to extract specific health-related tweet data.

---

## 📊 Methodology
1. **Data Collection**:
   - Live tweets are extracted using the **Twitter Developer API**.
   - Input parameters: Location and query keywords.

2. **Data Preprocessing**:
   - Stop-word removal, tokenization, and lemmatization.
   - Conversion of text into numerical vectors using **TF-IDF** and **Count Vectorizer**.

3. **Topic Modeling**:
   - Application of the **LDA algorithm** to identify dominant topics from the tweets.

4. **Visualization**:
   - Word clouds and graphical representations of the identified topics.

---

## 📂 Project Structure
- **Datasets**:
  - No static datasets. Data is collected live from Twitter based on user inputs.
- **Algorithms**:
  - LDA, TF-IDF, and Count Vectorizer for topic extraction.
- **Tools and Libraries**:
  - Python, Tweepy, Scikit-learn, Matplotlib, Word Cloud, NLTK.

---

## 🛠 System Requirements
**Hardware**:
- OS: Windows/Linux
- Processor: Minimum Intel i3
- RAM: 4 GB or more
- Storage: 256 GB SSD

**Software**:
- Python 3.7+
- Anaconda/Jupyter Notebook
- Required Python libraries:
  - `tweepy`, `nltk`, `scikit-learn`, `matplotlib`, `wordcloud`

---

## 📊 Results
- Analyzed over **40 major cities** for health-related tweet data.
- Successfully identified trends and key topics across various health issues.
- Provided actionable insights through **word clouds** and topic distributions.

---

## 🌟 Future Enhancements
- Incorporate stronger feature extraction methods for higher accuracy.
- Build an intuitive user interface (UI) for better interaction.
- Use larger datasets for improved topic modeling.
- Extend the model for real-time monitoring and trend prediction.

---

## 📚 References
- **Dataset**: Generated live using Twitter API.
- **Related Research**:
  - [Topic Modeling for Health Research](https://doi.org/10.1186/s40537-018-0145-4)
  - [Latent Dirichlet Allocation on Twitter Data](https://doi.org/10.1145/1964858.1964870)

---

## 🤝 Contributors
- **Parakala Venkata Anirudh** - [anirudhparakala@gmail.com](mailto:anirudhparakala@gmail.com)
- Podduturi Hruthvik Reddy
- Shaik Sohel
- Thunuguntla Srichakranath

---

## 📧 Contact
For inquiries or collaborations, contact **Parakala Venkata Anirudh** at [anirudhparakala@gmail.com](mailto:anirudhparakala@gmail.com).

---

### 🧐 Fun Fact
> Social media is faster than traditional media, making it a rich source of live health-related information!
