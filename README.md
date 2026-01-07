:
1. pip install djangorestframework
2. pip install psycopg2-binary
3. npm start מדליק את האתר
4. npm install @react-google-maps/api
5. python manage.py runserver מדליק את הקישור בין הקדימה לאחורה 

# RouteBite

RouteBite is a full-stack web application designed to help users choose restaurants more efficiently by providing real-time crowd and popularity data.

The system combines live data scraping, map-based visualization, and user preferences to support smarter dining decisions.

---

## 🌍 Project Overview

RouteBite was developed as an academic project during my degree studies, with the goal of building a real-world web system that integrates multiple external services and APIs.

The platform allows users to:
- View real-time restaurant crowd levels
- Filter restaurants based on preferred food types and time ranges
- Navigate to selected restaurants using Google Maps
- Make informed decisions based on real usage data rather than reviews alone

---

## 🎯 Problem Statement

Choosing a restaurant often involves uncertainty regarding:
- Current crowd levels
- Waiting times
- Peak hours

Existing platforms rarely provide **real-time load data** in a clear and interactive way.

RouteBite addresses this problem by combining **live popularity data** with an intuitive map-based interface.

---

## 💡 Solution

RouteBite uses:
- **Outscraper** to retrieve real-time popularity and busy-hours data for restaurants
- **Google Maps API** to visualize restaurants and enable navigation
- A **Django REST API** backend to process and serve data
- A **React-based frontend** to provide a clean and interactive user experience

Users can:
1. Select preferred dining hours
2. Choose food categories
3. View current and predicted crowd levels
4. Navigate directly to restaurants via Google Maps

---

## 🧠 Key Features

- 📍 Real-time restaurant load visualization
- 🕒 Popular hours and crowd estimation
- 🍔 Food category filtering
- 🗺️ Interactive Google Maps integration
- 🧭 Built-in navigation support
- 🔌 RESTful API architecture
- 🧩 Clean separation between frontend and backend

---

## 🛠️ Technologies Used

### Backend
- Python
- Django
- Django REST Framework
- PostgreSQL (via psycopg2)
- Outscraper API

### Frontend
- JavaScript
- React
- HTML / CSS
- Google Maps API
- @react-google-maps/api

### DevOps & Tools
- Git & GitHub
- Jenkins (CI/CD pipeline)
- npm / Node.js

---

## 🧱 Project Architecture

RouteBite/
├── backend/
│ ├── manage.py
│ ├── requirements.txt
│ └── Django REST API
├── frontend-clean/
│ ├── React application
│ └── Google Maps integration
├── Jenkinsfile
└── README.md



---

## ⚙️ Installation & Running Locally

### Clone the repository
```bash
git clone https://github.com/Nitaybenadmon123/RouteBite.git
cd RouteBite


Backend setup

pip install -r requirements.txt
pip install djangorestframework
pip install psycopg2-binary
python manage.py migrate
python manage.py runserver

Frontend setup

cd frontend-clean
npm install
npm start

🚀 Learning Outcomes

This project strengthened my skills in:

Full-stack web development

REST API design

Third-party API integration

Map-based UI development

System architecture and separation of concerns

Working with real-world, imperfect data

CI/CD fundamentals using Jenkins


🔮 Future Improvements

📱 Convert the system into a mobile application (Android / iOS)

🔐 Add user authentication and personalization

📊 Improve crowd prediction accuracy

☁️ Deploy to cloud infrastructure

🎨 Enhance UI/UX for mobile-first usage

📌 Project Status

Currently implemented as a web application.
Planned upgrade: mobile application for smartphones.
