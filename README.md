# MedWise: One-Stop Destination for Healthcare

MedWise is a web-based healthcare platform designed to streamline the interaction between patients and healthcare providers. The system allows patients to book doctor appointments, predict diseases based on symptoms, and access emergency healthcare services through an integrated SOS feature.

The goal of MedWise is to improve accessibility, efficiency, and responsiveness in healthcare by combining modern web technologies with intelligent medical prediction tools.

---

## 🚀 Features

- Online doctor appointment booking system
- Symptom-based disease prediction using machine learning
- Doctor availability and schedule management
- Emergency SOS system for ambulance and nearby doctor assistance
- Patient medical history tracking
- Admin dashboard for managing doctors and users
- Secure login and authentication system
- Responsive user interface for easy navigation

---

## 🛠️ Technologies Used

Frontend:
- HTML
- CSS
- JavaScript

Backend:
- Django

Database:
- PostgreSQL

Machine Learning:
- Scikit-learn

Other Tools:
- REST APIs
- Joblib for ML model loading

---

## 📂 Project Structure


MedWise
│
├── backend
│ ├── manage.py
│ ├── views.py
│ ├── models.py
│ └── urls.py
│
├── templates
│ ├── home.html
│ ├── login.html
│ ├── register.html
│ ├── symptom_input.html
│ └── prediction_result.html
│
├── static
│ ├── css
│ ├── js
│ └── images
│
├── ml_model
│ └── disease_prediction_model.pkl
│
└── README.md

## ⚙️ How to Run the Project

1. Clone the repository

git clone https://github.com/your-username/MedWise-Healthcare-Platform.git

2. Navigate to the project folder

cd MedWise-Healthcare-Platform


3. Install required dependencies


pip install -r requirements.txt


4. Run the Django server


python manage.py runserver


5. Open the project in your browser


http://127.0.0.1:8000/


---

## 👥 User Roles

### Patient
- Register and login
- Enter symptoms for disease prediction
- Book doctor appointments
- View prediction history
- Use emergency SOS feature

### Doctor
- Manage appointment requests
- View patient information
- Update availability

### Administrator
- Manage doctors and users
- Monitor system activity
- Access prediction logs

---

## 🧠 Machine Learning Module

The disease prediction system uses a trained machine learning model built using Scikit-learn. Users input their symptoms through a dynamic form, and the model predicts the most likely disease. The result is displayed along with suggested doctors for consultation.

---

## 🚑 Emergency SOS Feature

The SOS system allows patients to instantly request emergency medical assistance. The system helps locate the nearest available doctor or ambulance service, reducing response time in critical situations.

---

## 🔐 Security Features

- Role-based authentication
- Secure login and session management
- Input validation and error handling
- Protected admin routes

---

## 📈 Future Enhancements

- Integration with real-time hospital databases
- Mobile application version
- Online payment for consultations
- AI chatbot for health queries
- Real-time ambulance tracking

---

## 🎯 Project Objective

The objective of MedWise is to create a unified digital healthcare platform that simplifies appointment booking, enhances early disease detection using machine learning, and provides rapid emergency support.

---

## 👩‍💻 Author

Kritika Dhuper  
B.Tech Computer Science Engineering  
SRM Institute of Science and Technology

---

## 📜 License

This project is developed for educational and academic purposes.
