# 📝 Sentiment Analyzer

A sleek and lightweight web application built with **Flask** and **TextBlob** that performs real-time Natural Language Processing (NLP) to determine the sentiment of any given text.

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Framework-Flask-lightgrey.svg)](https://flask.palletsprojects.com/)
[![Vercel](https://img.shields.io/badge/Deployment-Vercel-black.svg)](https://vercel.com/)

---

## 🚀 Features

*   **Real-time Analysis:** Instantly calculates sentiment scores upon form submission.
*   **Sentiment Metrics:** Returns **Polarity** (how positive/negative) and **Subjectivity** (how factual/opinionated).
*   **Visual Feedback:** Dynamic UI changes (colors and emojis) based on the sentiment result.
*   **Responsive Design:** Fully styled with CSS for a professional user experience.
*   **Production Ready:** Optimized for deployment on Vercel.

---

## 🛠️ Tech Stack

*   **Backend:** Python 3.x, Flask
*   **NLP Engine:** TextBlob
*   **Frontend:** HTML5, CSS3 (Jinja2 Templating)
*   **Deployment:** Vercel

---

## 📁 Project Structure

```text
├── static/
│   └── style.css          # App styling and animations
├── templates/
│   └── index.html         # Main UI template
├── index.py                 # Main Flask application logic
├── requirements.txt       # Python dependencies
├── vercel.json            # Vercel deployment configuration
└── README.md              # Project documentation
```

---

## 💻 Local Setup

Follow these steps to run the project locally on your machine:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/vivekjoshi2006/Sentiment_Analysis_Web_App.git
    cd flask-sentiment-analysis
    ```

2.  **Create a Virtual Environment (Recommended):**
    ```bash
    python -m venv venv
    # Activate on Windows:
    venv\Scripts\activate
    # Activate on Mac/Linux:
    source venv/bin/activate
    ```

3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Run the application:**
    ```bash
    python App.py
    ```
    Access the app at `http://127.0.0.1:5000/`

---

## 📊 How it Works

The app uses the **TextBlob** library to process text:
*   **Polarity:** A float value within the range `[-1.0, 1.0]`. `-1` is very negative, `1` is very positive.
*   **Subjectivity:** A float value within the range `[0.0, 1.0]` where `0.0` is very objective (fact-based) and `1.0` is very subjective (opinion-based).

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

**Developed with ❤️ by VIVEK JOSHI**
