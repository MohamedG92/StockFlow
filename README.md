<div align="center">

# 📦 StockFlow

**Inventory & stock-movement manager: PHP REST API + MySQL + vanilla JavaScript dashboard**

![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat-square&logo=chartdotjs&logoColor=white)

</div>

## ✨ Features

- **Products**: create, edit and delete products with reference, category, price and a low-stock threshold
- **Categories** to organise the catalogue
- **Stock movements**: record stock in / stock out with quantity, user and comment; full history per product
- **Low-stock alerts** when a product falls under its threshold
- **Search and filters** on products and movements
- **Dashboard charts** (bar + line) with Chart.js
- **CSV export**
- **REST API** in PHP (`GET` / `POST` / `PUT` / `DELETE`) using PDO prepared statements

## 🗂️ Structure

```
api/          PHP REST endpoints (produits, categories, mouvements, stats) + db.php
js/           app logic, UI rendering, charts, API config
styles/       main styles, components, animations
setup.php     creates the database and tables (categories, produits, mouvements)
index.html    single-page dashboard
```

## 🚀 Run it locally

1. Install **XAMPP** (or any PHP + MySQL/MariaDB stack) and start Apache + MySQL.
2. Copy the project into `htdocs/StockFlow`.
3. Open `http://localhost/StockFlow/setup.php` once to create the `stockflow_db` database.
4. Open `http://localhost/StockFlow/`.

Database settings are in `api/db.php` (default: `localhost`, user `root`, no password).

---

<div align="center">Made by <a href="https://github.com/MohamedG92">Mohamed Iraqi Houssaini</a></div>
