# 📝 Text Preprocessing 

## 📖 Project Overview

This project demonstrates the implementation of a complete **Text Preprocessing Pipeline** using Python.

The objective is to clean and transform raw text data into a structured and meaningful format suitable for **Natural Language Processing (NLP)** and **Machine Learning applications**.

Raw text usually contains unwanted elements such as URLs, emojis, numbers, punctuation, special characters, and stop words. This project applies various preprocessing techniques to remove these unwanted elements and generate clean text.

The preprocessing pipeline includes:

- Lowercase conversion
- Sentence tokenization
- Word tokenization
- URL removal
- Email address removal
- Emoji removal
- Number removal
- Punctuation removal
- Stop word removal
- Stemming
- Lemmatization

---

# 🎯 Objectives

The main objectives of this project are:

✅ Read raw text from a text file.  
✅ Convert text into lowercase format.  
✅ Perform sentence tokenization.  
✅ Perform word tokenization.  
✅ Remove URLs.  
✅ Remove email addresses.  
✅ Remove emojis.  
✅ Remove numbers.  
✅ Remove punctuation.  
✅ Remove extra spaces.  
✅ Remove stop words.  
✅ Apply stemming.  
✅ Apply lemmatization.  
✅ Generate final cleaned text.  
✅ Save cleaned output into a text file.

---

# 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| 🐍 Python | Programming Language |
| 📚 NLTK | Natural Language Processing operations |
| 🔍 Regular Expressions (re) | Text pattern matching and cleaning |
| 🐼 Pandas | Data handling |

---

# 📂 Project Structure

```
Text-Preprocessing-From-Scratch/

│
├── 📄 Raw Text.txt
├── 📄 Cleaned_Text.txt
├── 📓 Text_Preprocessing.ipynb
└── 📘 README.md
```

---

# 📊 Dataset Description

The project uses a custom text dataset containing real-world notifications and messages.

### Dataset Examples:

🚦 Traffic alerts  
📚 Library reminders  
🚨 Emergency updates  
✈️ Flight notifications  
🌳 Community events  
🌩️ Weather warnings  
🅿️ Smart parking messages  
⌚ Fitness tracker reports  

The dataset contains:

- 🔤 Uppercase and lowercase letters
- 🔢 Numbers
- 🌐 URLs
- 📧 Email addresses
- 😀 Emojis
- ✏️ Punctuation
- 🔣 Special characters

This makes the dataset suitable for demonstrating different NLP preprocessing techniques.

---

# ⚙️ Text Preprocessing Pipeline

```
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

# 🔄 Preprocessing Techniques

## 🔡 Lowercase Conversion

Converts all uppercase letters into lowercase for consistency.

Example:

```
Before: Traffic Alert
After : traffic alert
```

---

## ✂️ Tokenization

### Sentence Tokenization
Divides text into individual sentences.

### Word Tokenization
Splits sentences into individual words.

Example:

```
Input:
Traffic alert detected

Output:
['traffic','alert','detected']
```

---

## 🌐 URL and Email Removal

Removes unwanted links and email addresses.

Example:

```
Before:
Visit https://studentportal.edu

After:
Visit
```

---

## 😀 Emoji Removal

Removes emojis and symbols.

Example:

```
Before:
Great job! 💪

After:
Great job
```

---

## 🔢 Number Removal

Removes numerical values.

Example:

```
Before:
Expected delay: 25 minutes

After:
Expected delay minutes
```

---

## 🚫 Stop Word Removal

Removes commonly used words that do not add significant meaning.

Example:

```
Before:
to download your marksheet

After:
download marksheet
```

---

## 🌱 Stemming and Lemmatization

Reduces words into their meaningful root forms.

Examples:

```
playing  → play
connected → connect
running → run
```

---

# 🔄 Raw Text vs Cleaned Text

| Raw Text | Cleaned Text |
|---|---|
| Traffic Alert: Heavy congestion detected near Central Bridge. Expected delay: 25 minutes. 🚦 | traffic alert heavy congestion detected near central bridge expected delay minutes |
| Visit https://studentportal.edu to download your semester marksheet. | visit download semester marksheet |
| Your fitness tracker recorded 12,486 steps and burned 542 calories today. Great job! 💪 | fitness tracker recorded steps burned calories today great job |

---

# 📌 Before vs After Comparison

| Preprocessing Step | Before | After |
|---|---|---|
| Lowercase | Traffic Alert | traffic alert |
| Remove URL | https://studentportal.edu | Removed |
| Remove Numbers | 25 minutes | minutes |
| Remove Emoji | 💪 | Removed |
| Remove Punctuation | Great job! | Great job |
| Remove Stop Words | to download your | download |
| Final Output | Raw Text | Clean Text |

---

# ✨ Features

The project performs:

📖 Reading raw text files  
🔡 Lowercase conversion  
✂️ Sentence tokenization  
🧩 Word tokenization  
🌐 URL and email removal  
😀 Emoji removal  
🔢 Number removal  
✏️ Punctuation removal  
🧹 Extra space removal  
🚫 Stop word removal  
🌱 Stemming  
📚 Lemmatization  
✅ Final clean text generation  

---

# 📤 Output

The project generates:

```
Original Text
      ↓
Lowercase Text
      ↓
Sentence Tokens
      ↓
Word Tokens
      ↓
Cleaned Text
      ↓
Final Output
```

The cleaned output is saved as:

```
Cleaned_Text.txt
```

---

# 🚀 Applications

This preprocessing pipeline can be used in:

- 💬 Sentiment Analysis
- 📑 Text Classification
- 🚫 Spam Detection
- 🤖 Chatbots
- 🌐 Machine Translation
- 🔎 Information Retrieval
- 📚 Document Classification
- ❓ Question Answering Systems
- 🧠 Language Models

---

# 🧠 Learning Outcomes

Through this project, I learned:

✅ Fundamentals of Natural Language Processing.  
✅ Importance of text preprocessing in AI applications.  
✅ Tokenization techniques.  
✅ Regular expression-based text cleaning.  
✅ Stop word removal.  
✅ Difference between stemming and lemmatization.  
✅ Preparing text data for machine learning models.

---

# 📝 Conclusion

This project successfully demonstrates a complete **Text Preprocessing Pipeline using Python**.

The raw text is transformed into clean and structured data through various NLP techniques such as lowercasing, tokenization, URL removal, emoji removal, number removal, punctuation removal, stop word removal, stemming, and lemmatization.

The final cleaned text provides a strong foundation for developing advanced **Natural Language Processing and Machine Learning applications**.

---
