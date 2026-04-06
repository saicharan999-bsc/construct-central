# 🚧 Construct Central

Construct Central is a full-stack web application that connects customers with heavy-duty vehicle owners (such as JCBs, trucks, cranes, etc.) for construction-related work.

The platform simplifies the process of finding equipment and skilled operators by enabling direct communication between customers and vehicle providers.

---

## 🚀 Features

- 🔍 Browse available construction vehicles
- 📱 One-click WhatsApp communication with vehicle owners
- ⚡ Fast and scalable backend using MongoDB
- 🖥️ Responsive user interface
- 📦 Efficient vehicle listing and management system

---

## 🛠️ Tech Stack

### Frontend
- HTML
- CSS
- JavaScript

### Backend
- Node.js
- Express.js

### Database
- MongoDB

### Tools
- Git
- GitHub
- VS Code

---

## 📂 Project Structure

construct-central/
│── public/
│ ├── index.html
│ ├── home.html
│ ├── explore.html
│ ├── login.html
│ ├── register.html
│ ├── signup.html
│ ├── request.html
│
│── views/
│ ├── excavator.ejs
│
│── server.js
│── package.json


---

## ⚙️ How It Works

1. Vehicle owners list their construction vehicles on the platform  
2. Customers browse available vehicles  
3. Users can directly contact vehicle owners via WhatsApp  
4. Backend handles data storage and retrieval using MongoDB  

---

## 🧑‍💻 Installation & Setup

### 1. Clone the repository

git clone https://github.com/saicharan999-bsc/construct-central.git
cd construct-central

2. Install dependencies
npm install


3. Start the server
npm start

or (if using nodemon):

nodemon server.js
4. Open in browser
http://localhost:3000


🌟 Future Improvements
Proper MVC architecture (separate routes, controllers, models)
User authentication system
Database integration for dynamic vehicle listings
Booking system
Payment integration
