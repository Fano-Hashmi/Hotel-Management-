
# 🏨 Hotel Management System

A desktop-based Hotel Management System developed in Java using Swing GUI. This application allows hotel staff to manage room bookings, customer details, meal selections, billing, and room availability through an interactive graphical interface.

## 📌 Features

### Room Management
- View available and booked rooms
- Book hotel rooms
- Cancel room bookings
- Real-time room status updates

### Customer Management
- Store customer information
- CNIC verification fields
- Track duration of stay

### Meal Management
- Breakfast selection
  - Egg
  - Paratha
  - Channay
  - Tea
  - Mineral Water

- Lunch/Dinner selection
  - Biryani
  - Karahi
  - Mutton Karahi
  - Beef Karahi
  - Salad

### Billing System
- Automatic room cost calculation
- Meal cost calculation
- Total bill generation
- Detailed bill summary

### GUI Features
- Java Swing graphical interface
- Color-coded room availability table
- Booking form
- Bill display panel
- User-friendly layout

---

## 🛠 Technologies Used

- Java
- Java Swing
- AWT
- JDBC
- MySQL (Database Connection Ready)

---

## 📂 Project Structure

```text
UltraAdvancedHotelSystem.java

├── DBHelper
├── Room
├── Customer
├── Hotel
└── UltraAdvancedHotelSystem (Main GUI)
```

---

## 🏠 Room Categories

| Room Type | Price (PKR) |
|------------|------------|
| Suite | 5000 |
| Single | 2000 |
| Double | 3500 |

Total Rooms:
- 20 Suite Rooms
- 20 Single Rooms
- 20 Double Rooms

**Total: 60 Rooms**

---

## 🚀 How to Run

### 1. Clone Repository

```bash
git clone https://github.com/Fano-Hashmi/hotel-management-system.git
```

### 2. Open Project

Open the project in:
- IntelliJ IDEA
- NetBeans
- Eclipse
- VS Code
  
### 3. Compile

```bash
javac UltraAdvancedHotelSystem.java
```

### 4. Run

```bash
java UltraAdvancedHotelSystem
```

---

## 🗄 Database Configuration

The project contains JDBC database connectivity support.

Update the database credentials in the `DBHelper` class:

```java
String url = "jdbc:mysql://localhost:3306/shrms";
String user = "root";
String pass = "";
```

Make sure:
- SQL Lite Server is running
- SQL Lite JDBC Driver is installed
- Database `shrms` exists

---

## 💳 Bill Calculation

Total Bill =

```text
(Room Price × Number of Days)
+
(Meal Cost × Number of Days)
```

The system automatically generates a detailed bill including:

- Customer Information
- Room Details
- Stay Duration
- Meal Selections
- Meal Charges
- Total Amount

---

## 🔮 Future Enhancements

- Database CRUD Operations
- Customer Search
- Booking History
- Online Payments
- PDF Bill Export
- Login & Authentication System
- Admin Dashboard
- Room Reservation Reports

---

## 👨‍💻 Author
Developed By {Fano-Hashmi}
Developed as a Hotel Management System project using Java Swing and JDBC.

---

## 📄 License

This project is open-source and available under the MIT License.
