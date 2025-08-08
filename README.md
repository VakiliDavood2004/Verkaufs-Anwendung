# **🇩🇪 README.md auf Deutsch**


## 🛍️ Verkaufs- und Bestellverwaltungssystem

Eine leistungsstarke Desktop-Anwendung zur Verwaltung von Bestellungen, Kunden, Produkten und Dienstleistungen mit einer modernen grafischen Benutzeroberfläche und integrierter Datenbank.  
Entwickelt mit **Python**, **PyQt5** und **SQLite**.

---

## 🚀 Hauptfunktionen

- Bestellungen mit vollständigen Details erfassen
- Automatische Berechnung des Gesamtpreises (Produkt × Menge + Dienstleistung)
- Verwaltung von Kunden, Produkten und Dienstleistungen
- Rechnungserstellung und Verkaufsberichte
- Zusätzliche Tools wie Taschenrechner, Notizblock, Kalender und Chat
- Einfache, schnelle und erweiterbare Benutzeroberfläche

---

## 🧩 Modulübersicht

| Modul | Beschreibung |
|-------|--------------|
| `main.py` | Einstiegspunkt der Anwendung; lädt das Hauptfenster und verbindet die Module |
| `order_module.py` | Formular zur Erfassung von Bestellungen mit Produkt-, Kunden- und Dienstleistungsauswahl |
| `product_module.py` | Formular zum Hinzufügen oder Bearbeiten von Produkten |
| `customer_module.py` | Formular zum Hinzufügen oder Bearbeiten von Kunden |
| `service_module.py` | Formular zum Hinzufügen oder Bearbeiten von Dienstleistungen |
| `order_manager_module.py` | Anzeige und Verwaltung der Bestellungen mit Such- und Löschfunktion |
| `product_list_module.py` | Anzeige der verfügbaren Produkte in Listenform |
| `customer_manager_module.py` | Vollständige Verwaltung der Kundendaten |
| `service_manager_module.py` | Verwaltung der angebotenen Dienstleistungen |
| `invoice_module.py` | Erstellung offizieller Rechnungen für Bestellungen |
| `report_module.py` | Verkaufsberichte nach Datum, Kunde oder Produkt |
| `sales_analysis_module.py` | Statistische Analyse der Verkäufe mit Diagrammen und Kennzahlen |
| `discount_tax_calculator.py` | Berechnung von Rabatten und Steuern für Bestellungen |
| `advanced_calculator_module.py` | Erweiterter Taschenrechner für manuelle Berechnungen |
| `notepad_module.py` | Integrierter Notizblock zum Speichern von Texten |
| `clock_calendar_widget.py` | Anzeige von Uhrzeit und Kalender im Programmfenster |
| `chat_module.py` | Einfacher Chat mit dem Benutzer oder integriertem Assistenten |
| `feedback_form_module.py` | Formular zur Erfassung von Nutzerfeedback |
| `help_module.py` | Hilfe und Anleitung zur Nutzung der einzelnen Programmteile |
| `delete_product_module.py` | Löschen von Produkten aus der Datenbank |
| `user_module.py` | Benutzerverwaltung und Zugriffskontrolle (optional für mehrere Nutzer) |
| `icon.ico` | Programmsymbol für Fenster und Taskleiste |
| `sales.db` | SQLite-Datenbank mit Tabellen für Bestellungen, Kunden, Produkte und Dienstleistungen |
| `README.md` | Projektdokumentation für Entwickler und Nutzer |

---

## 🛠️ Installation und Ausführung

### Voraussetzungen:
- Python 3.7 oder höher
- PyQt5

### PyQt5 installieren:

pip install PyQt5

### Programm starten:

python main.py

---

## 📌 Entwicklungshinweise

- Alle Formulare basieren auf der Klasse `QWidget` und können in `QMainWindow` integriert werden.
- Die SQLite-Datenbank wird automatisch erstellt und ist portabel.
- Neue Funktionen können einfach durch Erstellen eines neuen Moduls und Einbindung in `main.py` hinzugefügt werden.

---

## 👨‍💻 Entwickler

**Davood Vakili**  
Wenn dir dieses Projekt gefällt oder du es erweitern möchtest, helfe ich dir gerne weiter oder arbeite mit dir zusammen. 

---

## 🧠 Zukünftige Erweiterungen (TODO)

- Verbindung zu einer Online-Datenbank (MySQL/PostgreSQL)
- Benutzeranmeldung mit Passwort und Zugriffskontrolle
- Versand von Rechnungen per E-Mail
- Entwicklung einer mobilen Version mit Kivy oder Flutter


---



# **🇬🇧 README.md in English**


## 🛍️ Sales & Order Management System

A powerful desktop application for managing orders, customers, products, and services with a modern graphical user interface and built-in database.  
Developed using **Python**, **PyQt5**, and **SQLite**.

---

## 🚀 Key Features

- Register orders with full details
- Automatically calculate total price (Product × Quantity + Service)
- Manage customers, products, and services
- Generate invoices and sales reports
- Extra tools like calculator, notepad, calendar, and chat
- Simple, fast, and extensible user interface

---

## 🧩 Module Overview

| Module | Description |
|--------|-------------|
| `main.py` | Entry point of the application; loads the main window and connects modules |
| `order_module.py` | Order form with product, customer, and service selection and total price calculation |
| `product_module.py` | Add or edit product information |
| `customer_module.py` | Add or edit customer information |
| `service_module.py` | Add or edit service information |
| `order_manager_module.py` | View and manage orders with search and delete functionality |
| `product_list_module.py` | Display available products in a list |
| `customer_manager_module.py` | Full customer data management |
| `service_manager_module.py` | Manage available services |
| `invoice_module.py` | Generate official invoices for orders |
| `report_module.py` | Generate sales reports by date, customer, or product |
| `sales_analysis_module.py` | Statistical analysis of sales with charts and metrics |
| `discount_tax_calculator.py` | Calculate discounts and taxes for orders |
| `advanced_calculator_module.py` | Advanced calculator for manual computations |
| `notepad_module.py` | Built-in notepad for saving notes and reminders |
| `clock_calendar_widget.py` | Display time and calendar inside the application |
| `chat_module.py` | Simple chat interface with user or built-in assistant |
| `feedback_form_module.py` | Form to collect user feedback |
| `help_module.py` | Help and guidance for using different parts of the application |
| `delete_product_module.py` | Delete products from the database with confirmation |
| `user_module.py` | Manage users and access levels (optional for multi-user setup) |
| `icon.ico` | Application icon for windows and taskbar |
| `sales.db` | SQLite database containing tables for orders, customers, products, and services |
| `README.md` | Project documentation for developers and users |

---

## 🛠️ Installation & Execution

### Requirements:
- Python 3.7 or higher
- PyQt5

### Install PyQt5:

pip install PyQt5

### Run the application:

python main.py

---

## 📌 Development Notes

- All forms are based on `QWidget` and can be integrated into `QMainWindow`.
- The SQLite database is created automatically and is portable.
- To add new features, simply create a new module and import it in `main.py`.
- The code is modular and easy to maintain or extend.

---

## 👨‍💻 Developer

**Davood Vakili**  
If you like this project or want to expand it, I’d be happy to help or collaborate with you. 

---

## 🧠 Future Enhancements (TODO)

- Connect to an online database (MySQL/PostgreSQL)
- Add user login with password and access control
- Send invoices via email
- Build a mobile version using Kivy or Flutter



---


# 🛍️ سیستم مدیریت فروش و سفارش‌ها

یک نرم‌افزار دسکتاپی قدرتمند برای مدیریت سفارش‌ها، مشتریان، محصولات و خدمات با رابط کاربری گرافیکی مدرن و پایگاه داده داخلی.  
توسعه‌یافته با استفاده از **Python**، **PyQt5** و **SQLite**.

---

## 🚀 امکانات کلیدی

- ثبت سفارش با جزئیات کامل
- محاسبه خودکار مبلغ کل (محصول × تعداد + خدمات)
- مدیریت مشتریان، محصولات و خدمات
- صدور فاکتور و گزارش‌گیری از فروش‌ها
- ابزارهای جانبی مانند ماشین‌حساب، دفترچه یادداشت، تقویم و گفت‌وگو
- رابط کاربری ساده، سریع و قابل توسعه

---

## 🧩 معرفی کامل ماژول‌ها

| نام ماژول | توضیحات |
|-----------|----------|
| `main.py` | نقطه شروع برنامه؛ بارگذاری پنجره اصلی و اتصال ماژول‌ها |
| `order_module.py` | فرم ثبت سفارش شامل انتخاب محصول، مشتری، خدمات و محاسبه مبلغ کل |
| `product_module.py` | افزودن یا ویرایش اطلاعات محصولات |
| `customer_module.py` | افزودن یا ویرایش اطلاعات مشتریان |
| `service_module.py` | افزودن یا ویرایش اطلاعات خدمات |
| `order_manager_module.py` | نمایش و مدیریت سفارش‌ها با قابلیت جستجو و حذف |
| `product_list_module.py` | نمایش لیست محصولات موجود به صورت جدولی |
| `customer_manager_module.py` | مدیریت کامل اطلاعات مشتریان |
| `service_manager_module.py` | مدیریت خدمات قابل ارائه |
| `invoice_module.py` | صدور فاکتور رسمی برای سفارش‌ها |
| `report_module.py` | گزارش‌گیری از فروش‌ها بر اساس تاریخ، مشتری یا محصول |
| `sales_analysis_module.py` | تحلیل آماری فروش‌ها با نمودار و آمار دقیق |
| `discount_tax_calculator.py` | محاسبه تخفیف و مالیات برای سفارش‌ها |
| `advanced_calculator_module.py` | ماشین‌حساب پیشرفته برای محاسبات دستی |
| `notepad_module.py` | دفترچه یادداشت داخلی برای ذخیره متن‌ها و یادآوری‌ها |
| `clock_calendar_widget.py` | نمایش ساعت و تقویم در محیط برنامه |
| `chat_module.py` | گفت‌وگوی ساده با کاربر یا دستیار داخلی |
| `feedback_form_module.py` | فرم دریافت بازخورد از کاربران |
| `help_module.py` | راهنمای استفاده از بخش‌های مختلف برنامه |
| `delete_product_module.py` | حذف محصولات از پایگاه داده با تأیید کاربر |
| `user_module.py` | مدیریت کاربران و سطح دسترسی (در صورت نیاز به چند کاربر) |
| `icon.ico` | آیکون برنامه برای نمایش در پنجره‌ها و نوار وظیفه |
| `sales.db` | پایگاه داده SQLite شامل جداول سفارش‌ها، مشتریان، محصولات و خدمات |
| `README.md` | مستندات پروژه برای توسعه‌دهندگان و کاربران نهایی |

---

## 🛠️ نصب و اجرا

### پیش‌نیازها:
- Python نسخه ۳.۷ یا بالاتر
- کتابخانه PyQt5

### نصب PyQt5:

pip install PyQt5

### اجرای برنامه:

python main.py

---

## 📌 نکات توسعه

- تمام فرم‌ها بر پایه کلاس `QWidget` طراحی شده‌اند و قابل اتصال به `QMainWindow` هستند.
- پایگاه داده SQLite به صورت خودکار ساخته می‌شود و قابل انتقال است.
- برای افزودن قابلیت‌های جدید، کافیست یک ماژول جدید ایجاد کرده و در `main.py` فراخوانی کنید.
- ساختار ماژولار کدها توسعه و نگهداری را آسان می‌کند.

---

## 👨‍💻 توسعه‌دهنده

**داوود وکیلی**  
اگر این پروژه برایتان مفید بود یا قصد توسعه‌ی بیشتر آن را دارید، خوشحال می‌شوم در کنار شما باشم یا همکاری کنیم. 

---

## 🧠 پیشنهادات توسعه (TODO)

- اتصال به پایگاه داده آنلاین (MySQL/PostgreSQL)
- افزودن قابلیت ورود کاربران با رمز عبور و سطح دسترسی
- ارسال فاکتور به ایمیل مشتری
- طراحی نسخه موبایل با استفاده از Kivy یا Flutter
