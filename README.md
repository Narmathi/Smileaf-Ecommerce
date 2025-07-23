# 🌿 Smileleaf E-Commerce

Smileleaf E-Commerce is a full-featured e-commerce platform built with **CodeIgniter 4 (PHP Framework)**. It provides a seamless shopping experience with integrated payment gateway (**Razorpay**) and **Two-Factor SMS Authentication** for enhanced security. It also features a powerful Admin Dashboard for managing products, orders, customers, and dynamic website content.

---

## 🚀 Features

### 🛍️ Customer Features
- User registration & login with **JWT token authentication**
- Two-Factor Authentication (2FA) via SMS OTP
- Browse products with categories & subcategories
- Add to cart, checkout, and order tracking
- Payment integration with Razorpay
- Responsive design for mobile & desktop

### 🛠️ Admin Dashboard
- **Product Management**: Add, update, delete products
- **Order Management**: View, process, and update orders
- **Customer Management**: Manage registered users
- **Dynamic Menus/Submenus**: Update navigation dynamically
- **Payment Reports**: View and manage transactions

---

## 🏗️ Tech Stack

| Technology         | Description                        |
|---------------------|------------------------------------|
| **Frontend**        | HTML, CSS, Bootstrap, JavaScript  |
| **Backend**         | PHP (CodeIgniter 4 Framework)     |
| **Database**        | MySQL                             |
| **Authentication**  | JWT Token                         |
| **Payment Gateway** | Razorpay API                      |
| **SMS Gateway**     | Two-Factor API (2FA)              |
| **Admin Panel**     | Bootstrap-based dynamic dashboard |

---

## ⚙️ Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/smileleaf-ecommerce.git
   cd smileleaf-ecommerce
   ```

2. **Setup Environment**
   - Rename `.env.example` to `.env` and configure:
   
   - Add API keys for Razorpay and 2FA in `.env`:
     ```
     RAZORPAY_KEY=your_razorpay_key
     RAZORPAY_SECRET=your_razorpay_secret
     SMS_API_KEY=your_2fa_api_key
     ```

---

## 🔐 API Authentication

This project uses **JWT** for securing API endpoints. Include your JWT token in headers:

```
Authorization: Bearer <your_token>
```


## 👩‍💻 Author

- **Narmathi GP** – [GitHub](https://github.com/Narmathi) | [LinkedIn](https://www.linkedin.com/in/narmathi-gp-a888b31b1)
