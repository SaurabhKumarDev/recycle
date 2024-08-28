# E-Commerce Website

This is a full-stack e-commerce website built using the MERN stack (MongoDB, Express.js, React, Node.js). The application includes functionalities such as a shopping cart, payment processing, real-time notifications, and secure user authentication.

## Features

- **Shopping Cart:** Manage and review items in the shopping cart.
- **Payment Integration:** Secure payment processing using Razorpay.
- **Real-Time Notifications:** Receive live updates and alerts.
- **User Authentication:** Secure login and registration using JWT and OAuth.
- **Email Notifications:** Automated emails for order confirmation and updates.
- **State Management:** Efficient state management using Redux.

## Tech Stack

- **Frontend:**
  - [React](https://reactjs.org/): JavaScript library for building user interfaces.
  - [Tailwind CSS](https://tailwindcss.com/): Utility-first CSS framework for styling.
  - [Material UI (MUI)](https://mui.com/): React component library for modern UI design.
  - [Redux](https://redux.js.org/): State management library for handling complex application state.

- **Backend:**
  - [Node.js](https://nodejs.org/): JavaScript runtime for server-side development.
  - [Express.js](https://expressjs.com/): Web application framework for Node.js to build the API.

- **Database:**
  - [MongoDB Atlas](https://www.mongodb.com/cloud/atlas): Cloud-hosted MongoDB service for storing data.

- **Payment Gateway:**
  - [Razorpay](https://razorpay.com/): Payment gateway for processing transactions securely.

- **Modules:**
  - [JWT](https://jwt.io/): JSON Web Tokens for user authentication.
  - [OAuth](https://oauth.net/): Authorization framework for secure access.
  - [Bcrypt](https://www.npmjs.com/package/bcrypt): Password hashing for security.
  - [UID](https://www.npmjs.com/package/uid): Generating unique identifiers.
  - [Nodemailer](https://nodemailer.com/): Email sending library for notifications.
  - [Session](https://www.npmjs.com/package/express-session): Session management for user sessions.

## Installation

### Frontend

1. Clone the repository:
   ```bash
   git clone https://github.com/saurabhkumardev/recycle.git
   ```

2. Navigate to the frontend directory:
    ```bash
    cd recycle/frontend
    ```

3. Install dependencies:
    ```bash
    npm install
    ```

### Backend

1. Navigate to the backend directory:
    ```bash
    cd recycle/backend
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Create a .env file in the backend directory and add your environment variables. For example:
    ```env
    MONGO_URI=your_mongodb_atlas_connection_string
    JWT_SECRET=your_jwt_secret
    RAZORPAY_KEY=your_razorpay_key
    RAZORPAY_SECRET=your_razorpay_secret
    ```

## Usage

1. Start the backend server:
    ```bash
    cd recycle/backend
    npm start
    ```

2. Start the frontend development server:
    ```bash
    cd recycle/frontend
    npm start
    ```

3. Open your browser and visit `http://localhost:3000` to access the application.

## Deployment

  - Frontend: Deployed on Netlify. Visit [your-frontend-netlify-url] to view the live application.
  - Backend: Deployed on Cyclic. Visit [your-backend-cyclic-url] to access the backend services.

## Contributing

1. Fork the repository.

2. Create a new branch:
    ```bash
    git checkout -b feature/your-feature
    ```

3. Commit your changes:
    ```bash
    git commit -m "Add your commit message"
    ```

4. Push to the branch:
    ```bash
    git push origin feature/your-feature
    ```

5. Create a pull request with a description of your changes.
