
# 📚 MERN Stack Bookstore App

A fully functional, responsive Bookstore application built using the **MERN Stack** (MongoDB, Express, React, Node.js). This project features user authentication, protected routes, a dark/light theme toggle, and a modern UI designed with Tailwind CSS and DaisyUI.

## 🚀 Live Demo

*(If you have deployed it, paste the link here. If not, remove this line or write "Coming Soon")*

## 🌟 Key Features

  * **Responsive Design:** Fully optimized for desktop, tablet, and mobile devices.
  * **User Authentication:** Secure Signup and Login functionality using **Bcrypt.js** for password hashing.
  * **Protected Routes:** The "Courses" page is accessible only to authenticated users.
  * **Dark/Light Mode:** Theme toggler with state persistence using Local Storage.
  * **Book Showcase:** Slick slider integration to display free books on the home page.
  * **API Integration:** RESTful API built with Express and connected to MongoDB.
  * **Form Handling:** robust form validation using **React Hook Form**.
  * **Notifications:** Real-time success/error popups using **React Hot Toast**.

## 🛠️ Tech Stack

**Frontend:**

  * React.js (Vite)
  * Tailwind CSS
  * DaisyUI (Component Library)
  * React Router DOM (Routing)
  * Axios (HTTP Requests)
  * React Slick (Carousel)

**Backend:**

  * Node.js
  * Express.js
  * Mongoose (ODM)
  * Bcrypt.js (Security)
  * Cors (Cross-Origin Resource Sharing)

**Database:**

  * MongoDB (Compass/Atlas)

## 📸 Screenshots

*(You should upload screenshots of your project here. Example placeholders below:)*

| Home Page (Light) | Home Page (Dark) |
|:---:|:---:|
|  |  |

| Login Modal | Course Page (Protected) |
|:---:|:---:|
|  |  |

## ⚙️ Installation & Setup

Follow these steps to run the project locally on your machine.

### 1\. Clone the repository

```bash
git clone https://github.com/your-username/bookstore-app.git
cd bookstore-app
```

### 2\. Backend Setup

Navigate to the backend folder and install dependencies:

```bash
cd Backend
npm install
```

Create a `.env` file in the `Backend` root and add the following:

```env
PORT=4001
MongoDBURI=your_mongodb_connection_string
```

Start the server:

```bash
npm start
```

*(The server should run on port 4000 or 4001)*

### 3\. Frontend Setup

Open a new terminal, navigate to the frontend folder, and install dependencies:

```bash
cd Frontend
npm install
```

Start the client application:

```bash
npm run dev
```

## 📂 Project Structure

```text
├── Backend
│   ├── controller   # Logic for Books and Users
│   ├── model        # Mongoose Schemas (Book & User)
│   ├── route        # API Routes
│   └── index.js     # Entry point
│
├── Frontend
│   ├── src
│   │   ├── components  # Reusable UI components (Navbar, Banner, etc.)
│   │   ├── context     # Context API for Authentication
│   │   ├── home        # Home page layout
│   │   └── App.jsx     # Main application component
```

## 🤝 Contributing

Contributions are welcome\!

1.  Fork the project
2.  Create your feature branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## 👤 Author

Sorabh Kumar

  * GitHub: https://github.com/sorabh56
  * LinkedIn: https://www.linkedin.com/in/sorabh-kumar-61821b253/

-
