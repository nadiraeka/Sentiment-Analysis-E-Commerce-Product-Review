## Sentiment Analysis E Commerce Product Review Using BERT

### 📄 Description
<div align="justify">

This project explores **sentiment analysis on product reviews from Indonesian E-commerce platforms** using a fine-tuned **BERT** model. The goal is to automatically classify whether a review is **positive or negative**. With over 11,000 reviews collected from platforms like Tokopedia, Shopee, Lazada, and others, the project focuses on turning raw text into valuable sentiment insights. Reviews were originally written in Indonesian but translated into English to match the BERT model’s training language. The text was then converted to lowercase, filtered from punctuation, emoji, and stopwords. The reviews were divided into training, validation, and testing groups. The model used here is a pre-trained BERT designed to understand context in language. It was adjusted (fine-tuned) specifically for this task by training it over three rounds using the labeled review data. The final model achieved **94% accuracy** in classifying sentiments, with balanced performance across both positive and negative categories. The results were evaluated using metrics like precision, recall, and F1-score, and visualized through a **confusion matrix** and **classification report**. Additional **word clouds** were created to show the most frequent terms found in positive vs negative reviews.

</div>

### 🛠 Tools & Libraries
- Python, Jupyter Notebook
- `pandas`, `numpy` for data preprocessing  
- `re`, `string`, `nltk` for text cleaning  
- `transformers`, `datasets`, `torch`, `sklearn` for modeling and evaluation  
- `BERT` (bert-base-uncased) from Hugging Face Transformers  
- `matplotlib`, `seaborn`, `wordcloud` for visualization  
 

<div align="center">
  <img src="https://github.com/user-attachments/assets/9ebc2cc9-db2b-47a3-bec8-c3bca0305cdd" width="400" />
  <img src="https://github.com/user-attachments/assets/25272aea-6359-4d22-9ee7-69991842ab2b" width="400" />
  <img src="https://github.com/user-attachments/assets/0b1dbe1b-78e7-4da4-9a15-700d31494f03" width="400" />
  <img src="https://github.com/user-attachments/assets/a3f3a02f-f2a8-46a1-a7aa-3673c8adbc3c" width="400" />
  <img src="https://github.com/user-attachments/assets/49975e8a-eb1e-48e8-b03b-37be511d0481" width="400" />
</div>
