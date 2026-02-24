# 🧳 Tours & Travels Management System (PHP + MySQL)

A **Tours & Travels Management System** built using **PHP and MySQL** that allows users to book tours, get vehicle details, receive quotations, and manage travel requests online. The system supports both customer and agency workflows.

---

## 🚀 Features

- User can search for travel options between locations  
- Customer sends travel request with date and route  
- Admin (travel agency) views requests and provides quotes  
- Customer accepts or rejects quotations  
- Separate pages for historical tours and travel requests

---

## 🛠 Tech Stack

- **Language:** PHP  
- **Database:** MySQL  
- **Web Server:** Apache (XAMPP / WAMP)  
- **Frontend:** HTML, CSS

---

## 🎯 Project Description

This system simulates an online travel booking platform where:

1. A *customer* enters their trip details (source, destination, travel date)  
2. The travel agency receives the request  
3. The agency checks vehicle availability  
4. A quotation is sent back to the customer  
5. Customer can accept or negotiate quotation  
6. After confirmation, travel details are finalized

It helps manage travel requests efficiently and gives customers a smooth booking experience.

---

## 📥 Installation & Setup

### ✔ Step 1: Clone the Repository

```bash
git clone https://github.com/dineshdj87/dinesh.git
```

### ✔ Step 2: Setup Local Server

Use **XAMPP** or **WAMP**:

1. Start **Apache** and **MySQL**
2. Place the project folder in:
   - `C:\xampp\htdocs\` (for XAMPP)
   - OR `C:\wamp64\www\` (for WAMP)

### ✔ Step 3: Import Database

1. Open **phpMyAdmin**
2. Create a new database (e.g., `tours_db`)
3. Import the `.sql` file (if provided) into this database

### ✔ Step 4: Configure Database

In your PHP config file (if exists):
```php
define('DB_HOST', 'localhost');
define('DB_USER', 'root');
define('DB_PASS', '');
define('DB_NAME', 'tours_db');
```

### ✔ Step 5: Run the App

Open browser:

```
http://localhost/your_project_folder/
```

---

## 🗂 Project Structure

| File/Folder | Description |
|-------------|-------------|
| `index.php` | Landing / Home page |
| `enquiry.php` | Customer travel enquiry |
| `package-list.php` | List available tours |
| `package-details.php` | Tour details |
| `issuetickets.php` | Booking / issue tickets |
| `logout.php` | Logout session |
| `check_availability.php` | Vehicle availability check |
| `change-password.php` | Change user password |
| `tour-history.php` | Past bookings |

---

## 💡 How It Works (User Flow)

1. Customer enters travel info  
2. System checks availability  
3. Travel agency reviews and gives quotation  
4. Customer confirms booking  
5. Booking history stored for future reference

---

## 📌 Future Improvements

- Add **user authentication** (login / signup)
- Add **email notifications**
- Add **payment gateway**
- Mobile-friendly responsive UI
- Admin dashboard for analytics

---

## 👩‍💻 Author

**Dinesh**  
Software Developer  
GitHub: https://github.com/dineshdj87

---

## 🧠 Why This Project Matters

This project shows:

✔ Full-stack web development using PHP & MySQL  
✔ Practical understanding of web forms, database interaction  
✔ Real-world booking workflow simulation  
✔ Basic CRUD operations
