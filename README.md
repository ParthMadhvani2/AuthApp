# Basic Authentication App with Node.js

This simple authentication application is built using Node.js, Express, MongoDB, and JWT tokens. It provides basic user authentication functionalities like sign-up, login, and token-based authentication.

## Features

- User Sign Up: Register new users with unique email addresses.
- User Login: Authenticate users with email and password.
- JWT Token: Utilizes JSON Web Tokens (JWT) for secure authentication.
- MongoDB: Data storage and retrieval using MongoDB.
- Express: Web server framework for Node.js.
- Nodemon: Automatic server restarts on file changes during development.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/ParthMadhvani2/AuthApp.git
```

2. Navigate to the project directory:
```
cd your-auth-app
```

3. Install dependencies:
```
npm install
```

## Set up environment variables:

1. Create a .env file in the root directory and define the following variables:
```
PORT=3000
MONGODB_URI=your_mongodb_connection_uri
JWT_SECRET=your_secret_key
```

## Usage
1. Start the server:
   ```
   npm start
   ```
3. Use a REST client like Postman to interact with the API endpoints.
4. Access the API endpoints:
- Register a new user: POST /api/auth/register
- Login with existing user: POST /api/auth/login 
- Access protected routes by including the JWT token in the Authorization header.

## API Endpoints
- POST /api/auth/register: Register a new user.
  - Body: { "email": "user@example.com", "password": "password123" }
- POST /api/auth/login: Login with existing user credentials.
  - Body: { "email": "user@example.com", "password": "password123" }
- Protected routes require a valid JWT token in the Authorization header.

## Contributing
Contributions are welcome! Please feel free to open a pull request or submit an issue for any bugs, feature requests, or suggestions.

## License
This project is licensed under the MIT License.
```

Make sure to replace placeholders like `ParthMadhvani2`, `AuthApp`, `your_mongodb_connection_uri`, and `your_secret_key` with actual values specific to your project. Also, depending on your project's complexity, you might want to expand the README with more detailed instructions or explanations.
```
