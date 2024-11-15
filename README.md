# 🛒 ShopEZ: E-commerce Application

Welcome to **ShopEZ: E-commerce Application** – an online shopping platform that delivers a complete and seamless e-commerce experience. From product browsing to order management, this project simulates a fully functional online store with an intuitive interface.

<div align="center">
 <img width="60%" src="https://github.com/user-attachments/assets/187ee773-e25e-41c8-9fea-aa610bf8b03f" />
</div>


## ✨ Project Overview

**ShopEZ: E-commerce Application** is designed to provide users with a real-world shopping experience. It includes essential features such as product listings, cart management, user authentication, and order processing. Developed as part of a college project, it showcases a fully-fledged e-commerce platform using modern web development tools.

Our **Objective** is to create a user-friendly and responsive online shopping platform that allows customers to explore, add products to their cart, and place orders effortlessly.

<p align="center"> 
  <img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="700">
<center>

# 🌐 **Live Demo:** [Drive Link]https://drive.google.com/file/d/1fv2RxAtfkeLLU5Hq3YmLkPJ6Kq-xR_U5/view)

</center>
<p align="center"> 
  <img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="700">

## 🔥 Features

- **🛒 Product Management:** Users can browse, search, and filter products by categories.
- **🛍️ Cart System:** Add or remove products, adjust quantities, and view the total price in the cart.
- **🔑 User Authentication:** Secure login, sign-up, and logout functionalities.
- **💸 Order Management:** Place and manage orders, track purchase history.
- **👤 Admin Dashboard:** Admin can manage products, users, and orders (admin-specific features).
- **📱 Responsive Design:** Optimized for mobile, tablet, and desktop devices.

---

## 🛠️ Tech Stack

- **Frontend:** React.js, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Hosting:** Firebase

---

## 🚀 Getting Started

Follow these steps to set up and run the **ShopEZ: E-commerce Application** project on your local machine:

### Prerequisites

Ensure that the following software is installed on your system:

- [Node.js](https://nodejs.org/) (v14.x or higher)
- [npm](https://www.npmjs.com/) (Node package manager)
- [React.js](https://react.dev/) (React JS)

## 📦 Installation

To set up the **ShopEZ: E-commerce Application** project on your local machine, follow these detailed instructions for both the frontend and backend.

### Run With Docker

Don't want to setup with all of the below steps?
Use Docker Compose (Note: Docker should be installed)

1. **Set ENV File**
   Use this starter env file for setting up Docker, Client and Server.
   It should be at root level(In another words at same level where docker-compose.yml is)

   ```bash
   MONGO_URI=mongodb://mongodb
   PORT=3000
   JWT_SECRET=secret
   MONGODBPORT=27017
   MONGOEXPPORT=8081
   SERVERPORT=3000
   CLIENTPORT=5173
   ```

2. **Run Docker Compose**

   ```bash
   docker compose up --watch
   ```

   Note: --watch paramter helps docker to track changes in files if you don't use it you will not be able to see changes and would have to restart everytime/

3. **Stop Docker**

   ```bash
   docker compose down
   ```

   This commands stops docker containers and network and frees all the ports Docker was using.

   For more info on Docker look through this Youtube Video: https://www.youtube.com/watch?v=3c-iBn73dDE

### 🔧 Frontend Setup

1. **Fork the Repository:**  
   Go to the [GMart GitHub repository](https://github.com/MinavKaria/Ratna-Supermarket) and click the "Fork" button in the top-right corner to create your own copy.

2. **Clone the Repository:**  
   Clone your forked repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/Gmart.git
   ```

3. **Navigate to the Project Directory:**  
   Change your directory to the cloned project folder:

   ```bash
   cd Gmart
   cd client
   ```

4. **Install Frontend Dependencies:**  
   Run the following command to install all necessary frontend dependencies:

   ```bash
   npm install
   ```

5. **Start the Frontend Development Server:**  
   Launch the frontend in development mode by running:

   ```bash
   npm run dev
   ```

6. **Open the App:**  
   Open your browser and visit `http://localhost:5173` to see the app in action.

### 🛠️ Backend Setup

1. **Navigate to the Backend Directory:**  
   Change your directory to the backend folder:

   ```bash
   cd ../server
   ```

2. **Install Backend Dependencies:**  
   Install the necessary backend dependencies:

   ```bash
   npm install
   ```

3. **Set Up Environment Variables:**  
   Create or edit the `.env` file in the backend directory with the following variables:

   ```env
   MONGO_URI=<your-mongodb-connection-string>
   DB_NAME=<your-database-name>
   ```

4. **Start the Backend Server:**  
   Launch the backend server:

   ```bash
   node server.js
   ```

### 🐍 Running py_server Files

Ensure you have the following installed:

- [Python](https://www.python.org/) (version 3.x)
- [Flask](https://flask.palletsprojects.com/) (for creating the web server)
- [Flask-CORS](https://flask-cors.readthedocs.io/en/latest/) (for enabling CORS)
- [PyMongo](https://pymongo.readthedocs.io/en/stable/) (for MongoDB integration)

**Start the Backend Server:**  
 Launch the backend server:

```bash
python backend.py

```

## Folder Structure 📂

```
Gmart/
├── client/ # React frontend application
│   ├── src/ # React components and files
│   ├── public/ # Public static files
│   ├── package.json # Frontend dependencies
│   └── vite.config.js # Vite configuration file
├── server/ # Backend Node.js application
│   ├── server.js # Main server file
│   ├── .env # Environment configuration (not included in repo)
│   ├── package.json # Backend dependencies
│   └── ... # Other backend files
├── README.md # This file
└── ...

```

<br>

## 📜 Contributing

We welcome contributions from the community! To contribute, please check out our [CONTRIBUTING.md](./CONTRIBUTING.md) and [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md) to understand the guidelines.

### Quick Guide:

1. Fork and clone the repository.
2. Create a new branch for your feature/bug fix.
3. Make your changes and test them.
4. Submit a pull request for review.

For more details, refer to the [CONTRIBUTING.md](./CONTRIBUTING.md) file.

---

<p align="right"><a href="#top"><img src="https://img.shields.io/badge/Move%20to%20top-Blue?style=plastic" alt="Back To Top"></a></p>
