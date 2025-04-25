# 🛍️ E-commerce Database Design Project

## 🎯 Objective
This project is aimed at mastering relational database concepts by collaboratively developing a real-world **E-commerce Database** system.

---

## 📐 Overview
We designed a comprehensive Entity-Relationship Diagram (ERD) and implemented the database schema using **MySQL**. This system captures all essential components of an e-commerce platform—from product listings and variations to attributes and stock details.

---

## 🚧 What We Did
- ✅ Designed an intuitive **ERD** with clearly defined entities, relationships, and constraints.
- ✅ Created a detailed **SQL script (`ecommerce.sql`)** to implement the schema.
- ✅ Populated tables with sample data and relevant image URLs.
- ✅ Used **GitHub** for version control and seamless collaboration.

---

## 🗃️ Key Database Tables
| Table | Description |
|-------|-------------|
| `brand` | Stores brand names. |
| `product_category` | Classifies products into categories. |
| `product` | Holds core product details. |
| `product_image` | Stores image URLs for each product. |
| `color` | Lists available product colors. |
| `size_category` | Groups size types (e.g., clothing sizes). |
| `size_option` | Lists specific size values. |
| `product_variation` | Links products to color and size variations. |
| `product_item` | Represents a specific variation in stock. |
| `attribute_category` | Groups product attributes (e.g., tech specs). |
| `attribute_type` | Defines the type of each attribute. |
| `product_attribute` | Stores custom attribute values per product. |

---

## 📌 Entity Relationship Diagram (ERD)
This ERD was reverse-engineered from the actual SQL schema using MySQL Workbench:

![ERD Diagram](Assets/ERD.png)

---

## 📁 Repository Contents
- `ecommerce.sql` – Full SQL schema creation script
- `Assets/ERD.png` – ER diagram visual
- `README.md` – Project overview and documentation
