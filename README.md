# Text Preprocessing 

## Project Overview

This project demonstrates the implementation of a complete **Text Preprocessing** pipeline using Python. The objective is to clean and transform raw text into a structured format suitable for Natural Language Processing (NLP) and Machine Learning applications.

The project performs multiple preprocessing operations such as lowercasing, tokenization, removal of URLs, numbers, punctuation, emojis, stop words, stemming, and lemmatization to produce clean and meaningful text.

---

## Objectives

- Read raw text from a text file.
- Convert text to lowercase.
- Perform sentence tokenization.
- Perform word tokenization.
- Remove URLs.
- Remove email addresses.
- Remove emojis.
- Remove numbers.
- Remove punctuation.
- Remove extra spaces.
- Remove stop words.
- Apply stemming.
- Apply lemmatization.
- Generate the final cleaned text.
- Save the cleaned text into a text file.

---

## Technologies Used

- Python
- Pandas
- Regular Expressions (re)
- NLTK

---

## Project Structure

```
Text-Preprocessing-From-Scratch/
│
├── Raw Text.txt
├── Cleaned_Text.txt
├── Text_Preprocessing.ipynb
├── README.md
```

---

## Dataset

The project uses a custom text dataset consisting of real-world notifications and messages such as:

- Traffic alerts
- Library reminders
- Emergency updates
- Flight notifications
- Community events
- Weather warnings
- Smart parking messages
- Fitness tracker reports

The dataset contains:

- Uppercase and lowercase letters
- Numbers
- URLs
- Emojis
- Punctuation
- Special characters

This makes it suitable for demonstrating various text preprocessing techniques.

---

# Text Preprocessing Pipeline

```text
                Raw Text
                    │
                    ▼
        Convert to Lowercase
                    │
                    ▼
       Sentence Tokenization
                    │
                    ▼
         Word Tokenization
                    │
                    ▼
             Remove URLs
                    │
                    ▼
         Remove Email Addresses
                    │
                    ▼
            Remove Emojis
                    │
                    ▼
            Remove Numbers
                    │
                    ▼
         Remove Punctuation
                    │
                    ▼
         Remove Extra Spaces
                    │
                    ▼
         Remove Stop Words
                    │
                    ▼
              Stemming
                    │
                    ▼
            Lemmatization
                    │
                    ▼
            Final Clean Text
```

---

# Raw Text vs Cleaned Text

| Raw Text | Cleaned Text |
|----------|--------------|
| **Traffic Alert: Heavy congestion detected near Central Bridge. Expected delay: 25 minutes. 🚦** | **traffic alert heavy congestion detected near central bridge expected delay minutes** |
| **Visit https://studentportal.edu to download your semester marksheet.** | **visit download semester marksheet** |
| **Your fitness tracker recorded 12,486 steps and burned 542 calories today. Great job! 💪** | **fitness tracker recorded steps burned calories today great job** |

---

# Before vs After Comparison

| Preprocessing Step | Before | After |
|--------------------|--------|-------|
| Lowercase | `Traffic Alert` | `traffic alert` |
| Remove URL | `https://studentportal.edu` | *(removed)* |
| Remove Numbers | `25 minutes` | `minutes` |
| Remove Punctuation | `Great job!` | `Great job` |
| Remove Emoji | `💪` | *(removed)* |
| Remove Stop Words | `to download your` | `download` |
| Final Output | `Traffic Alert: Heavy congestion detected near Central Bridge. Expected delay: 25 minutes. 🚦` | `traffic alert heavy congestion detected near central bridge expected delay minutes` |

---

## Features

- Reads raw text from a text file.
- Performs lowercase conversion.
- Performs sentence tokenization.
- Performs word tokenization.
- Removes URLs and email addresses.
- Removes emojis and special characters.
- Removes numbers and punctuation.
- Removes extra spaces.
- Removes stop words.
- Applies stemming.
- Applies lemmatization.
- Generates clean text suitable for NLP applications.

---

## Output

The project generates:

- Original text
- Lowercase text
- Sentence tokens
- Word tokens
- URL-free text
- Emoji-free text
- Number-free text
- Punctuation-free text
- Stop-word removed text
- Stemmed words
- Lemmatized words
- Final cleaned text

The cleaned output is saved as:

```
Cleaned_Text.txt
```

---

## Applications

This preprocessing pipeline can be used in:

- Sentiment Analysis
- Text Classification
- Spam Detection
- Chatbots
- Machine Translation
- Information Retrieval
- Document Classification
- Question Answering Systems
- Language Modeling

---

## Conclusion

This project successfully demonstrates a complete Text Preprocessing pipeline using Python. The raw text is transformed into clean and structured text through techniques such as lowercasing, tokenization, removal of URLs, emojis, numbers, punctuation, stop words, stemming, and lemmatization. The resulting cleaned text is suitable for a wide range of Natural Language Processing (NLP) tasks and serves as a strong foundation for developing advanced text analytics and machine learning applications.

---
