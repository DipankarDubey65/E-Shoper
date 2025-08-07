# 🛒 E-Shoper - Django E-commerce Website

**E-Shoper** is a fully functional E-commerce web application built using the Django framework. It allows users to register,
log in, browse products, add them to a shopping cart, and place orders. Admins can manage products and categories through the Django admin panel.

---

## 🚀 Key Features

- 🔐 User Registration, Login, and Logout
- 📦 Product Listing by Category
- 🛒 Shopping Cart (Add, Remove, Update Quantity)
- ✅ Order Placement & Checkout Process
- 🗂️ Session-based Cart (works without login)
- 🖼️ Product Image Upload
- 📋 Order History for Logged-in Users
- 👨‍💻 Admin Panel for Product and Category Management
- 🎨 Responsive Frontend using Bootstrap

---

## 🛠️ Tech Stack

| Component      | Technology        |
|----------------|-------------------|
| Language       | Python 3.x        |
| Framework      | Django            |
| Frontend       | HTML, CSS, Bootstrap |
| Database       | SQLite (Default)  |
| Authentication | Django Auth       |

---

## 📁 Project Structure

E-Shoper/
├── accounts/ # Authentication
├── cart/ # Cart management
├── category/ # Product categories
├── products/ # Product listings
├── orders/ # Order and checkout logic
├── static/ # Static files (CSS, JS)
├── templates/ # HTML templates
├── media/ # Uploaded product images
├── EShoper/ # Project settings
└── manage.py



## ⚙️ Installation Guide

```bash
git clone https://github.com/your-username/E-Shoper.git
cd E-Shoper

# Virtual Environment (Optional but recommended)
python -m venv venv
source venv/bin/activate      # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Create superuser
python manage.py createsuperuser

# Run server
python manage.py runserver

Open your browser and go to:
👉 http://127.0.0.1:8000/ — User site
👉 http://127.0.0.1:8000/admin/ — Admin login
🔐 Admin Panel Usage

Use Django admin to:

    Add/Edit/Delete Categories

    Add/Edit/Delete Products

    View Orders


