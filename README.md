# MERN Stack Real Estate

## Project Description

MERN Stack Real Estate is a full-featured web application designed to facilitate the buying and selling of properties.
Utilizing the powerful MERN stack (MongoDB, Express.js, React, and Node.js), this platform offers a seamless and secure experience for users to list their properties
for sale and contact property owners if they are interested in making a purchase.
With the integration of cutting-edge technologies, including Google authentication, the application ensures secure and efficient user authentication.

## Features

- **User Authentication**: Secure user login and registration with JWT (JSON Web Tokens) to protect user data.
- **Google Authentication**: Integrated Google OAuth for seamless and quick authentication.
- **Property Listing**: Users can list their properties for sale with detailed descriptions, images, and pricing.
- **Property Search**: Browse and search for properties based on various criteria.
- **Contact Owners**: Interested buyers can contact property owners directly through the platform.
- **Responsive Design**: Optimized for both desktop and mobile devices, ensuring a smooth experience on any screen size.

## Technologies Used

- **Frontend**: React.js
- **Backend**: Node.js with Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens) and Google OAuth
- **Styling**: CSS, Bootstrap

## Getting Started

### Prerequisites

- Node.js
- MongoDB
- Google Cloud account for OAuth setup

### Installation

1. **Clone the repository:**

   ```bash
   https://github.com/abhishekiiitbh2903/E-STATE-MERN-STACK.git
   cd E-STATE-MERN-STACK
   ```

2. **Install dependencies for both frontend and backend:**

   ```bash
   # Install backend dependencies
   npm install

   # Install frontend dependencies
   cd ../client
   npm install
   ```

3. **Set up environment variables:**

   Create a `.env` file in the `root` directory and add the following:

   ```plaintext
   MONGO=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```
   Create a `.env` file in the `client` directory and add the following:

   ```plaintext
   FIREBASE=your_firebase_api_key
   ```

4. **Run the application:**

   ```bash
   # Start the backend server
   npm run dev

   # Start the frontend development server
   cd ../client
   npm run dev
   ```

5. **Access the application:**

   Open your browser and go to `http://127.0.0.1/5173` to start using the MERN Stack Real Estate application.

## Contributing

We welcome contributions to enhance the features and capabilities of this project. If you have suggestions or improvements, please fork the repository and create a pull request.
I am open to any genuine pull request .Let's see what we can change ...

For any questions or issues, please open an issue on the GitHub repository or contact us directly.

Happy property hunting and selling!
