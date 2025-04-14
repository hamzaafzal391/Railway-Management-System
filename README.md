# Railway-Management-System
A full-stack ASP.NET and SQL Server-based web application designed to manage railway operations efficiently. The system allows users to book tickets, view train schedules, and manage passenger information through an intuitive HTML/CSS/JavaScript frontend.

🛠️ Tech Stack
Frontend: HTML5, CSS3, JavaScript

Backend: ASP.NET (C#)

Database: Microsoft SQL Server

Architecture: MVC (Model-View-Controller)

📌 Features
🔍 Train Schedule Viewer: View upcoming train timings and routes

🧾 Ticket Booking: Reserve seats with validation and confirmation

👥 Passenger Management: Add, update, or remove passenger details

📊 Admin Panel (optional): For managing train data and bookings

🔐 User Authentication (optional): Login system for passengers and admins

📂 Project Structure
vbnet
Copy
Edit
/RailwayManagementSystem
│
├── /App_Code
├── /App_Data
├── /Pages
│   ├── BookTicket.aspx
│   ├── Schedule.aspx
│   ├── Passengers.aspx
│   └── ...
├── /Scripts
│   └── custom.js
├── /Styles
│   └── styles.css
├── Web.config
└── Global.asax
⚙️ How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/RailwayManagementSystem.git
Open in Visual Studio

Connect to your SQL Server and run the provided .sql script to set up the database

Update the connectionString in Web.config

Run the project using IIS Express

🗃️ Database Schema Overview
Trains: TrainID, Route, DepartureTime, ArrivalTime

Passengers: PassengerID, Name, Age, Gender, Contact

Bookings: BookingID, PassengerID, TrainID, SeatNo, BookingDate
