<img src="https://fascinating-squirrel-064eba.netlify.app/Hero.png" alt="bookstore icon" width="300">  

# Online Bookstore

The **Online Bookstore** is a full-stack web application developed using the MERN stack. This platform offers a seamless experience for users to explore, purchase, and manage books while providing robust role-based access for administrators.

## Features

- **User Authentication**: Secure sign-up and log-in using JWT.
- **Book Management**: Users can browse, search, and filter books by categories or authors.
- **Cart Functionality**: Add books to the cart and manage orders efficiently.
- **Favorites**: Add books to a personal favorites list for quick access.
- **Role-Based Access**: Admins can manage the inventory by adding, updating, or deleting books.
- **Categorized Collections**: Extensive library organized into genres:
  - Fiction
  - Children
  - Novels
  - Educational
  - Biography
  - Poetry

*Note: Online reading of books is not supported.*

## Technologies Used

- **Backend**: Node.js, Express, MongoDB (via Mongoose)
- **Frontend**: React, Styled-Components, Material-UI
- **Authentication**: JSON Web Tokens (JWT) with bcrypt for password hashing
- **HTTP Client**: Axios
- **Environment Management**: Dotenv
- **Database Connection**: Mongoose

## Development Credits

- **Frontend Developer**: [Prakash Kumar Mishra](https://github.com/your-github-profile)
- **Backend Developer**: [Prakash Kumar Mishra](https://github.com/your-github-profile)

## Setup

To run this project, follow these steps:

### 1. Clone the Repository
```sh
git clone https://github.com/your-username/online-bookstore.git
cd online-bookstore
```

### 2. Install Dependencies
For the server:
```sh
npm install
```

For the client:
```sh
cd frontend
npm install
```

### 3. Set Up Environment Variables
Create a `.env` file in the root directory and configure the following:
```env
PORT=1000
URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

### 4. Start the Application
Using `concurrently`, you can run both the backend and frontend servers:
```sh
npm run dev
```

### 5. Navigate to the Application
Visit [https://fascinating-squirrel-064eba.netlify.app/) to explore the Online Bookstore.

---

