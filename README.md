# Bookstore App 📚

A full-stack **Bookstore App** built with React Native for the frontend and Node.js/Express with MongoDB for the backend.  
The app allows users to sign up, log in, browse recommended books, add new books, and manage their profile.

---

## ✨ Features

- **User Authentication** – Secure sign up and login system  
- **Book Listings** – View a list of recommended books  
- **Add New Books** – Create and share your favorite books  
- **User Profile** – Manage user information and submitted books  
- **Cross-Platform** – Works on both Android and iOS  

---

## 🛠️ Technologies Used

- **Frontend**: React Native  
- **Backend**: Node.js, Express  
- **Database**: MongoDB  
- **Authentication**: JSON Web Tokens (JWT)  
- **Networking**: Axios / Fetch API  

---

## 🚀 Core API Endpoints

| Endpoint           | Method | Description                        |
|--------------------|--------|------------------------------------|
| `/api/auth/signup` | POST   | Register a new user                |
| `/api/auth/login`  | POST   | Authenticate user and return a JWT |
| `/api/books`       | GET    | Fetch all book recommendations     |
| `/api/books`       | POST   | Add a new book (requires auth)     |
| `/api/users/me`    | GET    | Get current user profile           |

---

## 🔮 Future Enhancements

- 📷 Upload book cover images  
- ⭐ Book ratings and reviews  
- 🔍 Search & filter functionality  
- 🔔 Push notifications for new books  
- ✏️ Edit/delete books  

---

## 📄 License

This project is licensed under the **MIT License**.
