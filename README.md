# 📚 Bundle Book Store

**Bundle Book Store** is a full-featured e-commerce web application built with **ASP.NET Core MVC**, designed to provide a seamless and intuitive online shopping experience for book lovers. 

---

## ✨ Features

- 🛒 Browse and search for books by category, author, or title
- 📦 Add to cart, remove items, and update quantities
- 🔐 User registration, login, and role-based authorization (Admin / Customer)
- 📚 Admin dashboard for managing inventory, categories, and orders
- 💳 Checkout system with order confirmation
- 🔍 Pagination and filtering
- 📈 Responsive and clean UI built with Bootstrap

---

## 🛠️ Tech Stack

- **Backend:** ASP.NET Core MVC, Entity Framework Core
- **Frontend:** HTML, CSS, JavaScript, Bootstrap
- **Database:** SQL Server / SQLite (for dev/testing)
- **Authentication:** ASP.NET Core Identity
- **IDE:** Visual Studio / VS Code

---

## 🚀 Getting Started

### Prerequisites

- [.NET 6 SDK or later](https://dotnet.microsoft.com/download)
- [SQL Server or SQLite](https://www.sqlite.org/index.html)
- [Visual Studio 2022](https://visualstudio.microsoft.com/) (recommended)

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/bundle-book-store.git
   cd bundle-book-store
   ```

2. **Update the `appsettings.json` with your DB connection string**

3. **Run migrations**

   ```bash
   dotnet ef database update
   ```

4. **Run the application**

   ```bash
   dotnet run
   ```

5. Visit `https://localhost:5001` in your browser.

---

## 🔑 Default Admin Credentials

```bash
Email: admin@bundle.com
Password: Admin@123
```

> ⚠️ Be sure to change this in production.

---

## 📁 Project Structure

```
/Controllers       --> MVC Controllers
/Models            --> Entity models and view models
/Views             --> Razor views (UI templates)
/Data              --> DB context and seeders
/wwwroot           --> Static files (CSS, JS, images)
/Areas/Admin       --> Admin area for managing books, orders, users
```

---

## 📌 Future Improvements

* Payment gateway integration (e.g., Stripe, PayFast)
* Book ratings and reviews
* Wishlist and user profiles
* RESTful API for mobile integration
* Email notifications

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

Developed by [Serge Thomas](https://github.com/SergeThomas)
Part of my journey into full-stack development with ASP.NET Core.
