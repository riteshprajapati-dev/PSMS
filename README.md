# PSMS
Premium Salon Management System — A full-stack Django web application for managing salon services, customer appointments, staff operations, feedback, reports, and revenue efficiently.
# 💇 Premium Salon Management System (PSMS)

A complete **Salon Management System** built with **Python and Django** to simplify salon operations, appointment management, customer management, services, feedback, and business reporting.

PSMS provides separate functionality for **Customers** and **Staff/Admin**, making it easier to manage daily salon activities through a centralized web application.

---

## 🚀 Features

### 👤 Customer Features

* 🔐 Customer Registration & Login
* 👤 Customer Profile Management
* 💇 Browse Available Salon Services
* 📅 Book Salon Appointments
* ⏰ Available Time Slot Management
* 📋 View My Appointments
* ❌ Cancel Pending Appointments
* ⭐ Give Ratings & Feedback
* 📊 View Appointment Status
* 🖼️ Profile Image Upload

### 🛠️ Admin / Staff Features

* 📊 Staff Dashboard
* 👥 Customer Management
* 💇 Service Management
* ➕ Add New Services
* ✏️ Edit Services
* 🗑️ Manage Services
* 📅 Appointment Management
* ✅ Approve Appointments
* ✔️ Mark Appointments as Completed
* ❌ Cancel Appointments
* 🔎 Search & Filter Appointments
* 👤 View Customer Details
* ⭐ Feedback & Rating Management
* 📈 Feedback Analytics
* 💰 Revenue Reports
* 📊 Appointment Statistics
* 📅 Appointment Calendar
* 📥 Export Appointment Data to CSV
* 📊 Export Data to Excel
* 📈 Dashboard Charts & Analytics

---

## 🧑‍💻 Technologies Used

| Technology      | Purpose               |
| --------------- | --------------------- |
| 🐍 Python       | Backend Programming   |
| 🌐 Django       | Web Framework         |
| 🗄️ SQLite      | Database              |
| 🎨 HTML5        | Page Structure        |
| 🎨 CSS3         | Styling               |
| 🅱️ Bootstrap 5 | Responsive UI         |
| ⚡ JavaScript    | Frontend Interactions |
| 📊 Chart.js     | Dashboard Charts      |
| 🖼️ Pillow      | Image Processing      |
| 📄 CSV / Excel  | Data Export           |
| 🔧 Git & GitHub | Version Control       |

---

## 🏗️ Project Structure

```text
PremiumSalon/
│
├── premium_salon/
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── accounts/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── forms.py
│   └── ...
│
├── salon/
│   ├── models.py
│   ├── views.py
│   ├── forms.py
│   ├── urls.py
│   ├── admin.py
│   └── ...
│
├── templates/
│   └── ...
│
├── media/
│   └── services/
│
├── manage.py
├── db.sqlite3
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/PremiumSalon.git
```

### 2. Open the Project

```bash
cd PremiumSalon
```

### 3. Create Virtual Environment

```bash
python -m venv venv
```

### 4. Activate Virtual Environment

### Windows

```bash
venv\Scripts\activate
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

If `requirements.txt` is not available:

```bash
pip install django pillow openpyxl
```

### 6. Apply Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 7. Create Superuser

```bash
python manage.py createsuperuser
```

Enter:

```text
Username:
Email:
Password:
```

### 8. Run the Development Server

```bash
python manage.py runserver
```

Open the application in your browser:

```text
http://127.0.0.1:8000/
```

Admin panel:

```text
http://127.0.0.1:8000/admin/
```

---

## 📅 Appointment Workflow

```text
Customer
   │
   ▼
Select Service
   │
   ▼
Select Date & Time
   │
   ▼
Book Appointment
   │
   ▼
Pending
   │
   ├──► Approved
   │       │
   │       ▼
   │   Completed
   │
   └──► Cancelled
```

---

## 📊 Dashboard

The staff dashboard provides useful business information such as:

* Today's appointments
* Recent appointments
* Total customers
* Total services
* Revenue
* Most booked services
* Appointment statistics
* Last 7 days appointment chart
* Monthly analytics

---

## 🔐 User Roles

### Customer

Customers can:

* Create an account
* Login
* Manage profile
* Browse services
* Book appointments
* View appointments
* Cancel pending appointments
* Submit feedback

### Staff / Admin

Staff members can:

* Manage services
* Manage customers
* Manage appointments
* Approve or cancel appointments
* Complete appointments
* View reports
* Manage feedback
* View analytics
* Export business data

---

## 📈 Reports & Analytics

PSMS provides business reports including:

* 💰 Revenue Report
* 📅 Appointment Report
* 👥 Customer Information
* ⭐ Rating & Feedback Analytics
* 💇 Most Booked Services
* 📊 Appointment Statistics

Data can also be exported for further analysis.

---

## 🔒 Security

The application uses Django's built-in security features including:

* User authentication
* Password hashing
* CSRF protection
* Login-required views
* Staff-only access control
* Django ORM for database operations

> **Note:** This project is currently configured for development purposes. Production deployment should use appropriate security settings, environment variables, a production database, and a proper web server.

---

## 🎯 Future Improvements

Some planned improvements include:

* 💳 Online Payment Integration
* 📧 Email Notifications
* 📱 SMS Appointment Notifications
* 📱 Mobile Responsive Improvements
* 🧾 Invoice Generation
* 📦 Inventory Management
* 👨‍💼 Employee Management
* 📊 Advanced Business Analytics
* ☁️ Cloud Deployment
* 🔔 Real-time Notifications

---

## 👨‍💻 Developer

**Ritesh Prajapati**

Full-Stack Web Developer | Python & Django

### Skills Used

`Python` `Django` `HTML` `CSS` `JavaScript` `Bootstrap` `SQLite` `Chart.js` `Git` `GitHub`

---

## ⭐ Project Goal

The main goal of **Premium Salon Management System** is to digitize salon operations and provide an easy-to-use platform for managing customers, services, appointments, staff activities, feedback, and business reports.

---

## 📜 License

This project is created for **learning, portfolio, and educational purposes**.
