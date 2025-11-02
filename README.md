# 💬 Sentiment-Analysis-for-ChatGPT-Reviews

This project is a **Streamlit web application** that performs **sentiment analysis** on ChatGPT reviews.  
It uses **Natural Language Processing (NLP)** and **Machine Learning** to analyze review texts and classify them as **Positive**, **Negative**, or **Neutral**.

## 🚀 Features

- 📊 **Interactive Dashboard** – Upload and explore the ChatGPT reviews dataset.  
- 🔍 **Real-time Sentiment Prediction** – Enter any review text and get instant sentiment results.  
- 🧠 **Machine Learning Model** – Trained using Logistic Regression / Naive Bayes on processed review data.  
- ⚙️ **Custom Filters** – Filter reviews by rating, language, and platform.  
- 🌗 **Dark/Light Theme Support** – Adaptive footer and clean UI for both modes.  
- 📁 **Modular Codebase** – Organized into `preprocess.py`, `model_train.py`, and `app.py` for clarity.  


## 🧩 Project Structure

📦 ChatGPT-Review-Sentiment-Analysis
│
├── app.py # Streamlit web application
├── model_train.py # Model training script
├── preprocess.py # Data preprocessing and text cleaning functions
├── model.pkl # Trained ML model
├── vectorizer.pkl # TF-IDF vectorizer
├── chatgpt_style_reviews_dataset.xlsx # Dataset containing ChatGPT reviews
├── requirements.txt # Python dependencies
└── README.md # Project documentation



## ⚙️ Installation

### 1️⃣ Clone this repository
''' bash
git clone https://github.com/<your-username>/ChatGPT-Review-Sentiment-Analysis.git
cd ChatGPT-Review-Sentiment-Analysis '''

2️⃣ Create a virtual environment
python -m venv venv
venv\Scripts\activate   # On Windows
source venv/bin/activate  # On Mac/Linux

3️⃣Install dependencies
pip install -r requirements.txt

🏃‍♂️ Run the App
streamlit run app.py

Then open your browser at 👉 http://localhost:8501

🧠 Model Training

If you want to retrain the model:
python model_train.py

