# Restaurant Table Booking System

A web-based **Restaurant Table Booking System** that allows users to reserve tables online. This project provides a seamless reservation experience for customers while helping restaurants manage bookings efficiently.

## Features

### User Features
- **Table Reservation:** Users can book tables by selecting date, time, and party size.
- **Account Management:** Sign up, log in, and manage reservations.
- **Real-time Availability:** Check available tables instantly.
- **Notifications:** Get confirmation emails or SMS for bookings.

### Admin Features
- **Dashboard:** View and manage reservations.
- **Table Management:** Set table availability and capacity.
- **Customer Insights:** Track frequent customers and reservations.
- **Cancel/Modify Bookings:** Manage customer reservations easily.

## Tech Stack
- **Frontend:** Angular Js
- **Backend:** Node.js, Express.js
- **Database:** MongoDB Atlas
- **Authentication:** JWT (JSON Web Tokens)
- **Deployment:** Cloudflare Pages (Frontend), Vercel/Render (Backend)

## Installation & Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/restaurant-booking-system.git
   cd restaurant-booking-system
   ```

2. **Install Dependencies:**
   - Backend:
     ```bash
     cd backend
     npm install
     ```
   - Frontend:
     ```bash
     cd frontend
     npm install
     ```

3. **Set Up Environment Variables:**
   Create a `.env` file in the backend directory and configure:
   ```env
   MONGO_URI=your_mongodb_uri
   JWT_SECRET=your_secret_key
   ```

4. **Run the Application:**
   - Backend:
     ```bash
     npm run dev
     ```
   - Frontend:
     ```bash
     npm run dev
     ```

5. **Access the Application:**
   Open `http://localhost:5173` in your browser.

## Future Enhancements
- **Payment Integration** for prepaid reservations.
- **AI-powered Table Suggestions** based on customer preferences.
- **Multilingual Support** for broader accessibility.

## Contributing
We welcome contributions! Fork the repo, create a feature branch, and submit a pull request.

## License
This project is licensed under the **MIT License**.

---


