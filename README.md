# 🎟️ Movie Ticket Booking System

## 🧩 Problem Statement

Moviegoers often face issues like **long queues** and **manual seat allocation** at theaters.
The **Movie Ticket Booking System**, built using **Java, Servlets, JSP**, and **XML**, aims to solve these problems by allowing customers to:

* Browse currently running and upcoming movies
* View showtimes
* Reserve seats in real time

The use of **XML-based seat mapping** ensures structured seat tracking and prevents double booking, providing a smooth and automated booking experience.

---

## 🚀 Key Features

### 🎮 Movie Listings & Showtimes

* Display currently running and upcoming movies
* Show available theaters and showtimes

### 💺 Seat Reservation

* XML-based seat map for each show
* Real-time seat locking and releasing during booking

### 👤 User Registration & Login

* Secure account creation and login
* Track booking history
* Option for guest checkout

### 🔍 Search & Filters

* Filter by **language**, **genre**, **theater**, or **show timing**
* Search for specific movies easily

### 💳 Booking & Payment Integration

* Reserve multiple seats in one transaction
* Integrated payment gateway for online ticket purchases

### 🧾 E-Ticket Generation

* Generate XML-based booking confirmation
* QR code or barcode for entry validation

### ❌ Cancellation & Refund

* Allow users to cancel tickets as per theater policy
* Automated refund handling

### ⚙️ Admin Panel

* Manage movie listings, schedules, and pricing
* View booking statistics and reports

### 🔄 Real-time Updates

* Automatic update of seat availability after each booking
* Prevents double booking through live synchronization

### 📈 Scalability

* Extendable to support multiple theaters and chains
* Future-ready for mobile app integration

---

## 🛠️ Tech Stack

| Component                  | Technology                    |
| -------------------------- | ----------------------------- |
| **Frontend**               | JSP, HTML, CSS                |
| **Backend**                | Java Servlets                 |
| **Database / Data Source** | XML (Seat Maps, Movie Data)   |
| **Server**                 | Apache Tomcat                 |
| **Tools**                  | Eclipse / VS Code, Git, Maven |

---

## 📂 Project Structure

```
Movie-Ticket-Booking-System/
│
├── src/
│   ├── main/
│   │   ├── java/servlets/       # Servlet files
│   │   ├── webapp/              # JSP files
│   │   └── resources/xml/       # XML data (movies, seats, etc.)
│
├── web.xml                      # Deployment descriptor
├── pom.xml                      # Maven dependencies (if used)
└── README.md
```

---

## 🧠 How It Works

1. **User** opens the system and views available movies.
2. **Selects** movie → showtime → seats → proceeds to checkout.
3. **Seat map** updates in real time to reflect availability (XML-based).
4. **Payment** completed via integrated gateway.
5. **E-ticket** (with QR/barcode) is generated and emailed or displayed.
6. **Admin** can manage listings, schedules, and reports through a secure panel.

---

## 💡 Future Enhancements

* Mobile app integration for iOS & Android
* AI-based movie recommendations
* Multi-language support for UI
* Integration with wallet and UPI payment options

---

## 👨‍💻 Developed By

**Johnwick Babayaga**
🎓 Nimbus Project Submission

---

### ⭐ If you like this project, give it a star on GitHub!

---
