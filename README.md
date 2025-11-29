# 🏥 Hospital Management System

A complete hospital management system built with Flask, SQLite, and Bootstrap.

## Features

- **Admin Dashboard**: Manage doctors, patients, and appointments
- **Doctor Portal**: View appointments, manage availability, add treatment records
- **Patient Portal**: Book appointments, view treatment history, manage profile

## Technologies Used

- **Backend**: Flask, SQLAlchemy
- **Frontend**: HTML, CSS, Bootstrap , Jinja2
- **Database**: SQLite

## Installation

1. Clone the repository:
```bash
git clone https://github.com/24f2000184/hospital-management-system-project-iitm-bs
cd hospital-management-system
```

2. Install dependencies:
```bash
pip install flask flask-sqlalchemy
```

3. Run the application:
```bash
python app.py
```

4. Open browser and go to: `http://127.0.0.1:5000/`

## Default Login

**Admin:**
- Email: admin@hospital.com
- Password: admin123

## Project Structure
```
hospital-management/
│
├── app.py
├── hospital.db (auto-created)
│
├── templates/
│   ├── base.html
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   ├── admin_dashboard.html
│   ├── admin_doctors.html
│   ├── admin_patients.html
│   ├── admin_appointments.html
│   ├── doctor_dashboard.html
│   ├── doctor_appointments.html
│   ├── doctor_availability.html
│   ├── complete_appointment.html
│   ├── patient_history.html
│   ├── patient_dashboard.html
│   ├── patient_doctors.html
│   ├── book_appointment.html
│   ├── patient_appointments.html
│   ├── treatment_history.html
│   └── patient_profile.html
│
└── static/
    └── css/
        └── style.css
```

## License

MIT License