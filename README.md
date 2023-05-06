# Sid-Share

Sid-Share is a social media website that allows users to share their thoughts, images, and messages with the world. The application is built using the MERN (MongoDB, Express.js, React, and Node.js) stack and features authentication, post creation, like and comment functionality, and more. This project was created as part of my learning experience in the FreeCodeCamp's MERN Stack course.

## Features

- User authentication: users can sign up, log in, and log out of the website.
- Post creation: users can create new posts by adding a title and a body.
- Like and comment functionality: users can like and comment on posts created by other users.
- User profiles: each user has a profile that displays their username and their posts.
- User feed: the user feed displays the posts of all users in reverse chronological order.

## Installation

To install Sid-Share, follow these steps:

1. Clone the repository: `git clone https://github.com/s166harth/sid-share.git`.
2. Install the dependencies by running `npm install` in both the client and server directories.
3. Create a `.env` file in the server directory with the following contents:

```
MONGODB_URI=<your MongoDB connection string>
JWT_SECRET=<your JWT secret>
```

4. Start the development server by running `npm start` in both the client and server directories.

## Technologies Used

- MongoDB: a NoSQL database used to store user data and posts.
- Express.js: a web application framework used to build the server-side API.
- React: a JavaScript library used to build the client-side user interface.
- Node.js: a JavaScript runtime used to build the server-side API.
- Apollo Server: a GraphQL server used to handle requests and responses.
- Apollo Client: a GraphQL client used to communicate with the server.
- JWT: a JSON Web Token used for user authentication.

## Deployment

The application is deployed using Heroku. You can access the live version of the application at https://sid-share.herokuapp.com/.

## Contributing

If you would like to contribute to this project, feel free to fork the repository and submit a pull request. Alternatively, you can report bugs or suggest new features by creating an issue.


![sidshare](https://user-images.githubusercontent.com/56957437/159137865-e903e1f5-687c-412a-86b4-05791173b57a.gif)



