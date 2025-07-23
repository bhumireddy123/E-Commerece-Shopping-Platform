🛒 Dream's Django E-Commerce Project
📁 Project Structure
django_ecommerce/
├── ecommerce_project/       # Django project settings
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── store/                   # Main e-commerce logic
│   ├── migrations/
│   ├── templates/
│   │   └── store/
│   │       ├── cart.html
│   │       ├── checkout.html
│   │       ├── home.html
│   │       ├── orders.html
│   │       ├── product_detail.html
│   │       ├── vendor_dashboard.html
│   │       ├── product_form.html
│   │       └── vendor_product_list.html
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── urls.py
│   ├── views.py
│   ├── forms.py
│   └── tests.py
│
├── users/                   # User registration and authentication
│   ├── templates/
│   │   └── users/
│   │       ├── login.html
│   │       ├── logout.html
│   │       ├── register.html
│   │       └── vendor_register.html
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── urls.py
│   ├── views.py
│   └── forms.py
│
├── static/
│   └── style.css            # CSS styles
│
├── media/                   # Uploaded images (product photos)
│   └── products/
│       ├── img1.png
│       └── img2.png
│
├── db.sqlite3               # SQLite DB (or your DB if configured)
├── manage.py
└── README.md
