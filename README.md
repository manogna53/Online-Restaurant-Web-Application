🍽️ Online Restaurant Web Application
📌 Project Overview

This project is an Online Restaurant Web Application developed using Django.
It allows users to browse food items, customize orders, add items to cart, and place orders.

The main goal of this project is to simulate a real-world food ordering system with basic functionalities.

🚀 Features
👤 User Registration and Login
🍕 Browse Menu Items
➕ Add Items to Cart
🧀 Customize Food with Toppings
🛒 Cart Management
📦 Order Placement System
🛠️ Technologies Used
Backend: Python, Django
Frontend: HTML, CSS, JavaScript
Database: SQLite
Framework Architecture: MVT (Model-View-Template)
🧩 Project Structure
OnlineRestaurantWebApp/
│
├── manage.py
├── db.sqlite3
├── pizza/                # Main project folder
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── orders/               # Main application
│   ├── migrations/
│   ├── static/orders/
│   │   └── styles.css
│   ├── templates/orders/
│   │   ├── base.html
│   │   ├── index.html
│   │   ├── login.html
│   │   ├── signup.html
│   │   ├── cart.html
│   │   ├── topping.html
│   │   └── addtopping.html
│   ├── admin.py
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── apps.py
│
├── itemlist.csv
├── pricelist.csv
└── import.py
⚙️ How to Run the Project
Clone the repository:
git clone https://github.com/your-username/your-repo-name.git
Navigate to the project folder:
cd OnlineRestaurantWebApp
Install dependencies:
pip install django
Run migrations:
python manage.py migrate
Start the server:
python manage.py runserver
Open browser and go to:
http://127.0.0.1:8000/
🔐 Authentication
Users can register and login
Django’s built-in authentication system is used
🛒 Order Flow
User browses menu
Selects food item
Adds toppings (optional)
Adds item to cart
Views cart and places order
🗄️ Database
Managed using Django Models
Uses SQLite by default
Data stored using Django ORM
📈 Future Enhancements
💳 Online Payment Integration
📍 Order Tracking System
📱 Mobile Responsive UI
🔔 Notifications
📚 Learning Outcome

This project helped in understanding:

Django MVT architecture
Routing and Views
Template rendering
Database handling using ORM
User authentication
