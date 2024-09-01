# Angular E-commerce Project

![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![RxJS](https://img.shields.io/badge/RxJS-B7178C?style=for-the-badge&logo=reactivex&logoColor=white)

An e-commerce web application built with Angular, featuring user authentication, product browsing, shopping cart functionality, and order management.

## 📋 Table of Contents

- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Components](#-components)
- [Services](#-services)
- [Additional Information](#-additional-information)

## 🚀 Features

- User authentication (login, register, forgot password)
- Product browsing and searching
- Shopping cart functionality
- Order management
- Brand and category filtering
- Responsive design

## 💻 Tech Stack

- Angular
- RxJS
- ngx-owl-carousel-o
- ngx-toastr
- ngx-spinner
- Angular Material

## 📁 Project Structure

```
src/
├── app/
│   ├── components/
│   ├── setting/
│   ├── app-routing.module.ts
│   ├── app.component.css
│   ├── app.component.html
│   ├── app.component.spec.ts
│   ├── app.component.ts
│   ├── app.module.ts
│   ├── auth.guard.spec.ts
│   ├── auth.guard.ts
│   ├── auth.service.ts
│   ├── cart.service.ts
│   ├── headers-interceptor.interceptor.spec.ts
│   ├── headers-interceptor.interceptor.ts
│   ├── products.ts
│   ├── products.service.spec.ts
│   ├── products.service.ts
│   ├── search.pipe.spec.ts
│   └── search.pipe.ts
```

## 🏁 Getting Started

1. Clone the repository
   ```
   git clone https://github.com/Moemen99/E-Commerce-app
   ```
2. Install dependencies
   ```
   npm install
   ```
3. Start the development server
   ```
   ng serve
   ```
4. Open your browser and navigate to `http://localhost:4200/`

## 🧩 Components

- Home
- Footer
- Navbar
- Login
- Register
- Brands
- Categories
- Cart
- ProductDetails
- MainSlide
- FeaturedProducts
- ForgotPasswords
- CategoryDetails
- AllOrders
- BrandDetails

## 🛠 Services

- AuthService
- CartService
- ProductsService

## ℹ️ Additional Information

- **Pipes**: SearchPipe
- **Interceptors**: HeadersInterceptorInterceptor
- **Routing**: The application uses Angular's routing module for navigation
- **Styling**: Combination of custom CSS and Angular Material components
- **Testing**: Run `ng test` to execute the unit tests via Karma
- **Build**: Run `ng build` to build the project. Build artifacts will be stored in the `dist/` directory

