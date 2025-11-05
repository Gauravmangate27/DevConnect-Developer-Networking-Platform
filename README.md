# DevConnect: A Networking Platform for Developers

<p align="center">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express.js" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
</p>

**DevConnect** is a full-stack social networking platform built specifically for developers. Inspired by platforms like LinkedIn and Dev.to, it provides a space for developers to create profiles, share their work, write blog posts, and connect with a global community of peers.

This project is built with the **MERN** stack (MongoDB, Express.js, React, Node.js) and serves as a comprehensive example of a modern, scalable web application.

## 📸 Screenshots

**(IMPORTANT: Add your own screenshots here!)**

*Drag and drop your project screenshots into this section to showcase your work.*

| Landing Page | Developer Profiles |
| :---: | :---: |
|  |  |

| Posts Feed | Job Board |
| :---: | :---: |
|  |  |

## ✨ Key Features

* **👤 Custom Developer Profiles:** Create and customize a detailed portfolio, including bio, skills, experience, education, and social links.
* **✍️ Blogging & Posts:** Write and share technical blog posts or simple status updates with the community.
* **🤝 Networking:** Connect with other developers through a follow system and view their profiles and posts.
* **💼 Job Board:** Browse and post job listings tailored for developer roles.
* **💬 Real-time Chat:** (Upcoming Feature) Communicate directly with other developers.
* **🔐 Secure Authentication:** Secure registration and login using JSON Web Tokens (JWT).

---

## 🛠️ Tech Stack

This project is built with the MERN stack and other modern technologies.

### Frontend
* **Library:** [React](https://reactjs.org/)
* **UI Framework:** [Vite](https://vitejs.dev/) + [Tailwind CSS](https://tailwindcss.com/)
* **State Management:** [Redux Toolkit](https://redux-toolkit.js.org/) or Context API
* **Routing:** [React Router](https://reactrouter.com/)

### Backend
* **Framework:** [Node.js](https://nodejs.org/) with [Express.js](https://expressjs.com/)
* **Database:** [MongoDB](https://www.mongodb.com/) with [Mongoose](https://mongoosejs.com/) for object data modeling.
* **Authentication:** [JWT](https://jwt.io/) for secure, token-based authentication.

---

## 🚀 Getting Started

Follow these instructions to get a local copy up and running for development and testing.

### Prerequisites

* **Node.js & npm:** Make sure you have Node.js (v18.x or newer) installed.
* **MongoDB:** You'll need a MongoDB database. You can use a local installation or a cloud service like [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) (recommended).
* **Git:** You'll need Git installed to clone the repository.

### 1. Clone the Repository

Clone your forked repository to your local machine:
```bash
git clone [https://github.com/Gauravmangate27/DevConnect-Developer-Networking-Platform.git](https://github.com/Gauravmangate27/DevConnect-Developer-Networking-Platform.git)
cd DevConnect-Developer-Networking-Platform
```

### 2. Backend Setup (`server` directory)

1.  Navigate to the server directory:
    ```bash
    cd server
    ```
2.  Install the backend dependencies:
    ```bash
    npm install
    ```
3.  Create a `.env` file in the `server` directory and add your environment variables:
    ```.env
    MONGO_URI="your_mongodb_connection_string"
    JWT_SECRET="your_jwt_secret_key"
    PORT=5000
    ```
4.  Start the backend server:
    ```bash
    npm start
    ```
    The server will be running on `http://localhost:5000`.

### 3. Frontend Setup (`client` directory)

1.  Open a **new terminal window** and navigate to the client directory:
    ```bash
    cd client
    ```
2.  Install the frontend dependencies:
    ```bash
    npm install
    ```
3.  Start the frontend development server:
    ```bash
    npm run dev
    ```
    The React app will open and run on `http://localhost:5173` (or another port if 5173 is busy).

---

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

---

## 🙏 Acknowledgments

* This project is based on the [alvarotorrestx/DevConnect](https://github.com/alvarotorrestx/DevConnect) repository.
* Inspiration from the developer community.

---

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for more information.
