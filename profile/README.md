# 💊 PharmaHub Ecommerce Platform

**PharmaHub** is a full-featured ecommerce platform designed for pharmacy owners to sell medicines and beauty products online. It helps users easily find and order medicines from the nearest pharmacy.

This project is divided into two main repositories:

- 🎯 [Frontend - Angular App](https://github.com/PharmaHub-Ecommerce-Angular-WebAPI/PharmaHub-Ecommerce-Angular)
- 🔧 [Backend - ASP.NET Core Web API](https://github.com/PharmaHub-Ecommerce-Angular-WebAPI/PharmaHub-Ecommerce-WebAPI)

---

## 🔍 Overview

PharmaHub allows pharmacies to create and manage their own online stores, while customers can:

- Search for medicines and see which nearby pharmacy sells them
- Register, log in, and verify email accounts
- Browse products, add them to cart, and complete payment securely via Stripe
- Upload prescriptions or browse product packages

---

## 🧰 Tech Stack

| Layer      | Technology                                      |
|------------|--------------------------------------------------|
| Frontend   | Angular 18, TypeScript, Bootstrap, RxJS          |
| Backend    | ASP.NET Core Web API, Entity Framework Core      |
| Database   | Microsoft SQL Server                             |
| Auth       | JWT, Role-Based Access, Email Confirmation       |
| Payments   | Stripe                                           |
| Media      | Cloudinary                                       |

---

## 🚀 Features

- 🛒 **Ecommerce functionalities** (search, filter, cart, payments)
- 🔐 **JWT Authentication & Role-based Authorization**
- 📩 **Email Confirmation using SMTP**
- 💳 **Stripe Payment Integration**
- ☁️ **Cloudinary Image Uploads**
- 🧠 **Advanced Search** (Exact, Partial, Fuzzy Matching)
- 📦 **Product Packages** (One-to-Many Weak Entities)

---

## 📂 Repositories

### 🔧 Backend: [.NET Core Web API](https://github.com/PharmaHub-Ecommerce-Angular-WebAPI/PharmaHub-Ecommerce-WebAPI)

- N-Tier architecture with clean separation of concerns
- Secure authentication using JWT
- CRUD APIs for pharmacies, products, categories, etc.
- Stripe and Cloudinary integrations
- Connected to a deployed SQL Server database

### 🎯 Frontend: [Angular 14 App](https://github.com/PharmaHub-Ecommerce-Angular-WebAPI/PharmaHub-Ecommerce-Angular)

- Fully responsive UI for users and pharmacy owners
- Angular guards, interceptors, and JWT token storage
- Form validation, modals, filtering, sorting, and search
- Integrated with the backend API




---

## 📄 License

This project is licensed under the MIT License - see the individual repo LICENSE files for more details.
