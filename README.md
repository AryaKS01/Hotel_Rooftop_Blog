# Hotel Rooftop Blog

Welcome to the Hotel Rooftop Blog project! This is a full-stack web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js) that allows users to create, view, and interact with blog posts.

## Features

- **User Authentication**: Users can sign up and log in to their accounts.
- **Blog Management**: Authenticated users can create, edit, and delete their own blog posts.
- **Commenting System**: Users can comment on blog posts, and comments are preserved across different posts.
- **Search Functionality**: Users can search for blog posts using keywords.
- **Responsive Design**: The application is designed to be responsive and user-friendly across various devices.

## Tech Stack

- **Frontend**:
  - React.js
  - CSS for styling
  - Axios for API requests

- **Backend**:
  - Node.js
  - Express.js
  - MongoDB (with Mongoose for database interaction)

- **Authentication**:
  - JSON Web Tokens (JWT)

- **Other Tools and Libraries**:
  - Nodemon for backend development
  - dotenv for environment variable management

## Project Structure

The project is divided into two main directories:

- `frontend`: Contains the React.js application.
- `backend`: Contains the Express.js server and MongoDB database configuration.

## Getting Started

To run this project locally, follow the steps below:

### Prerequisites

Ensure you have the following installed on your system:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)
- [MongoDB](https://www.mongodb.com/)

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/AryaKS01/Hotel_Rooftop_Blog.git
   cd Hotel_Rooftop_Blog
   ```

2. **Backend Setup**:

   - Navigate to the backend directory:

     ```bash
     cd backend
     ```

   - Install backend dependencies:

     ```bash
     npm install
     ```

   - Create a `.env` file in the `backend` directory with the following environment variables:

     ```env
     MONGODB_URL=your_mongodb_connection_string
     JWT_SECRET_KEY=your_jwt_secret_key
     ```

     Replace `your_mongodb_connection_string` with your MongoDB connection string and `your_jwt_secret_key` with a secret key for JWT authentication.

   - Start the backend server:

     ```bash
     npm run start:dev
     ```

3. **Frontend Setup**:

   - Open a new terminal window and navigate to the frontend directory:

     ```bash
     cd frontend
     ```

   - Install frontend dependencies:

     ```bash
     npm install
     ```

   - Start the frontend application:

     ```bash
     npm run dev
     ```

4. **Access the Application**:

   - Open your browser and navigate to `http://localhost:3000` to access the application.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
