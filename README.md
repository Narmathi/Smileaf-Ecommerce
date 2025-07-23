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
     ```
     database.default.hostname = localhost
     database.default.database = your_db_name
     database.default.username = your_db_user
     database.default.password = your_db_pass
     ```
   - Add API keys for Razorpay and 2FA in `.env`:
     ```
     RAZORPAY_KEY=your_razorpay_key
     RAZORPAY_SECRET=your_razorpay_secret
     SMS_API_KEY=your_2fa_api_key
     ```

3. **Install Dependencies**
   ```bash
   composer install
   ```

4. **Run Migrations**
   ```bash
   php spark migrate
   ```

5. **Serve the Application**
   ```bash
   php spark serve
   ```
   Visit [http://localhost:8080](http://localhost:8080)

---

## 🔐 API Authentication

This project uses **JWT** for securing API endpoints. Include your JWT token in headers:

```
Authorization: Bearer <your_token>
```

---

## 📸 Screenshots

| User View                         | Admin Dashboard                |
|------------------------------------|---------------------------------|
| ![User View](screenshots/user.png) | ![Admin Dashboard](screenshots/admin.png) |

*(Add your screenshots in the `/screenshots` folder)*

---

## 📖 License

This project is licensed under the [MIT License](LICENSE).

---

## 👩‍💻 Author

- **Narmathi GP** – [GitHub](https://github.com/your-username) | [LinkedIn](https://linkedin.com/in/your-link)
