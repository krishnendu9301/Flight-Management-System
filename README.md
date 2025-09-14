# ✈️ Flight Management System

## 📌 Overview
The **Flight Management System** is a Python-based application that manages flights, bookings, cancellations, and reporting.  
It uses **CSV files** for data storage and leverages **Pandas**, **NumPy**, and **Matplotlib** for data handling and visualization.  

This project demonstrates how Python can be applied in real-world scenarios such as airline operations, with automation of repetitive tasks and analytical insights.  

---

## 🚀 Features
- **Add Flights** – Register new flights with airline name, route, timings, capacity, and fare.  
- **View Flights** – Display all available flights in tabular form.  
- **Book Tickets** – Confirm seat if available, otherwise add passenger to waitlist.  
- **Cancel Tickets** – Cancel confirmed bookings with automatic waitlist promotion.  
- **View Bookings** – Show all passenger bookings across flights.  
- **Reports & Analytics**:  
  - 📊 **Occupancy Pie Chart** (Confirmed, Waitlisted, Cancelled, Available).  
  - 📈 **Revenue Histogram** (Revenue per flight).  

---

## 🛠️ Tech Stack
- **Python 3.x**  
- **Pandas** → Data handling (CSV read/write)  
- **NumPy** → Numeric operations (seat allocation, capacity checks)  
- **Matplotlib** → Charts & visualization  

---

## 📂 File Structure
Flight-Management-System/
│
├── flight_management.py # Main Python program
├── flights.csv # Stores flight details
├── bookings.csv # Stores passenger bookings
└── README.md # Project documentation

---

## ⚙️ Setup & Installation
1. Clone or download this repository.  
2. Install Python (>=3.8).  
3. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib
Run the project:
python flight_management.py

---

Charts
Occupancy Pie Chart – Shows seat utilization.
Revenue Histogram – Compares total revenue per flight.

---

👤 Author
This project is solely developed and maintained by Krishnendu Mondal.

---

📜 License
This project is open for educational and personal use. Redistribution or modification is allowed with proper credit to the author.
