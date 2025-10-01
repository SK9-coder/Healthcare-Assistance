# Healthcare Assistance Web Application

A full-stack web platform that simplifies healthcare access by connecting patients, doctors, and pharmacies. Built as a Master's team project, the system enables patients to book appointments, consult doctors, and forward prescriptions to nearby pharmacies for convenient medicine collection.

## Features
- **Patient Module:** Login, raise health issues, book appointments with doctors.
- **Doctor Module:** View patient requests, confirm/cancel appointments, issue prescriptions.
- **Pharmacy Module:** Receive prescriptions electronically, prepare medicines for pickup.
- **Dashboard:** Integrated views for patients, doctors, and pharmacies.
- **Database Integration:** Store and retrieve data using MySQL.
- **Flexible Payments:** Patients pay directly at clinic/pharmacy instead of in-app.

## Tech Stack
- **Frontend:** React.js (JavaScript, HTML, CSS)  
- **Backend:** Python Flask  
- **Database:** MySQL  
- **Tools:** VS Code, GitHub  

## Getting Started

### Prerequisites
- Node.js (for frontend)  
- Python 3.x (for backend)  
- MySQL server  

### Setup Instructions

####Frontend
```
- cd HealthCore/frontend
- npm install
- npm start
```
####Backend
```
- cd HealthCore/flaskpython
- pip install -r requirements.txt
- python app.py
```

#### Database
- Open `DatabaseConnection.py` and replace the default username/password with your MySQL credentials.  
- Create a database in MySQL (example: `healthcare_db`).  
- Add required tables (patients, doctors, pharmacies, appointments).  
