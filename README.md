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

### **Setup Instructions**

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Vaibhav7720/exploro-asg.git
   cd exploro-asg

2. **Install Dependencies**
   ```bash
   cd Frontend
   yarn
   yarn serve

   ```bash
   cd Backend
   yarn
   yarn dev

3. **Environment Variables**
   ```env
    Create a .env file in the Backend/ directory and add the following:
    MONGO_URI=<your_mongo_connection_string>
    JWT_SECRET=<your_jwt_secret_key>



