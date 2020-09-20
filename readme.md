
# tech

Express.js — A node.js framework that makes it easy to build web applications.

mongodb — Official MongoDB driver for Node.js

mongoose — An object modeling tool designed to work in an asynchronous environment. We shall use mongoose to define database schemas and interact with the database.

bcrypt.js — This will help us hash user passwords before storing them into the database.

validator — We shall use this package to validate and sanitize user input, for example, we need to ensure that a user gives us an email in the right format.

Jsonwebtoken — JSON Web Token(JWT) will be used for authentication and authorization. This package will help to set up protected routes that only logged in users can access.

env-cmd — This will enable us to create and manage environment variables in our project.

nodemon — Nodemon will re-run the express server every time we make changes to our code.

# routes

HTTP POST /users — Register users.
HTTP POST /users/login — Allow users to login.
HTTP GET / users/me — Get user profile.
HTTP POST /users/logout —Logout the user
HTTP post /users/logoutall — Logout from all devices.

# env file

MONGODB_URL=mongodb+srv://username:<password>@cluster0-e1zyx.mongodb.net/<dbname>?retryWrites=true&w=majority
JWT_KEY=WinterIsComingNEW2023
PORT=3000