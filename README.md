# Exploro-ASG

**Exploro-ASG** is a full-stack web application designed for exploring and managing travel destinations. The project is divided into two main components: a **frontend** for user interaction and a **backend** for data management and API services.

---

## 🛠 Features

### **Frontend**
- Responsive and user-friendly UI.
- Seamless navigation through destinations.
- Integration with API services for dynamic content rendering.

### **Backend**
- RESTful APIs for managing data.
- Secure authentication and authorization using JWT.
- MongoDB integration for database operations.

---

## 🏗 Tech Stack

### **Frontend**
- **Framework**: React.js
- **Styling**: CSS / SCSS

### **Backend**
- **Runtime**: Node.js
- **Framework**: Express.js
- **Database**: MongoDB
- **Authentication**: JWT

---


---

## 🚀 Getting Started

### Prerequisites
Make sure you have the following installed on your system:
- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)
- [Git](https://git-scm.com/)

---
## Approach
To build this project, I take this following approach:

### 1. **Requirement Analysis**
   - Identified the key features needed for a travel-related application.
   - Focused on ensuring both frontend and backend were modular and scalable.

### 2. **Frontend Development**
   - Used **React.js** to create a dynamic and interactive user interface.
   - Organized components based on functionality and reusability.
   - Styled the application using plain CSS to maintain flexibility.
   - Integrated API calls using `axios` to fetch and display data.

### 3. **Backend Development**
   - Set up an **Express.js** server to handle RESTful API requests.
   - Integrated **MongoDB** as the database for storing user and travel-related data.
   - Used **Mongoose** for schema validation and data modeling.
   - Implemented **JWT authentication** for secure user sessions.

### 4. **API Design**
   - Designed RESTful APIs for:
     - **Authentication**: User registration and login.
     - **CRUD Operations**: Managing travel data (create, read, update, delete).
   - Followed REST principles to ensure predictable and scalable APIs.

### 5. **Environment Management**
   - Used environment variables for sensitive information like database connection strings and JWT secrets.

### 6. **Testing and Debugging**
   - Tested the application locally to identify and resolve issues.
   - Verified API responses using tools like **Postman**.
   - Debugged deployment issues using Railway and Vercel build logs.

---
### **Setup Instructions**

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Vaibhav7720/exploro-asg.git
   cd exploro-asg
---
2. **Install Dependencies**
   - **Frontend**
   ```bash
   cd Frontend
   yarn
   
- **Backend**
   ```bash
   cd Backend
   yarn
---
3. **Environment Variables**
   ```env
    Create a .env file in the Backend/ directory and add the following:
    MONGO_URI=<your_mongo_connection_string>
    JWT_SECRET=<your_jwt_secret_key>
---
4. **Run the Application**
 - **Backend**
   ```bash
   cd Backend
   yarn dev
   
- **Frontend**
   ```bash
   cd Frontend
   yarn serve
---
5. Open your browser and navigate to http://localhost:3000 to access the application.
---
6. **Deployment :**
   This project is deployed using services like:
     - Railway(Backend)
     - Vercel (Frontend)
---
7. **🛡 Security**
      - All sensitive information like API keys and secrets are stored in .env files and excluded from version control using .gitignore.
      - User authentication is handled securely using JWT tokens.
 

