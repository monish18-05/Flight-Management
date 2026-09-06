# ✈️ Flight Management System

A Java Servlet-based web application for managing flight records. The system allows users to log in, add new flights, view available flights, filter flights based on price, and sort flights by price or departure time. It is built using Java Servlets, JDBC, PostgreSQL, and Apache Tomcat.

## 🚀 Features

- 🔐 User Authentication
- ➕ Add New Flights
- 📋 View All Flights
- 💰 Filter Flights by Price
- 📊 Sort Flights by Price
- 🕒 Sort Flights by Departure Time
- 🗄️ PostgreSQL Database Integration
- 🌐 Responsive Web Interface

## 🛠️ Tech Stack

- **Backend:** Java Servlets
- **Frontend:** HTML, CSS, JavaScript
- **Database:** PostgreSQL
- **Connectivity:** JDBC
- **Server:** Apache Tomcat
- **IDE:** Eclipse / IntelliJ IDEA

## 📂 Project Structure

```
FlightManager/
│── src/
│   └── com/
│       └── flight/
│           ├── AddFlightServlet.java
│           ├── DBConnection.java
│           ├── FilterServlet.java
│           ├── Flight.java
│           ├── LoginServlet.java
│           ├── SortPriceServlet.java
│           ├── SortTimeServlet.java
│           └── ViewFlightsServlet.java
│
├── WebContent/
│   ├── index.html
│   ├── dashboard.html
│   ├── css/
│   ├── js/
│   └── WEB-INF/
│       └── web.xml
│
└── README.md
```

## 📸 Screenshots

> Add screenshots of the following pages:

- Login Page
- Dashboard
- Add Flight
- Flight List
- Filter Results

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/monish18-05/FlightManager.git
cd FlightManager
```

### 2. Configure PostgreSQL

Create a PostgreSQL database and update the database credentials in `DBConnection.java` or configure the following environment variables:

```
DB_URL
DB_USER
DB_PASSWORD
```

### 3. Import the Project

Import the project into Eclipse or IntelliJ IDEA as a Dynamic Web Project.

### 4. Add Apache Tomcat

Configure Apache Tomcat (v9 or later) and deploy the project.

### 5. Run

Start the Tomcat server and open:

```
http://localhost:8080/FlightManager
```

## 📌 Future Enhancements

- Flight Booking Module
- Update and Delete Flight Records
- Role-Based Authentication
- Search Flights
- Flight Status Tracking
- Responsive UI Improvements
- Password Encryption
- REST API Integration

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

## 👨‍💻 Author

**Monish Shetty**

- GitHub: https://github.com/monish18-05

## 📄 License

This project is developed for educational and learning purposes.
