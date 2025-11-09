🛍️ E-Commerce Website

A fully functional E-Commerce platform built with Django and Django Templates using server-side rendering (SSR) — no APIs or frontend frameworks.
This project was my first ever Django project, where I learned the fundamentals of full-stack web development, database modeling, routing, and server-side rendering. Despite being a beginner project, it demonstrates solid architecture, modular design, and separation of concerns through the use of multiple Django apps.
📬 alirzglshn
🚀 Tech Stack


Backend Framework: Django (Python)


Templating Engine: Django Templates (Server-Side Rendering)


Database: SQLite


Frontend: HTML, CSS, JavaScript


Payment Handling: Custom logic via Django views


Other Tools: Django Messages Framework, Context Processors, Static & Media File Handling



🧩 Project Structure
The project is organized into three main Django apps:
App NamePurposecoreHandles main pages (home, products, categories, search, authentication, etc.)cardManages shopping cart logic and session-based cart systempaymentHandles checkout flow, order management, and payment confirmation

⚙️ Key Features
✅ Server-Side Rendering (SSR) using Django Templates
✅ Dynamic product catalog (with categories and search)
✅ Session-based shopping cart system
✅ Basic user registration and login
✅ Order and checkout workflow
✅ Admin dashboard (Django’s built-in admin panel)
✅ Static and media file configuration

🧠 What I Learned
This project was a huge milestone in my Django journey. I learned:


How to structure Django projects and create reusable apps


How server-side rendering works without REST APIs


Handling forms, sessions, and user data securely


Using Django’s ORM for database interactions


Implementing templates, context processors, and URL routing



🛠️ Installation & Setup
Clone the repository:
git clone https://github.com/yourusername/ecommerce-website.git
cd ecommerce-website

Create and activate a virtual environment:
python -m venv venv
source venv/bin/activate   # Linux / macOS
venv\Scripts\activate      # Windows

Install dependencies:
pip install -r requirements.txt

Run migrations and start the server:
python manage.py migrate
python manage.py runserver

Open your browser and go to:
👉 http://127.0.0.1:8000/

📂 Folder Structure
ecommerce-website/
│
├── core/           # Main app (products, categories, auth, etc.)
├── card/           # Shopping cart functionality
├── payment/        # Checkout and order management
├── ecom/           # Project configuration and URLs
├── static/         # CSS, JS, images
├── templates/      # HTML templates for SSR
└── manage.py


🧾 Notes

⚠️ This project was built before I learned about REST APIs and client-side rendering frameworks like React or Vue.
It’s fully server-rendered, showing my grasp of core Django fundamentals before moving into more advanced API-based architectures.


🌟 Future Improvements


Add Django REST Framework for API support


Integrate React or Vue.js for a modern frontend


Implement user authentication and authorization


Add CRUD operations for products and categories



🧑‍💻 Author


Alireza Golshan
Backend Developer (Django) - but i know a bit of fronend and client side rendering too

THANKS FOR VEWING THIS REPOSITORY 
