# Zephyr Feed
Welcome to the Zephyr Feed project! Zephyr Feed is a social media application inspired by Twitter, built using React.js, MongoDB, Node.js, Express, Tailwind CSS, and React Query. It offers a modern and feature-rich platform for social networking and content sharing.



## Features
-Authentication with JSONWEBTOKENS (JWT): Secure user authentication using JSON Web Tokens.

-React Query: Efficient data fetching, caching, and state management.

-Suggested Users: Display suggestions for users to follow based on interests.

-Posts Management:

    -Create new posts.
    
    -Delete owned posts.
    
    -Like and comment on posts.
    
-Profile Management:

    -Edit profile information.
    
    -Upload and manage cover image and profile image using Cloudinary.
    
-Notifications: Receive notifications for likes, comments, and follows.



## Technology Used

### Frontend Technologies:

React.js:   A JavaScript library for building user interfaces, providing a fast and interactive frontend experience.

Tailwind CSS:   A utility-first CSS framework that helps in quickly styling components with a modern and responsive design.

React Query:   A powerful data-fetching library for managing and caching API data in React applications, optimizing performance.


### Backend Technologies:

Node.js:  A runtime environment for executing JavaScript code outside of a web browser, used for server-side development.

Express:  A minimalist web framework for Node.js that simplifies routing, middleware creation, and API handling.

MongoDB:  A NoSQL database that stores data in flexible, JSON-like documents, providing scalability and flexibility for storing user data.

Mongoose: An ODM (Object Data Modeling) library for MongoDB and Node.js, facilitating schema-based modeling for application data.


### Other Tools and Libraries:

JSON Web Tokens (JWT):  Used for secure authentication by generating tokens that verify user identity.

Cloudinary:   A cloud-based image and video management service used for uploading and managing user profile images and media files.

dotenv:   A module that loads environment variables from a .env file into process.env, enabling secure configuration of sensitive data.

Axios:   A promise-based HTTP client for making API requests from the frontend to the backend server.

bcrypt.js:  A library used for hashing passwords to securely store and manage user authentication credentials.

moment.js:   A library for parsing, validating, manipulating, and formatting dates and times in JavaScript.



#### Create a .env file in the root directory and configure the following variables:
    MONGO_URI=

    PORT=

    JWT_SECRET=

    NODE_ENV=

    CLOUDINARY_CLOUD_NAME=

    CLOUDINARY_API_KEY=

    CLOUDINARY_API_SECRET=



#### Usage
-Authentication: Sign up or log in to start using Zephyr Feed.

-Explore Features: Navigate through the home feed, profile, notifications, and other pages.

-Create posts, like and comment on posts, follow other users, and update profile settings.
