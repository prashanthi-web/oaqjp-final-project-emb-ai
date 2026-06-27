# 📊 Emotion Detection Web Application

## 🧠 Project Overview

This project is an AI-powered **Emotion Detection Web Application** built using **Python, Flask, and IBM Watson NLP (Emotion Analysis API)**.
The application analyzes user input text and detects emotions such as **anger, disgust, fear, joy, and sadness**, along with the dominant emotion.

## 🚀 Features

* 🔍 Detects emotions from text input
* 🤖 Uses IBM Watson NLP Emotion Analysis API
* 🌐 Web interface built with Flask
* ⚠️ Handles empty or invalid input gracefully
* 📊 Displays emotion breakdown and dominant emotion
* 🧪 Includes unit testing and static code analysis (Pylint 10/10)

## 🛠️ Tech Stack

* Python 🐍
* Flask 🌐
* JavaScript
* HTML/CSS
* IBM Watson NLP API 🤖
* Pylint (Code Quality)

## 📂 Project Structure

final_project/
│
├── EmotionDetection/
│   └── emotion_detection.py
│
├── templates/
│   └── index.html
│
├── static/
│   └── mywebscript.js
│
├── server.py
├── requirements.txt
└── README.md

## ⚙️ How It Works

1. User enters text in the web interface
2. Flask server sends request to `emotion_detector()` function
3. IBM Watson NLP API processes the text
4. Response returns emotion scores
5. Application displays:

   * Anger
   * Disgust
   * Fear
   * Joy
   * Sadness
   * Dominant Emotion

## ▶️ How to Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/prashanthi-web/oaqjp-final-project-emb-ai.git
cd oaqjp-final-project-emb-ai
```

### 2. Install dependencies

```bash
pip install flask requests
```

### 3. Run the application

```bash
python server.py
```

### 4. Open in browser

```
http://127.0.0.1:5000/
```

## 🧪 Testing

The project includes:

* Unit tests for emotion detection
* Manual UI testing
* Error handling validation for blank inputs

## ⚠️ Error Handling

* If input is blank or invalid:

  ```
  Invalid text! Please try again!
  ```
* API failure or bad request handled gracefully


## 📈 Code Quality

* Static code analysis performed using **Pylint**
* Achieved **10/10 score**
* Clean code with proper docstrings and structure

## 📌 Learning Outcomes

* Flask web development
* REST API integration
* IBM Watson NLP usage
* Error handling in Python
* Unit testing & code quality practices
* Git & GitHub workflow

---

## 👩‍💻 Author

**Prashanthi Web**

---

## 📜 License

This project is part of an educational assignment and is intended for learning purposes.

