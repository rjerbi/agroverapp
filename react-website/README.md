# Agrovera Web Application

A full-stack web application developed by **Rahma Jerbi**  for managing members, payments, and agricultural production data.  
This project includes a **public-facing website** and a **dashboard** for admins to monitor members and payments with interactive charts.

---

##  Features

### Website
- Home, About, Production, and Membership pages
- Mission, vision, and values sections
- Responsive layout with images and styled sections
- Contact form to submit inquiries

### Dashboard
- CRUD operations for members and payments
- Authentication system using Django REST Framework and token-based login
- Interactive charts using **Recharts**:
  - Bar chart: member locations by continent
  - Pie chart: member payment status

---

##  Technologies Used

### Backend
- Python & Django
- Django REST Framework
- Token-based authentication
- PostgreSQL (or other relational database)
- API endpoints for:
  - Members management
  - Member payments
  - Contact form
  - Login

### Frontend
- React.js
- React Router for navigation
- Recharts for charts
- Slick Carousel for slideshows
- Font Awesome for icons
- CSS & custom styles


## Installation & Running Locally
1. **Create virtual environment:**
- python -m venv env
- env\Scripts\activate     # Windows

2. **Install Backend dependencies:**
pip install Django djangorestframework djangorestframework-authtoken psycopg2 django-cors-headers python-dotenv

3. **then, you can run:**
- python manage.py migrate
- python manage.py createsuperuser
- python manage.py runserver

4. **Install Frontend dependencies:**
- npm install
- npm start




