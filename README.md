# 🏋️ Gym Management System

A full-featured Gym Management System built using **Java (Swing GUI)** and **MySQL**, designed for easy tracking of member and trainer records, attendance, payments, packages, schedules, and more. Ideal for small to medium-sized gyms and fitness centers.

---

## 📌 Features

### 👤 Member Management
- Register new members with personal and package details
- View, update, and delete member records
- Assign packages with pricing and type

### 🧑‍🏫 Trainer Management
- Add and manage trainer profiles
- Assign trainers to specific schedules
- Maintain trainer skill and salary details

### 📅 Attendance Module
- Record daily attendance for members and trainers
- Track hours attended
- Display all attendance logs in table format

### 💸 Payment Handling
- Manage **Member Payments** with multiple payment modes (Cash, QR, Online)
- Handle **Trainer Payments** based on days and hours worked
- Automatically calculate and display total salary

### 🧾 Reports & Receipts
- View complete payment history
- Generate printable payment receipts
- Auto-generated Receipt IDs

### 🕒 Weekly Schedules
- Assign members to weekly classes
- View and edit class schedules by time slots

---

## 🧑‍💻 Tech Stack

| Component      | Technology     |
|----------------|----------------|
| Language       | Java 8         |
| GUI Framework  | Java Swing     |
| Database       | MySQL          |
| DB Connection  | JDBC           |
| IDE Used       | IntelliJ IDEA  |

---

## 📂 Project Structure

📁 GymManagement
├── src/
│ ├── GymSignup.java
│ ├── GymSignin.java
│ ├── GymReg.java
│ ├── Attendance.java
│ ├── Trainer.java
│ ├── GymPay.java
│ ├── WeeklySch.java
│ ├── Packagecurd.java
│ ├── GenrateReport.java
│ └── DBConnect.java
├── images/
│ └── *.png, *.jpg (UI banners, icons)
├── invoices/
│ └── *.pdf, *.txt (generated receipts)



---

## 🏁 Getting Started

### ✅ Prerequisites
- Java 8 or above
- MySQL Server (with database and required tables)
- IntelliJ IDEA or any Java IDE

### 📥 Setup Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/GymManagement.git```

### 2.Import in IntelliJ IDEA

Open IntelliJ → Import Project → Select this folder

3.Configure MySQL

Edit DBConnect.java with your DB credentials

Example:conn = DriverManager.getConnection("jdbc:mysql://localhost:3306/gymdb", "root", "password");


4.Run the App

Right-click GymAdmin.java → Run


📸 Screenshots
<img width="1920" height="1080" alt="Screenshot 2025-07-26 000738" src="https://github.com/user-attachments/assets/fd02f000-5fc7-4de3-a478-2bd48e907b53" />
<img width="1920" height="1080" alt="Screenshot 2025-07-26 000745" src="https://github.com/user-attachments/assets/92ec7e25-1d36-4ec9-aa7e-e2de079d58d9" />
<img width="1920" height="1080" alt="Screenshot 2025-07-26 000751" src="https://github.com/user-attachments/assets/59b5ea18-37c5-4512-9b8f-906bc4d10a30" />
<img width="1920" height="1080" alt="Screenshot 2025-07-26 000759" src="https://github.com/user-attachments/assets/d6730e4a-0b85-419c-af19-8fdc1bafed9e" />
<img width="1920" height="1080" alt="Screenshot 2025-07-26 000805" src="https://github.com/user-attachments/assets/554c71ee-e53e-446f-91f3-9d09216f05f3" />
<img width="1920" height="1080" alt="Screenshot 2025-07-26 000811" src="https://github.com/user-attachments/assets/8f678e6e-12ab-4084-8fac-ae7a3b958282" />




🙋‍♂️ Author
Ashutosh Bhavsar





---

### 👉 Next Steps:

- Want me to **generate a `LICENSE` (MIT)** file too?
- Want me to push the `README.md` and license to GitHub now?

Let me know and I’ll prepare the file or push them automatically.
