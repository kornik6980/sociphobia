# Sociophobia - social media app

A social media MERN CRUD app project I created to practice web development skills.

## Table of Contents

- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

App includes all of the most important features of social media pp like:

- creating and account and logging in with authorization and verification
- adding posts with pictures
- likes
- adding friends
- viewing other profile's pages
- light and dark mode
- responsible

## Technologies

### Server-side Technologies

- Node.js
- Express.js
- body-parser
- cors
- dotenv
- Helmet
- jsonwebtoken
- mongoose
- morgan
- multer
- multer-gridfs-storage
- bcrypt
- gridfs-stream

### Client-side Technologies

- React
- React DOM
- React Router DOM
- React Redux
- Redux Toolkit
- formik
- yup
- @emotion/react
- @emotion/styled
- @mui/icons-material
- @mui/material
- react-dropzone
- web-vitals
- @testing-library/jest-dom
- @testing-library/react
- @testing-library/user-event
- dotenv
- react-scripts

## Installation

1.  Clone the repository: `git clone https://github.com/kornik6980/app`
2.  Navigate to the server directory: `cd app/server`
3.  Install server dependencies: `npm install`
4.  Navigate to the client directory: `cd ../client`
5.  Install client dependencies: `npm install`

## Usage

1.  Start the server:

    - Navigate to the server directory: `cd ../server`
    - Add .env file with `MONGO_URL`, `PORT` and `JWT_SECRET` token
    - Run the server in development mode: `npm run dev`
    - The server will start running on `http://localhost:PORT`

2.  Start the client:

    - Open a new terminal or command prompt.
    - Navigate to the client directory: `cd app/client`
    - Start the client app: `npm start`
    - The client app will open in your default browser at `http://localhost:3000`

Make sure to start the server first before starting the client to ensure proper communication between them.

The server folder contains the server-side code and dependencies, while the client folder contains the client-side code and dependencies.

Please adjust the file paths and commands as necessary based on your project's directory structure and scripts configuration.

If you have any further questions, feel free to ask!

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvement, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
