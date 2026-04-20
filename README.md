# 🪑 Shreeji Furniture Website

## 📌 Project Overview
Shreeji Furniture is a dynamic web-based application developed using PHP and MySQL. The website is designed to showcase furniture products, categories, and company details in an attractive and user-friendly interface.

This project demonstrates full-stack web development skills including frontend design, backend logic, and database integration.

---

## 🚀 Features

- 🖼️ Dynamic Homepage with Image Slider
- 📂 Product Categories Display
- 📞 Contact Page for User Queries
- ℹ️ About Us Page
- 🔗 Reusable Components (Header & Footer)
- 🗄️ MySQL Database Integration
- 📱 Responsive Design using Bootstrap

---

## 🛠️ Technologies Used

### Frontend:
- HTML5
- CSS3
- Bootstrap
- JavaScript
- Owl Carousel (for slider)

### Backend:
- PHP

### Database:
- MySQL

---

## 📂 Project Structure
Shreeji_Furniture/
│── index.php # Homepage
│── about.php # About page
│── categories.php # Product categories
│── contact.php # Contact form
│── header.php # Common header
│── footer.php # Common footer
│── connect.php # Database connection
│── admin/ # Admin images & data
│── lib/ # External libraries


---

## ⚙️ Installation & Setup

### Step 1: Clone Repository
git clone https://github.com/your-username/shreeji-furniture.git


Step 2: Move to Server Directory
Copy project folder to:
XAMPP → htdocs
WAMP → www


tep 3: Setup Database
1)Open phpMyAdmin
2)Create a database:sf_db


Step 4: Configure Database Connection

Open connect.php and update:
$host = "localhost";
$username = "root";
$password = "";
$database = "sf_db";


Step 5: Run Project

Open browser:
http://localhost/Shreeji_Furniture/
