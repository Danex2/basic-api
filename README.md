## Node/express backend with react frontend
The app is called devconnector, following the "MERN stack front to back" videos from udemy.

## What I hope to learn by the end of this
This will teach me how to make an api with node/express on the backend and have react display that data on the front end. I will learn things like, authenticating a user, adding a new user to the database and user sessions.

## Technologies used
React  
Node.js  
Express  

## Routes

### Profile

Public Routes  
``GET: api/profile/all`` - Get all profiles  
``GET: api/profile/handle/:handle`` - Get user by handle  
``GET: api/profile/user/:user_id`` - Get user by user id  

Private routes  
``GET: api/profile`` - Get the currently logged in user's profile  
``POST: api/profile`` - Create a new profile for the registered user  
``POST: api/profile/experience`` - Add experience for the registered user  
``POST: api/profile/education`` - Add education from the registered user  
``DELETE: api/profile/experience/:exp_id`` - Remove experience from the users profile  
``DELETE: api/profile/education/:edu_id`` - Remove education from the users profile  
``DELETE: api/profile`` - Remove the whole account  

### User
Public Routes  
``GET: api/users/register`` - Register a new user  
``GET: api/users/login`` - Login as a registered user  

Protected
``GET: api/users/current`` - Get the current logged in user  
