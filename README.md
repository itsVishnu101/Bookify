
# 📚 Bookify – A Smart Book Resale Platform

Bookify is a full-stack web application designed to simplify the process of **buying and selling used books** online. It connects book lovers, students, and readers who wish to resell their old books or purchase affordable pre-owned copies — all in one clean, responsive platform.

---

## 🚀 Features

### 👤 User Features
- **User Authentication** – Secure login and signup with JWT-based authentication  
- **Book Listing** – Post books for sale with title, author, price, and condition details  
- **Search & Filter** – Find books easily by title, category, or price range  
- **Wishlist** – Save favorite books for later  
- **Chat/Contact Option** – Communicate directly with sellers  

### 🛠️ Admin Features
- Manage all book listings  
- Remove inappropriate or duplicate listings  
- Monitor user activities and transactions  

### 🌐 General Features
- Fully **responsive** design for desktop and mobile  
- RESTful **API integration** between frontend and backend  
- **Image upload support** for book covers  
- Clean and intuitive **UI/UX**  

---

## 🧩 Tech Stack

### 💻 Frontend
- **React.js**  
- **HTML5**, **CSS3**, **JavaScript (ES6+)**  
- **Axios** for API communication  

### ⚙️ Backend
- **Node.js** with **Express.js**  
- **MongoDB** (via Mongoose) for database  
- **JWT Authentication** for user sessions  
- **Cloudinary / Multer** for image uploads  

---

## 🧠 How It Works

1. **Users sign up or log in**  
2. **List books for sale** by adding details and uploading images  
3. **Browse books** listed by others  
4. **Buyers contact sellers** to finalize deals  
5. **Admin moderates** the listings to maintain quality  

---

## 🗂️ Folder Structure

```

Bookify/
│
├── client/                # Frontend React code
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── utils/
│   │   └── App.js
│   └── package.json
│
├── server/                # Backend Node.js + Express API
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── config/
│   ├── server.js
│   └── package.json
│
├── .env                   # Environment variables
├── README.md
└── package.json

````

---

## ⚡ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/<your-username>/Bookify.git
cd Bookify
````

### 2️⃣ Install dependencies for backend

```bash
cd server
npm install
```

### 3️⃣ Install dependencies for frontend

```bash
cd ../client
npm install
```

### 4️⃣ Create `.env` file in `server` folder

```
MONGO_URI = your_mongodb_connection_string
JWT_SECRET = your_jwt_secret
CLOUDINARY_URL = your_cloudinary_url (if used)
PORT = 5000
```

### 5️⃣ Run the app

```bash
# Run backend
cd server
npm start

# Run frontend
cd ../client
npm start
```

Your app will be live at
👉 **Frontend:** [http://localhost:3000](http://localhost:3000)
👉 **Backend:** [http://localhost:5000](http://localhost:5000)

---

## 🧑‍💻 Future Enhancements

* 📦 Add payment gateway integration
* 💬 Implement real-time chat between buyers and sellers
* 🌎 Add location-based filtering
* 📱 Launch as a mobile app using React Native

---

## 🤝 Contributing

Contributions are welcome!
If you’d like to contribute, fork this repository and submit a pull request.

---

## 🧾 License

This project is licensed under the **MIT License** – feel free to use and modify it.

---

##  Acknowledgements

Thanks to all open-source libraries and resources that made this project possible.

> Made with 💙 by [**Vishnu Verma**](https://github.com/itsVishnu101)

```
