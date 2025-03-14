# Apihub

## Overview
Apihub is a powerful API management system designed to streamline API interactions, handle authentication, and provide seamless integration capabilities.

---

## Apihub - A Powerful API Management System

<!-- First Image -->
<p align="center">
  <img src="https://github.com/user-attachments/assets/90be54f1-217f-4588-874e-ebfd30b891f3" 
       width="800" 
       style="border-radius: 10px; box-shadow: 5px 5px 15px rgba(0, 0, 0, 0.2);" 
       alt="Apihub Overview">
</p>
<p align="center"><em>Manage APIs effortlessly with Apihub.</em></p>

---

## Todo API Dashboard

<p align="center">
  <img src="https://github.com/user-attachments/assets/8c71d2c4-e3ed-48b6-8920-37996e1b9175" 
       width="800" 
       style="border-radius: 10px; box-shadow: 5px 5px 15px rgba(0, 0, 0, 0.2);" 
       alt="Todo API Dashboard">
</p>
<p align="center"><em>View and manage Todo APIs from a dashboard.</em></p>

---

## Apihub with ReDoc

<p align="center">
  <img src="https://github.com/user-attachments/assets/e5d6c5c0-9ca3-4422-a7ae-c587f4dc0cb4" 
       width="800" 
       style="border-radius: 10px; box-shadow: 5px 5px 15px rgba(0, 0, 0, 0.2);" 
       alt="Apihub API Monitoring">
</p>
<p align="center"><em>Apihub API documentation in ReDoc.</em></p>

---

## Features
✔ **Swagger & Django Integration**  
✔ **PostgreSQL Database**  
✔ **Docker & Docker Compose Support**  
✔ **CORS Support**  
✔ **Real-time API Processing**  
✔ **Deployment on Render**  

---

## Getting Started

### Prerequisites
Ensure you have the following installed:

- Python **3.11+**
- PostgreSQL
- Docker & Docker Compose *(optional for containerized setup)*
- Git

### Installation Steps

#### Clone the Repository
```sh
git clone https://github.com/mohitnandaniya-git/Apihub.git
cd Apihub
```

#### Set Up a Virtual Environment
```sh
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

#### Install Dependencies
```sh
pip install -r requirements.txt
```

#### Configure Environment Variables
Create a `.env` file and add:
```ini
SECRET_KEY = your_secret_key
DEBUG = 'True'
ALLOWED_HOSTS = '*'
CORS_ALLOWED_ORIGINS = '*'
POSTGRES_DB=apihub_db
POSTGRES_USER=your_user
POSTGRES_PASSWORD=your_password
POSTGRES_HOST = your_host
POSTGRES_PORT = your_port
```

#### Run Migrations
```sh
python manage.py makemigrations
python manage.py migrate
```

#### Start the Development Server
```sh
python manage.py runserver
```

## Access the Project
- **🔗 [Apihub Live Demo](https://apihub-ihuq.onrender.com)**


## References
- **[🔗 APIHUB](https://github.com/hiteshchoudhary/apihub)**
- **[🔗 DRF-YASG](https://drf-yasg.readthedocs.io/en/stable/readme.html)**
