
# Restaurant Reservation System

A full-stack web application for managing restaurant reservations, built using the MERN stack. This project allows users to browse and reserve tables, while restaurant staff can manage and track bookings efficiently.

## ✨ Features

  * **User-Friendly Interface:** A clean and intuitive front-end built with React.
  * **Table Reservations:** Users can select dates, times, and party sizes to reserve a table.
  * **Admin Dashboard:** A separate dashboard for restaurant staff to view, create, update, and delete reservations.
  * **Secure API:** A RESTful API built with Express.js to handle all data requests securely.
  * **Database Management:** Reservations are stored and managed in a MongoDB database.

-----

## 🛠️ Tech Stack

**Client-Side:**

  * **React:** For building the dynamic user interface.
  * **CSS/HTML:** For styling and structure.

**Server-Side:**

  * **Node.js:** The JavaScript runtime environment.
  * **Express.js:** A robust web framework for Node.js.
  * **MongoDB:** A NoSQL database for storing reservation data.
  * **Mongoose:** An elegant MongoDB object modeling for Node.js.

-----

## 🚀 Installation

Follow these steps to set up the project on your local machine.

### Prerequisites

  * Node.js and npm installed.
  * MongoDB instance (local or remote) running.

### 1\. Clone the Repository

```bash
git clone https://github.com/AVparkhe/Restaurant_Reservation_Project.git
cd Restaurant_Reservation_Project
```

### 2\. Configure Environment Variables

Create a file named `.env` in the root of your project and add the following:

```
# Server Configuration
PORT=5000
MONGODB_URI=<Your_MongoDB_Connection_String>
```

  * Replace `<Your_MongoDB_Connection_String>` with your actual MongoDB connection string.

### 3\. Install Dependencies

Navigate to the project directory and install dependencies for both the client and server.

```bash
# Install server dependencies
npm install

# Navigate into the client directory
cd client

# Install client dependencies
npm install

# Go back to the root directory
cd ..
```

-----

## ▶️ Usage

To run the application, you'll need to start both the server and the client.

### 1\. Start the Server

```bash
npm start
```

The server will run on the port you specified (e.g., `http://localhost:5000`).

### 2\. Start the Client

```bash
cd client
npm start
```

The React development server will start, typically on `http://localhost:3000`, and will automatically open in your browser.

-----

## 🤝 Contributing

Contributions are what make the open-source community a fantastic place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1.  Fork the Project.
2.  Create your Feature Branch (`git checkout -b feature/NewFeature`).
3.  Commit your Changes (`git commit -m 'Add some NewFeature'`).
4.  Push to the Branch (`git push origin feature/NewFeature`).
5.  Open a Pull Request.

-----

## 📝 License

This project is licensed under the MIT License - see the `LICENSE` file for details.
