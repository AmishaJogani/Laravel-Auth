# 🚀 Laravel Custom Authentication with Email Verification  


This repository demonstrates how to implement a **custom authentication system** in Laravel **with email verification**.  
Unlike Laravel's default authentication, this approach gives **full control** over the authentication process.  

---

##  Features  

- **User Registration with Email Verification**  
- **Secure Login & Logout Functionality**  
- **Send Verification Email**  
- **Middleware Protection for Unverified Users**  
- **Built with Laravel 11**  
- **Fully Customizable Authentication System**  

---

##  Installation  

### 1️ Clone the Repository  
```bash
git clone https://github.com/your-username/laravel-auth.git
cd laravel-auth
```

### 2️ Install Dependencies  
```bash
composer install
```

### 3️ Configure Environment  
Copy the `.env.example` file and set up your environment:  
```bash
cp .env.example .env
```
Edit the `.env` file to configure your database and mail settings:  
```ini
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
```

### 4️ Run Migrations  
```bash
php artisan migrate
```

### 5️ Generate Application Key  
```bash
php artisan key:generate
```

### 6️ Start the Server  
```bash
php artisan serve
```
Your application will now be accessible at: **http://127.0.0.1:8000**  

---

## 🔑 API Endpoints  

| Method | Route | Description |
|--------|-------|------------|
| **POST** | `/register` | Register a new user |
| **POST** | `/login` | Authenticate a user |
| **GET** | `/verify-email/{id}/{hash}` | Verify email address |
| **POST** | `/resend-verification` | Resend verification email |
| **POST** | `/logout` | Logout the user |

---

##  License  
This project is **open-source** and available under the **MIT License**.  
