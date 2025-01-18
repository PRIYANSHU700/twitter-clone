# Twitter Clone

This project is a Twitter clone built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It replicates core features of Twitter, including user authentication, posting tweets, following users, and liking tweets.

## Features

- **User Authentication**: Sign up, log in, and log out securely with JWT-based authentication.
- **Tweet Functionality**: Post, edit, delete tweets, and view timelines.
- **Likes and Retweets**: Interact with tweets by liking or retweeting them.
- **Follow System**: Follow and unfollow users to curate your feed.
- **Responsive Design**: Optimized for desktop and mobile devices.

## Tech Stack

### Frontend:
- **React.js**
  - React Router for navigation
  - Axios for API requests
  - Styled Components or CSS for styling

### Backend:
- **Node.js** with **Express.js**
  - RESTful API design
  - JSON Web Tokens (JWT) for authentication
  - bcrypt for password hashing

### Database:
- **MongoDB**
  - Mongoose for object modeling

### Other Tools:
- **Nodemon**: For automatic server restarts during development.
- **Cross-env**: For managing environment variables across platforms.

## Installation and Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/twitter-clone.git
   cd twitter-clone
   ```

2. **Install Dependencies**
   - Backend:
     ```bash
     cd backend
     npm install
     ```
   - Frontend:
     ```bash
     cd ../frontend
     npm install
     ```

3. **Set Up Environment Variables**
   - Create a `.env` file in the `backend` directory with the following keys:
     ```env
     PORT=5000
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     ```

4. **Run the Application**
   - Backend:
     ```bash
     cd backend
     npm run dev
     ```
   - Frontend:
     ```bash
     cd ../frontend
     npm start
     ```

5. **Access the Application**
   Open your browser and navigate to `http://localhost:3000`.

## Folder Structure

```
.
├── backend
│   ├── models
│   ├── routes
│   ├── controllers
│   ├── middleware
│   └── server.js
├── frontend
│   ├── src
│   │   ├── components
│   │   ├── pages
│   │   ├── services
│   │   ├── App.js
│   │   └── index.js
└── README.md
```

## Contributing

Contributions are welcome! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Open a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments

- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [React.js](https://reactjs.org/)
- [MongoDB](https://www.mongodb.com/)
- [Twitter](https://twitter.com/) for inspiring this project.

