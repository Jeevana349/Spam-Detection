# 📧 Email Spam Classification App

A simple **Machine Learning–powered web application** built using **Streamlit** that classifies emails as **Spam** or **Not Spam (Ham)**. The app uses a pre-trained ML model and a text vectorizer to analyze the content of an email entered by the user.

---

## 🚀 Features

* Classifies emails as **Spam** or **Not Spam**
* Clean and interactive UI built with **Streamlit**
* Uses a trained **scikit-learn** model
* Fast and lightweight
* Beginner-friendly ML project

---

## 🧠 Machine Learning Overview

* **Text Preprocessing & Vectorization**: Emails are transformed using a trained text vectorizer (`vectorizer.pkl`).
* **Model**: A supervised ML classification model trained on labeled email data (`spam.pkl`).
* **Prediction**: The model predicts whether the email is spam (`1`) or not spam (`0`).

---

## 🛠️ Tech Stack

* **Python**
* **Streamlit** – Web UI
* **Scikit-learn** – Machine Learning
* **NLTK** – Text processing
* **NumPy & SciPy** – Numerical computations
* **Pickle** – Model serialization

---

## 📂 Project Structure

```
├── app.py                  # Streamlit application
├── spam.pkl                # Trained ML model
├── vectorizer.pkl          # Trained text vectorizer
├── requirements.txt        # Project dependencies
└── README.md               # Project documentation
```

---

## 📦 Requirements

The application requires the following Python packages:

```
click==8.1.7
colorama==0.4.6
joblib==1.4.2
nltk==3.9.1
numpy==2.1.3
regex==2024.9.11
scikit-learn==1.5.2
scipy==1.14.1
setuptools==75.3.0
threadpoolctl==3.5.0
tqdm==4.66.6
wheel==0.44.0
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```
git clone https://github.com/your-username/email-spam-classifier.git
cd email-spam-classifier
```

### 2️⃣ Create a Virtual Environment (Optional but Recommended)

```
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3️⃣ Install Dependencies

```
pip install -r requirements.txt
```

### 4️⃣ Run the Application

```
streamlit run app.py
```

The app will open automatically in your browser.

---

##  Application UI

* Enter an email in the text area
* Click **Classify**
* Instantly see whether the email is **Spam** or **Not Spam**

---

##  app.py Overview

* Loads the trained model and vectorizer using `pickle`
* Accepts user input via Streamlit text area
* Transforms input text using the vectorizer
* Predicts spam/ham using the ML model
* Displays results clearly to the user

---

##  Notes

* Ensure `spam.pkl` and `vectorizer.pkl` are present in the root directory
* The model must be trained using the same preprocessing steps as used during prediction

---

##  Future Improvements

* Add confidence/probability score
* Improve UI styling
* Add email preprocessing preview
* Support file upload (.txt / .eml)
* Deploy on Streamlit Cloud / AWS / Heroku

---

## 👨 Author

**Sai Jeevana**
Made with ❤️ using Python & Machine Learning

---

## 📜 License

This project is open-source and available for learning and educational purposes.

---


## Live Demo

Check out the live demo of the app here: [Streamlit App](https://spam-detectiongit-miambpbifqzbfweroy8m9k.streamlit.app/)

---
