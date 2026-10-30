# 🏭 Warehouse Catalogue Management System

A lightweight, browser-based **Warehouse Catalogue Management System** built entirely with HTML, CSS, and vanilla JavaScript — no backend or dependencies needed.

## 📋 Features

- ➕ **Add Products** — Register new products with a unique ID, name, price, and warehouse assignment
- ✏️ **Edit Products** — Load product details into the form for modification
- 🔄 **Update Products** — Save updated product information back to the catalogue
- 🗑️ **Delete Products** — Remove a product from the catalogue instantly
- 📊 **Live Product Table** — The product list refreshes automatically after every action

## 🚀 Getting Started

No installation required. Open directly in any modern browser:

```
house/index.html
```

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| HTML5 | Structure & Layout |
| CSS3 | Styling (light blue headers, responsive table) |
| JavaScript (Vanilla) | CRUD Logic & DOM Manipulation |

## 📁 Project Structure

```
house/
└── index.html    # All-in-one HTML file (HTML + CSS + JS)
```

## 💡 How to Use

1. **Add a Product** — Fill in Product ID, Name, Price, and select a Warehouse, then click **Add Product**
2. **Edit a Product** — Click **Edit** on any row to load its data into the form
3. **Update a Product** — Modify the fields and click **Update Product**
4. **Delete a Product** — Click **Delete** on any row to remove it

## ✅ Validations

- Product ID must be a positive integer and unique
- Product Name cannot be empty
- Price must be a positive number
- Warehouse selection is required

## 🏬 Warehouses Supported

- Warehouse 1
- Warehouse 2

## 📌 Notes

- Data is stored in-memory (JavaScript array) and resets on page refresh
- No external libraries or internet connection required
