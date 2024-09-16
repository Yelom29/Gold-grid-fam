# React + Vite

# React Portal Application

This project is a **React Portal** with the following features:

- User Registration
- User Login
- List of Registered Users and last login time

## Table of Contents

1. [Demo](#demo)
2. [Features](#features)
3. [Technologies](#technologies)
4. [Installation](#installation)
5. [Running the Application](#running-the-application)
6. [Folder Structure](#folder-structure)
7. [API Endpoints](#api-endpoints)
8. [Contributing](#contributing)
9. [License](#license)

---

## Demo

Provide a link here to the live demo of the portal if available.

## Features

- **User Registration:** Users can register with an email and password.
- **User Login:** Users can log in using registered credentials.
- **List Users:** Display a list of all registered users and last login.

## Technologies

- **React.js** for the frontend.
- **Tailwind CSS** for styling.
- **AWS Lambda** for serverless backend functions.
- **Axios** for API requests.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/BensonGathu/azubi-frontend.git
   ```

2. Navigate to the project directory:

   ```bash
   cd azubi-frontend
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

4. Run the development server:

   ```bash
   npm run dev
   ```

## Folder Structure

```
.
├── public
├── src
│   ├── pages
│   │   ├── Login.jsx
│   │   ├── Register.jsx
│   │   ├── Dashboard.jsx
│   │   ├── LandingPage.jsx
│   ├── styles
│   │   └── tailwind.css  
│   ├── App.jsx
│   ├── main.jsx
├── .env
├── package.json
├── tailwind.config.js 
├── postcss.config.js 
├── README.md
```

## API Endpoints

Your backend is powered by **AWS Lambda Functions**:

- **POST** `/register`: Registers a new user.
- **POST** `/login`: Authenticates a user and returns a token.
- **GET** `/userdata`: Fetches a list of all registered users (requires authentication).

## Contributing

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch-name`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-branch-name`.
5. Submit a pull request.

## License

This project is licensed under the MIT License.
