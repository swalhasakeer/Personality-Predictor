# 🧠 Personality Predictor Web App

This project is a machine learning web application that predicts a person's **personality type**—**Introvert** or **Extrovert**—based on behavioral features such as social event attendance, time spent alone, and stage fear. The app includes **Exploratory Data Analysis (EDA)**, **model comparison**, and a **Flask-based web interface**.

---

## 🚀 Project Overview

- ✅ **EDA** to understand patterns in social and behavioral data
- ✅ Multiple **machine learning models** evaluated (Logistic Regression, Random Forest, SVM, etc.)
- ✅ Best model (**K-Nearest Neighbors**) saved using `pickle`
- ✅ Clean and responsive **Flask web app**
- ✅ HTML form with `select` options for binary inputs like **Stage Fear** and **Drained After Socializing**

---

## 📊 Dataset Features

| Feature                    | Description                               |
|----------------------------|-------------------------------------------|
| Time_spent_Alone           | Hours spent alone daily (0–11)            |
| Stage_fear                 | Presence of stage fright (Yes/No)         |
| Social_event_attendance    | Frequency of social events (0–10)         |
| Going_outside              | Frequency of going outside (0–7)          |
| Drained_after_socializing  | Feeling drained after socializing (Yes/No)|
| Friends_circle_size        | Number of close friends (0–15)            |
| Post_frequency             | Social media post frequency (0–10)        |
| **Personality (Target)**   | Target variable (Extrovert/Introvert)     |

---

## 🧪 Models Trained

- Logistic Regression
- Random Forest
- Decision Tree
- K-Nearest Neighbors (Best Model)
- Support Vector Machine
- Extra Trees Classifier

📈 **Best Accuracy:** `K-Nearest Neighbors – 93.21%`

---

## 🧰 Tech Stack

- Python
- Pandas, NumPy, Matplotlib, Seaborn (EDA)
- scikit-learn (ML Models)
- Flask (Web Framework)
- HTML(Frontend)

---

## 🧠 How It Works

1. Perform EDA to visualize and understand trends in the dataset.
2. Preprocess data (Label Encoding, Scaling).
3. Train multiple models and compare their accuracy.
4. Save the best model (`KNN`) using `pickle`.
5. **Build a Flask app that**:
   - Accepts input through a form.
   - Encodes the binary options from select dropdowns.
   - Predicts the personality.
   - Displays the result as **Introvert** or **Extrovert**.

**This is the App's Frontend:**

![image](https://github.com/user-attachments/assets/b689822f-1597-4f3c-ab36-c882bea939b9)

---

## 🔧 How to Run Locally

```bash
# Clone the repository
git clone https://github.com/your-username/personality-predictor.git
cd personality-predictor

# Install dependencies
pip install -r requirements.txt

# Run the Flask app
python app.py
```
---

## 📁 Folder Structure
```bash
├── app.py                           # Flask backend
├── knn_model.pkl                    # Saved KNN model
├── templates/
│   └── index.html                   # Frontend HTML form
├── Personality_Prediction.ipynb     # Exploratory Data Analysis
├── README.md
└── requirements.txt
```
---

## 📌 Future Enhancements
  - Add user authentication

  - Store predictions in a database

  - Host on Render or Heroku

  - Mobile responsive UI

---

## 🙌 Acknowledgments

Thanks to open-source libraries and tools that made this possible!
