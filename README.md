# Table Booking System

## Overview
The Table Booking System is a web-based application designed to facilitate reservations for tables in restaurants, cafes, or event venues. This project was developed using Angular for the frontend and .NET for the backend, with APIs for seamless communication. It supports user authentication, table selection, booking management, and an admin panel for managing reservations.

## Features
- **User Authentication:** Secure login and registration.
- **Table Selection:** Users can view available tables and select their preferred time slots.
- **Booking Management:** Users can create, modify, or cancel bookings.
- **Admin Panel:** Admins can manage bookings, view reports, and configure table availability.
- **Responsive Design:** Optimized for various devices and screen sizes.
- **Email Notifications:** Users receive confirmation emails for successful reservations.
- **API Integration:** Uses REST APIs to fetch and update booking data.

## Technologies Used
### Frontend:
- Angular
- TypeScript
- HTML, CSS, Bootstrap

### Backend:
- .NET Core
- C#
- Entity Framework
- SQL Server (Database)
- ASP.NET Web API

### Deployment & Tools:
- Docker (for containerization)
- Azure (for hosting)
- Visual Studio Code & Visual Studio (for development)

## Installation Guide
### Steps to Run Locally
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/table-booking.git
   cd table-booking
   ```
2. Install frontend dependencies:
   ```sh
   cd frontend
   npm install
   ```
3. Start the Angular frontend:
   ```sh
   ng serve
   ```
4. Set up the backend:
   - Open the `backend` folder in Visual Studio.
   - Configure the database connection in `appsettings.json`.
   - Run database migrations:
     ```sh
     dotnet ef database update
     ```
   - Start the backend server:
     ```sh
     dotnet run
     ```
5. Access the application:
   - Open `http://localhost:4200` in your browser.

analytics and reporting features for admins.


## License
This project is licensed under the MIT License - see the LICENSE file for details.

