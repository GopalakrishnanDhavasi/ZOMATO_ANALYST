# 🍽️ Zomato Database & REST API

This project is a **Zomato-like food ordering and analytics system** built with **Python (Flask)** for the backend and **MySQL** for data storage.  
It allows customers to place orders, manage items, and analyze business data such as revenue, payments, and top customers.

---

## 🚀 Features

### Backend (Flask REST API)
- `POST /place_order` → Place a new order with cart items and delivery address.
- `GET /orders` → Retrieve all orders.
- Analytics queries for:
  - Top customers by total revenue
  - Popular food categories
  - Payment insights

### Database (MySQL Schema)
- **categories** → food categories (e.g., Biryani, Paneer, Drinks)  
- **customers** → customer details (name, phone, email)  
- **items** → menu items with category reference  
- **orders** → order metadata (customer, date, delivery address)  
- **order_items** → mapping of orders to items with quantity and price  
- **payments** → payment details (order_id, amount, method, status)  

---

## 🛠️ Tech Stack

- **Backend**: Python (Flask)  
- **Database**: MySQL  
- **Frontend**: HTML, CSS, JavaScript (served via Flask templates)  

---

## 📂 Project Structure
<img width="600" height="225" alt="image" src="https://github.com/user-attachments/assets/6ba04943-a093-43c6-8fc9-30c6aeb1c6a7" />


