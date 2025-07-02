# 🛍️ React Product Dashboard

A responsive and interactive Product Management Dashboard built with **React**, **Material UI**, and **React Router v6+**. Supports product listing, searching, adding, editing, deleting, and cart management — all with local storage persistence.

## 🚀 Features

- 🏠 **Product Listing Page** (`/`)
  - Fetches products from [DummyJSON API](https://dummyjson.com/products)
  - Client-side search
  - Product cards showing image, name, category, and price

- 🔍 **Product Details Page** (`/product/:id`)
  - Shows detailed view of a product
  - Add-to-cart functionality

- ➕ **Add Product** (`/add`)
  - Form to add a product (stored in local state + localStorage)
  - Form validation included

- ✏️ **Edit Product** (`/edit/:id`)
  - Prefills the form with existing product data
  - Updates saved products in localStorage

- 🗑️ **Delete Product**
  - Deletes locally added products from the dashboard

- 🛒 **Cart Page** (`/cart`)
  - Lists all items added to cart
  - Quantity support & remove item feature
  - Cart state persisted via `localStorage`

## 🛠️ Tech Stack

- ⚛️ **React** (with Hooks)
- 🌐 **React Router v6**
- 🎨 **Material UI**
- 📦 **LocalStorage** for data persistence
- 🔗 **DummyJSON API** (for initial product data)
