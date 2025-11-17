# Pharmacy-Managemnt-System-Project



### ** Project Overview**

* A desktop-based Pharmacy Management System built using **Python (Tkinter)**.
* Manages medicines, company details, stock, pricing, and expiry dates.
* Integrated with **MySQL database** for storing and retrieving records.
* Provides GUI-based CRUD operations for both medicine categories and pharmacy records.

---

## ** Features**

* **Add, Update, Delete, Reset** medicine records.
* Store complete medicine information:

  * Reference Number
  * Company Name
  * Type of Medicine
  * Medicine/Tablet Name
  * Lot Number
  * Issue Date & Expiry Date
  * Usage details
  * Side effects
  * Precautions & Warnings
  * Dosage
  * Price
  * Quantity
* Medicine master list where new medicines can be added separately.
* **Search functionality** based on:

  * Reference No
  * Medicine Name
  * Lot Number
* Integrated **Treeview tables** to display data with scrollbars.
* Handles exceptions and user validations.

---

## **Technologies Used**

* **Python**
* **Tkinter** (GUI Framework)
* **Pillow (PIL)** for image handling
* **MySQL Connector** for database operations
* **MySQL Database**
* **ttk widgets** for modern UI components

---

## **🛢 Database Used**

### **Tables**

* **medicine**

  * Stores reference numbers and medicine names.
* **pharmacy**

  * Stores complete medicine details used in inventory.

---

## ** Core Functionalities**

* Insert new medicine data into MySQL.
* Fetch and load data automatically at startup.
* Select data from table → auto-fill in form.
* Search data dynamically using SQL queries.
* Remove or update existing entries.
* Clear input fields using Reset button.
* Exit confirmation popup using messagebox.

---

## ** UI Features**

* Uses **frames**, **labels**, **buttons**, **entry widgets**, **Treeview** tables.
* Embedded image assets (logo, banners, icons).
* Clean layout divided into:

  * Header Section
  * Left Data Entry Section
  * Right Medicine Management Section
  * Bottom Buttons Section
  * Main Data Table

---

## ** How to Run**

* Install required modules:

  * `pip install pillow`
  * `pip install mysql-connector-python`
* Create MySQL database:

  * Database: **mydata2**
  * Tables: **medicine**, **pharmacy**
* Place image files (`logos.jpg`, `photo.jfif`, etc.) in project folder.
* Run:
* 
  python yourfilename.py




## ** Summary**

* Fully functional pharmacy inventory software.
* Helps manage medicine stock and company records.
* Suitable for small medical stores or educational projects.
* Provides smooth GUI experience with MySQL backend.


