# 🏠 Airbnb Clone

## 📌 Overview
This is an **Airbnb clone web app** built using the **MVC framework** with **HTML/CSS**, **JavaScript**, **EJS**, **Node.js**, **Express.js**, and **MongoDB**. The app allows users to sign up, log in, add new posts, edit, delete, and manage their listings. It follows the **Model-View-Controller (MVC)** architecture for better organization and maintainability. The app is deployed and hosted on **Render** for easy access.

## 🛠️ Technologies Used
- **HTML/CSS** – For creating and styling the frontend
- **JavaScript** – For interactive frontend behavior
- **EJS** – For dynamic templating on the backend
- **Node.js** – For server-side logic and API handling
- **Express.js** – For routing and backend framework
- **MongoDB** – For database management
- **Render** – For hosting the app online

## 🎯 Features
✅ **User authentication** – Users can sign up, log in, and manage sessions  
✅ **Add/Edit/Delete listings** – Users can add new properties, edit them, or remove them from the platform  
✅ **Listing details page** – Detailed view for each property with images, description, and pricing  
✅ **Responsive design** – Optimized for both desktop and mobile usage  
✅ **MVC architecture** – Clean separation of concerns with Models, Views, and Controllers  

## 📂 Project Structure
```
/airbnb-clone
│── public/              # Public assets (CSS, images, etc.)
│── views/               # EJS views for rendering HTML pages
│   ├── index.ejs        # Home page
│   ├── login.ejs        # Login page
│   ├── signup.ejs       # Sign-up page
│   ├── dashboard.ejs    # User dashboard to manage listings
│── controllers/         # Business logic
│   ├── authController.js # Handles user authentication
│   ├── listingController.js # Handles listings-related actions
│── models/              # MongoDB models for users and listings
│   ├── User.js          # User model
│   ├── Listing.js       # Listing model
│── routes/              # API and page routes
│   ├── authRoutes.js    # Authentication routes (login, signup)
│   ├── listingRoutes.js # Listings-related routes (add, edit, delete)
│── server.js            # Main server file
│── .env                 # Environment variables
│── README.md            # Project documentation
```

## 🚀 How to Use
1. **Clone the repository**  
   ```bash
   git clone https://github.com/yourusername/airbnb-clone.git
   ```  
2. **Navigate to the project folder**  
   ```bash
   cd airbnb-clone
   ```  
3. **Install dependencies**  
   ```bash
   npm install
   ```  
4. **Set up the environment**  
   - Create a `.env` file and add the following:  
   ```
   MONGODB_URI=your_mongo_db_connection_string_here
   SESSION_SECRET=your_session_secret_here
   ```  
5. **Run the app**  
   - Start the server:  
   ```bash
   npm start
   ```  
6. Open `http://localhost:3000/` in your browser.

## 📸 Screenshots
![Airbnb-clone](https://github.com/user-attachments/assets/c3123e9d-af17-4b1f-aaa0-22c265a864e0)


## 🔗 Live Demo
[Live Preview](https://airbnb-clone-lwq8.onrender.com/listings)  

## 📌 Future Enhancements
- Implement **search functionality** for listings based on location, price, etc.  
- Add **booking feature** for users to reserve listings  
- Include **ratings and reviews** for listings  
- Support **user profile management**  

## 📝 License
This project is **free to use** and open-source.
