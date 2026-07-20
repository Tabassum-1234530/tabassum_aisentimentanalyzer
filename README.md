# 🛍️ Customer Review Sentiment Analyzer

A Machine Learning web application that analyzes customer product reviews and predicts whether the sentiment is **Positive**, **Neutral**, or **Negative**.

The application is built using **Python**, **Flask**, **Scikit-learn**, and **TF-IDF Vectorization**, with a simple and responsive web interface.

---

## 📌 Features

- 🔍 Analyze customer product reviews
- 😊 Predict Positive, Neutral, or Negative sentiment
- 🧠 Machine Learning-based prediction
- 🌐 User-friendly Flask web interface
- 🎨 Responsive and modern UI
- ⚡ Real-time sentiment analysis
- 💾 Pre-trained model using Joblib

---

## 🖥️ Demo

### Home Page

- Enter a customer review
- Click **Analyze Sentiment**
- View the predicted sentiment instantly

---

## 📂 Project Structure

```
Customer_Review_Sentiment_Analyzer/
│
├── models/
│   ├── sentiment_model.pkl
│   └── tfidf_vectorizer.pkl
│
├── static/
│   └── style.css
│
├── templates/
│   └── index.html
│
├── dataset/
│   └── amazon_reviews.csv
│
├── app.py
├── train_model.py
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 🛠️ Technologies Used

- Python
- Flask
- Scikit-learn
- Pandas
- NumPy
- Joblib
- HTML5
- CSS3

---

## 📊 Machine Learning Pipeline

1. Load Dataset
2. Data Cleaning
3. Text Preprocessing
4. TF-IDF Vectorization
5. Train-Test Split
6. Logistic Regression Model
7. Model Evaluation
8. Save Model
9. Flask Deployment

---

## 📈 Model Performance

| Metric | Score |
|---------|--------|
| Accuracy | **83.36%** |

### Classification Report

| Class | Precision | Recall | F1-score |
|--------|-----------|--------|----------|
| Negative | 0.80 | 0.35 | 0.49 |
| Neutral | 0.76 | 0.83 | 0.80 |
| Positive | 0.88 | 0.91 | 0.90 |

---

## 📦 Installation

Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/Customer_Review_Sentiment_Analyzer.git
```

Move into the project directory

```bash
cd Customer_Review_Sentiment_Analyzer
```

Create a virtual environment

```bash
python -m venv venv
```

Activate the virtual environment

### Windows

```bash
venv\Scripts\activate
```

### macOS/Linux

```bash
source venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
python app.py
```

Open your browser

```
http://127.0.0.1:5000
```

---

## 🧠 Train the Model

If you want to retrain the model using the dataset:

```bash
python train_model.py
```

The script will generate

```
models/
├── sentiment_model.pkl
└── tfidf_vectorizer.pkl
```

---

## 📋 Dataset

This project uses an Amazon Product Reviews dataset containing customer reviews labeled as:

- Positive
- Neutral
- Negative

The dataset includes:

- Cleaned Review
- Sentiment Label
- Review Length
- Review Score

---

## 📸 Screenshots


### Prediction Result

https://github.com/Tabassum-1234530/tabassum_aisentimentanalyzer/blob/main/Output_Prediction.png

---

## 🚀 Future Enhancements

- Confidence Score
- Sentiment Probability Graph
- Review History
- Dark Mode
- Multiple ML Model Comparison
- Deep Learning (LSTM/BERT)
- REST API Support
- Docker Deployment
- User Authentication

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit changes

```bash
git commit -m "Added new feature"
```

4. Push to GitHub

```bash
git push origin feature-name
```

5. Create a Pull Request

---

## 👨‍💻 Author

**Shaik Tabassum Sultana**

GitHub:
https://github.com/Tabassum-1234530/

LinkedIn:
https://www.linkedin.com/in/shaik-tabassum-sultana-4410322bb/

---

## ⭐ Support

If you found this project helpful, please consider giving it a ⭐ on GitHub.

---
