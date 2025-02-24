# 🚀 Laravel Custom Authentication with Email Verification  

This repository demonstrates how to implement a **custom authentication system** in Laravel **with email verification**.  
Unlike Laravel's default authentication, this approach gives **full control** over the authentication process.  

---

## 📌 Features  

✔️ **User Registration with Email Verification**  
✔️ **Secure Login & Logout Functionality**  
✔️ **Send Verification Email**  
✔️ **Middleware Protection for Unverified Users**  
✔️ **Built with Laravel 11**  
✔️ **Fully customizable authentication system**  

---

## 📄 Installation  

### 1️⃣ **Clone the Repository**  
```bash
git clone https://github.com/your-username/laravel-auth.git
cd laravel-auth
2️⃣ Install Dependencies
bash
Copy
Edit
composer install
3️⃣ Configure Environment
Copy the .env.example file and update your database & mail settings:

bash
Copy
Edit
cp .env.example .env
Update the .env file:

env
Copy
Edit
APP_NAME="Laravel Auth"  
APP_URL=http://127.0.0.1:8000  

DB_CONNECTION=mysql  
DB_HOST=127.0.0.1  
DB_PORT=3306  
DB_DATABASE=your_database  
DB_USERNAME=your_username  
DB_PASSWORD=your_password  

MAIL_MAILER=smtp  
MAIL_HOST=smtp.example.com  
MAIL_PORT=587  
MAIL_USERNAME=your_email@example.com  
MAIL_PASSWORD=your_password  
MAIL_ENCRYPTION=tls  
MAIL_FROM_ADDRESS=your_email@example.com  
MAIL_FROM_NAME="Your App Name"  
4️⃣ Run Migrations
bash
Copy
Edit
php artisan migrate
5️⃣ Generate Application Key
bash
Copy
Edit
php artisan key:generate
6️⃣ Start the Server
bash
Copy
Edit
php artisan serve
