# 🚖 Uber Price Data Analysis Using Machine Learning

This project is a **Machine Learning-based Uber Fare Prediction System** developed using **Python** and **Django**. The system predicts the estimated Uber ride fare based on trip-related information entered by the user.

---

# 📌 Project Overview

The objective of this project is to analyze Uber trip data and build a Machine Learning model that accurately predicts ride fares. The trained model is integrated with a Django web application, allowing users to estimate Uber fares through a simple web interface.

## Project Modules

* Data Collection
* Data Preprocessing
* Exploratory Data Analysis (EDA)
* Data Visualization
* Feature Selection
* Machine Learning Model Training
* Model Evaluation
* Model Saving
* Django Frontend Integration
* Fare Prediction System

---

# 🚀 Technologies Used

## 🖥️ Frontend

* HTML5
* CSS3
* Bootstrap

## ⚙️ Backend

* Python
* Django

## 🤖 Machine Learning

* Scikit-learn
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Pickle

---

# 📂 Project Structure

```
Uber/
│
├── backend/
│   ├── data.csv
│   ├── Uber.ipynb
│   └── model.pkl
│
├── frontend/
│   ├── base/
│   ├── Uber/
│   ├── static/
│   ├── templates/
│   ├── db.sqlite3
│   ├── manage.py
│   ├── model.pkl
│   ├── py3.11.4.txt
│   └── requirements.txt
```

---

# 📊 Machine Learning Workflow

## 1️⃣ Dataset Collection

* Uber trip fare dataset
* Ride details collected for fare prediction
* Dataset stored as `data.csv`

---

## 2️⃣ Data Preprocessing

* Handling missing values
* Removing duplicate records
* Data cleaning
* Feature selection
* Preparing training and testing datasets

---

## 3️⃣ Exploratory Data Analysis (EDA)

Performed data visualization to understand:

* Fare distribution
* Feature relationships
* Correlation between variables
* Dataset statistics
* Outlier detection

---

## 4️⃣ Machine Learning Model Training

The dataset is divided into training and testing sets, and multiple regression algorithms can be used to predict Uber fares.

The best-performing model is saved using **Pickle**.

---

## 5️⃣ Model Saving

The trained model is stored as:

```
model.pkl
```

The Django application loads this model to generate fare predictions.

---

# 📈 Data Visualization

Libraries Used:

* Matplotlib
* Seaborn

Visualizations include:

* Histogram
* Scatter Plot
* Correlation Heatmap
* Distribution Plot
* Feature Analysis

---

# ⚡ Installation Steps

## 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/Uber-price-data-analysis-using-Machine-learning.git
```

## 2. Navigate to the Project

```bash
cd Uber/frontend
```

## 3. Create Virtual Environment

```bash
python -m venv env
```

## 4. Activate Virtual Environment

### Windows

```bash
env\Scripts\activate
```

### Linux / macOS

```bash
source env/bin/activate
```

## 5. Install Dependencies

```bash
pip install -r requirements.txt
```

## 6. Run Django Server

```bash
python manage.py runserver
```

---

# 🌐 Open in Browser

```
http://127.0.0.1:8000/
```

---

# 🧠 Prediction Process

1. User opens the application.
2. User logs into the system.
3. Trip information is entered.
4. Input is sent to the Django backend.
5. The trained Machine Learning model predicts the estimated Uber fare.
6. The predicted fare is displayed on the result page.

---

# ✨ Features

* User Authentication
* Uber Fare Prediction
* Machine Learning Integration
* Django Web Application
* Responsive User Interface
* Data Visualization
* Trained Model Deployment

---

# 📌 Future Enhancements

* Google Maps API Integration
* Live Traffic Analysis
* Surge Pricing Prediction
* Route Optimization
* Cloud Deployment
* Mobile Application
* Real-Time Fare Estimation

---

# 👩‍💻 Author

**Yuvapriya S.**

AI & ML Engineer | Data Science Enthusiast

---

# ⭐ Conclusion

This project demonstrates a complete Machine Learning workflow, from data preprocessing and model training to deployment using Django.

It is a beginner-friendly project for understanding:

* Machine Learning
* Data Analysis
* Data Visualization
* Regression Models
* Django Development
* Model Deployment
* Real-world Fare Prediction
