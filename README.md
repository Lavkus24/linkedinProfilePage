## [Backend Part](https://github.com/Lavkus24/Link_backend)




![Screenshot 2024-05-14 183624](https://github.com/Lavkus24/linkedinProfilePage/assets/106608679/0c481058-17a0-4499-9ae4-46a5eb115cf0)
![Screenshot 2024-05-14 183557](https://github.com/Lavkus24/linkedinProfilePage/assets/106608679/bd660363-9c70-4adf-94b9-beacc39eab3f)

# LinkedIn Profile Page Clone

This project is a clone of the LinkedIn profile page, built using the MERN stack (MongoDB, Express.js, React.js, Node.js). It allows users to create an account, add their education, about, address, and skills information, and provides an option to edit these fields according to their needs. The project utilizes hooks for managing component state and Redux for state management, as well as JSON Web Tokens (JWT) for authorization and authentication.


## Features

- User Authentication: Implements JWT for secure user authentication and authorization.
- Profile Page: Displays user profile information similar to LinkedIn's profile page layout , followed by an editing feature allowing users to supplement and modify their education, about, address, and skills 
  information as desired.
- Redux State Management: Utilizes Redux for managing application state and data flow.
- Hooks: Utilizes React hooks for managing component state and lifecycle.
- MongoDB Database: Stores user information, profile data, and user-generated content in a MongoDB database.


## Technologies Used

- MongoDB: NoSQL database used for storing user information and profile data.
- Express.js: Web application framework for building RESTful APIs.
- React.js: Frontend library for building user interfaces.
- Node.js: JavaScript runtime environment for server-side development.
- Redux: State management library for managing application state.
- JSON Web Tokens (JWT): Used for secure user authentication and authorization.
- React Hooks: Used for managing component state and lifecycle.
- HTML/CSS: Markup and styling languages for building user interface elements.

## Setup Instructions

1. Clone the repository: `git clone <repository-url>`
2. Navigate to the project directory: `cd linkedin-profile-page`
3. Install dependencies: `npm install`
4. Set up environment variables: Create a `.env` file in the root directory and configure environment variables such as MongoDB connection string, JWT secret key, etc.
5. Start the server: `npm start`
6. Open your web browser and visit: `http://localhost:3000`

## Project Structure

- `client`: Frontend code written in React.js.
- `server`: Backend code written in Node.js using Express.js.
- `models`: MongoDB database models and schema definitions.
- `routes`: Express.js routes for defining API endpoints.
- `middleware`: Custom middleware functions for request validation, error handling, authentication, etc.
- `actions`: Redux action creators for managing state updates.
- `reducers`: Redux reducers for handling state changes.

## [Backend Part](https://github.com/Lavkus24/Link_backend)
