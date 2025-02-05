# 📚 Library Management System

A simple yet robust Library Management System built to manage books, users, and transactions efficiently. Follow this guide to set up and run the project on your local machine.

---

## 🚀 How to Run the Library Management System Project

### 1. **Download the Project**
- **Download** and **unzip** the file on your local system.
- **Copy** the `library` folder from the unzipped directory.

### 2. **Move to Root Directory**
- Place the `library` folder inside the root directory of your local web server:
  - For **XAMPP**: Place it in the `htdocs` folder.
  - For **WAMP**: Place it in the `www` folder.

---

## ⚙️ Database Configuration

### 1. **Open PHPMyAdmin**
- Open PHPMyAdmin by navigating to: [http://localhost/phpmyadmin](http://localhost/phpmyadmin)

### 2. **Create a Database**
- Create a new database named **`library`**.

### 3. **Import Database**
- In the `library` database, **import** the SQL file:
  - `library.sql` (available inside the zip package).

---

## 🌐 Accessing the System

### For Users:
1. Open your browser and go to:
   - **[http://localhost/library](http://localhost/library)**

### Login Details for Users:
| **Username**          | **Password**  |
|-----------------------|---------------|
| `test@gmail.com`       | `Test@123`    |

---

## 🔐 Admin Panel Access

The admin can manage the library system through the admin panel:

1. Open your browser and go to:
   - **[http://localhost/library/admin](http://localhost/library/admin)**

### Login Details for Admin:
| **Username** | **Password**  |
|--------------|---------------|
| `admin`      | `Test@123`    |

---

## 🛠️ Technologies Used

- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Backend**: PHP
- **Database**: MySQL (via PHPMyAdmin)
- **Server**: Apache (XAMPP, WAMP, or any local server)

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to explore, modify, and improve the Library Management System!
