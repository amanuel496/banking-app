
# Banking Application

This repository contains a full-stack banking application, encompassing both frontend and backend components.

## Overview

The Banking Application is designed to simulate basic banking operations, including:

- User authentication and account management
- Viewing account balances
- Performing deposits and withdrawals
- Transferring funds between accounts
- Viewing transaction history

## Project Structure

The project is divided into two main components:

- **Frontend:** Handles the user interface and user experience aspects of the application.
- **Backend:** Manages the business logic, database interactions, and API endpoints.

For detailed information on each component, refer to their respective repositories:

- Frontend Repository: [banking-app-frontend](https://github.com/amanuel496/banking-app-frontend)
- Backend Repository: [banking-app-backend](https://github.com/amanuel496/banking-app-backend)

## Features

- **User Registration and Authentication:** Secure sign-up and login functionalities.
- **Account Management:** Create and manage multiple bank accounts per user.
- **Transactions:**
  - Deposit and withdraw funds.
  - Transfer funds between your accounts.
  - View detailed transaction history.

## Technologies Used

- **Frontend:**
  - React.js
  - HTML5 and CSS3
  - JavaScript (ES6+)
- **Backend:**
  - Node.js with Express.js
  - MongoDB (Mongoose ORM)
- **Authentication:** JSON Web Tokens (JWT)
- **Version Control:** Git

## Getting Started

To set up the project locally, follow these steps:

### Prerequisites

- Node.js (v14.x or higher)
- MongoDB
- Git

### Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/amanuel496/banking-app.git
   cd banking-app
   ```

2. **Install Dependencies:**

   - **Backend:**

     ```bash
     cd backend
     npm install
     ```

   - **Frontend:**

     ```bash
     cd ../frontend
     npm install
     ```

3. **Configure Environment Variables:**

   - Create a `.env` file in the `backend` directory with the following variables:

     ```env
     PORT=5000
     MONGODB_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     ```

4. **Run the Application:**

   - **Backend:**

     ```bash
     cd backend
     npm start
     ```

   - **Frontend:**

     ```bash
     cd ../frontend
     npm start
     ```

   The frontend should be accessible at `http://localhost:3000`, and the backend API at `http://localhost:5000`.

## Usage

1. **Register a New User:** Sign up with a new account through the frontend interface.
2. **Create Bank Accounts:** After registration, create one or more bank accounts.
3. **Perform Transactions:**
   - Deposit or withdraw funds.
   - Transfer funds between your accounts.
4. **View Transaction History:** Access the transaction history for each account.

## Contributing

Contributions are welcome! To contribute:

1. **Fork the Repository**
2. **Create a Feature Branch:**

   ```bash
   git checkout -b feature/YourFeatureName
   ```

3. **Commit Your Changes:**

   ```bash
   git commit -m 'Add some feature'
   ```

4. **Push to the Branch:**

   ```bash
   git push origin feature/YourFeatureName
   ```

5. **Open a Pull Request**

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
