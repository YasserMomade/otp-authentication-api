# Laravel SMS OTP Authentication API

A RESTful authentication API built with Laravel that allows users to register and log in using their mobile phone number and a One-Time Password (OTP) sent via SMS.  
The system is integrated with **mozeSMS** for reliable OTP delivery and supports managing personal user information.

---

## 🚀 Features

- User registration using mobile number
- Login via SMS-based OTP (One-Time Password)
- OTP generation and verification
- Integration with **mozeSMS** SMS gateway
- Secure API authentication
- User profile management:
  - Full name
  - Date of birth
  - Gender
  - Province
  - Email address
- RESTful API architecture
- Clean and scalable Laravel project structure
  
---

## 🛠️ Technologies Used

- **Laravel** (Backend framework)
- **PHP**
- **MySQL (Database)
- **mozeSMS API** (SMS & OTP delivery)
- **REST API**
- **JSON**
  
---

## 📌 Use Case

This project is ideal for applications that require:
- Passwordless authentication
- Mobile-first user registration
- Secure login via SMS OTP
- Scalable authentication APIs for web or mobile apps

  ---

## 🔐 Authentication Flow

1. User submits their mobile number.
2. The system generates a One-Time Password (OTP).
3. OTP is sent via SMS using **mozeSMS**.
4. User submits the OTP for verification.
5. Upon successful verification, the user is authenticated.
6. User can create or update personal profile information.


