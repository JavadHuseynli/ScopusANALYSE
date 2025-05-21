
markdown
Копировать
Редактировать
# 📊 Scopus Analysis System (PHP-Based)

The **Scopus Analysis System** is a web-based platform developed in **PHP** that allows users to upload and analyze bibliometric data exported from the Scopus database. It is designed to assist researchers, academic institutions, and research managers in gaining insights into publication trends, citation metrics, and collaboration patterns.

---

## 🌟 Key Features

- 📥 Upload Scopus-exported CSV files
- 📊 Display publication and citation statistics per year
- 👤 Analyze author productivity and h-index (if applicable)
- 🏫 Group data by affiliations or institutions
- 🌍 Identify international co-authorship trends
- 📤 Export results as downloadable reports (CSV, PDF, or Excel)

---

## 🛠️ Built With

- **PHP 7.x+**
- **MySQL** – for storing and querying bibliographic data
- **Bootstrap** – for responsive frontend
- **Chart.js** – for data visualizations
- **PHPExcel or PhpSpreadsheet** – for Excel export
- **TCPDF** – for PDF generation (optional)

---

## ⚙️ Installation

1. Clone this repository:
```bash
git clone https://github.com/JavadHuseynli/Scopus-Analysis-System.git
Move the project to your local web server (e.g., htdocs or www folder):

bash
Копировать
Редактировать
mv Scopus-Analysis-System /var/www/html/scopus
Import the scopus.sql file into your MySQL database.

Configure your database settings in /config/db.php:

php
Копировать
Редактировать
$host = 'localhost';
$db   = 'scopus';
$user = 'root';
$pass = '';
Open the project in your browser:

arduino
Копировать
Редактировать
http://localhost/scopus
📂 Folder Structure
bash
Копировать
Редактировать
/scopus
├── /config
├── /uploads          ← Scopus CSV files uploaded here
├── /charts           ← Auto-generated graphs
├── /reports          ← Exported reports (Excel, PDF)
├── index.php
├── upload.php
├── analyze.php
├── export.php
└── README.md
🖼️ Example Screenshots
(Add screenshots showing graphs, upload form, report export, etc.)

👨‍💻 Usage
Go to the main page (index.php)

Upload the .csv file downloaded from Scopus

View the visualizations and statistical tables

Download report as PDF or Excel

📤 Export Capabilities
Publication trends by year

Citation count per author

Author-level metrics

Collaboration reports

✅ To Do
 CSV upload & parsing

 Chart visualizations with Chart.js

 Advanced filters by year, journal, and country

 Co-authorship network graph

 Role-based user login system

📜 License
This project is licensed under the MIT License – feel free to use, modify, and share.

📫 Contact
Javad Huseynli
🔗 GitHub: JavadHuseynli
✉️ (Optional email)

📌 Made for academic analysis and research insight in a modern and simple PHP interface.

---
Əgər istəyirsənsə, sənə ayrıca `config/db.php`, `upload.php`, `analyze.php`, və `export.php`
