# 🏥 Smart Healthcare System

A comprehensive Django-based Healthcare Management System with 20 integrated modules.

## 📋 Modules Overview

| # | Module | Description |
|---|--------|-------------|
| 1 | User Authentication | Registration, Login, Role Management |
| 2 | Patient Management | Patient Profile, Medical History, Health Records |
| 3 | Doctor Management | Doctor Profile, Specialization, Availability |
| 4 | Appointment Management | Booking, Scheduling, Status Tracking |
| 5 | Disease Prediction | Symptom-Based AI Disease Prediction |
| 6 | Medical Image Analysis | X-ray, MRI, CT Scan Upload & Analysis |
| 7 | EHR | Electronic Health Records Storage |
| 8 | Prescription Management | Digital Prescription Generation |
| 9 | Medicine Recommendation | Medicine Database & Recommendations |
| 10 | IoT Health Monitoring | Heart Rate, Temp, SpO₂, BP Monitoring |
| 11 | AI Healthcare Chatbot | 24/7 Health Assistance Bot |
| 12 | Emergency Alert | SOS Alerts & Emergency Contacts |
| 13 | Health Analytics | Disease Stats, Trends, Reports |
| 14 | Notification System | SMS, Email & In-app Reminders |
| 15 | Admin Dashboard | User Management & System Monitoring |
| 16 | Feedback & Reviews | Patient Feedback & Doctor Ratings |
| 17 | Telemedicine | Video Consultation (Jitsi Meet) |
| 18 | Laboratory Management | Test Requests & Results |
| 19 | Billing & Payment | Online Payments & Invoices |
| 20 | Report Generation | PDF Reports & Analytics Export |

## 🚀 Quick Start

### Prerequisites
- Python 3.9+
- pip

### Installation

```bash
# 1. Extract the zip file
# 2. Navigate to project directory
cd smart_healthcare

# 3. Create virtual environment
python -m venv venv
source venv/bin/activate    # Linux/Mac
venv\Scripts\activate       # Windows

# 4. Install dependencies
pip install -r requirements.txt

# 5. Run migrations
python manage.py migrate

# 6. Create superuser (or use seeded accounts below)
python manage.py createsuperuser

# 7. Run the server
python manage.py runserver

# 8. Open browser
# http://127.0.0.1:8000/
```

## 👥 Demo Accounts

| Role | Username | Password |
|------|----------|----------|
| Admin | admin | admin123 |
| Doctor | doctor1 | doctor123 |
| Patient | patient1 | patient123 |

## 🏗 Project Structure

```
smart_healthcare/
├── authentication/       # User auth & roles
├── patients/             # Patient management
├── doctors/              # Doctor management
├── appointments/         # Appointment booking
├── disease_prediction/   # AI disease prediction
├── medical_imaging/      # Image upload & analysis
├── ehr/                  # Electronic health records
├── prescriptions/        # Prescriptions
├── medicine/             # Medicine database
├── iot_monitoring/       # IoT health monitoring
├── chatbot/              # AI chatbot
├── emergency/            # SOS alerts
├── analytics/            # Health analytics
├── notifications/        # Notifications
├── dashboard/            # Main dashboard
├── feedback/             # Reviews & feedback
├── telemedicine/         # Video consultations
├── laboratory/           # Lab tests
├── billing/              # Billing & payments
├── reports/              # Report generation
├── templates/            # HTML templates
├── static/               # CSS, JS, Images
├── media/                # Uploaded files
├── manage.py
├── requirements.txt
└── README.md
```

## 🔗 URL Routes

- `/` → Dashboard
- `/auth/login/` → Login
- `/auth/register/` → Register
- `/patients/` → Patients List
- `/doctors/` → Doctors List
- `/appointments/` → Appointments
- `/disease-prediction/` → Disease Prediction
- `/medical-imaging/` → Medical Imaging
- `/ehr/` → EHR Records
- `/prescriptions/` → Prescriptions
- `/medicine/` → Medicine Database
- `/iot/` → IoT Monitoring
- `/chatbot/` → AI Chatbot
- `/emergency/` → Emergency
- `/analytics/` → Analytics
- `/notifications/` → Notifications
- `/telemedicine/` → Telemedicine
- `/laboratory/` → Laboratory
- `/billing/` → Billing
- `/reports/` → Reports
- `/admin/` → Django Admin Panel

## 🛠 Tech Stack

- **Backend:** Django 4.2, Django REST Framework
- **Database:** SQLite (development), PostgreSQL (production)
- **Frontend:** Bootstrap 5.3, Font Awesome 6, Chart.js
- **AI/ML:** Rule-based disease prediction (extensible to sklearn/TensorFlow)
- **Video Calls:** Jitsi Meet integration
- **Authentication:** Django built-in auth system

## 🔑 Key Features

- Multi-role system (Patient, Doctor, Admin, Lab Technician, Pharmacist)
- Real-time IoT vital signs monitoring with live updates
- AI symptom checker with disease prediction
- Full CRUD operations for all modules
- Responsive Bootstrap 5 UI
- RESTful API ready (Django REST Framework)
- SOS emergency alert system
- Video consultation via Jitsi Meet

## 📝 License

This project is for educational purposes.
