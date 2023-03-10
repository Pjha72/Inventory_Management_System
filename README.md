# Inventory management 
A MERN stack application i built with mongoDB, Express, React and NodeJS.

## Features
- API endpoints with Express
- Authentication with JSON Web Token including User Registration, Login and Password Reset
- CRUD functionality on various routes(auth, users, allUsers, products, customers). I'll probably add more later
- Upload image with multer and save to folder
- Protect routes to only be accessed by logged-in users
- Frontend pages with React and SCSS
- Routing with React Router V6
- CRUD functionality ( Create Read Update Delete)
- Implement pagination on the front-end
- Connect frontend to backend using Axios
- Manage state with Redux Toolkit
- Dashboard for product management
- Utilize "express-async-handler" package
- Error handling in Express
- Hash passwords
- User profile page
- Contact us page

<!-- Add other features -->

## API docs

### Routes

- `/api/allUsers`: This GET route serves json of all registers users as an array of objects(when parsed).

- `/api/auth`: This route does two things. The GET method authenticates a logged in user(private route and requires a token) by using the token to check for the user. Thereby returning the currently logged in user. The POST method is used for logging in a user and authenticating them. Fields required: one of of `email` or `username` and `password`.

- `/api/customers`: This has GET, POST, PUT and DEL methods. They perform CRUD functionalities for an authenticated user's customers.

- `/api/products`: This has GET, POST, PUT and DEL methods. They perform CRUD functionalities for an authenticated user's products.

- `/api/users`: This has POST, PUT and DEL methods. They respectively create users, edit users' details and delete users.

-----------------
