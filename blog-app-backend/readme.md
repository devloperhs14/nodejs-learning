# STEP 1
Clone the repo & navigate to login-app folder using: 
```
cd blog-app-backend
```

Next run the follow commands in terminal:
```
npm install express morgan body-parser
```

# STEP 2
In terminal run:
```
node app.js
```
Open **[localhost//3301](http://localhost:3001/auth/test)**


# STEP 3
Open webpage:
* Unauthorised Access:  localhost:3001/user/test
* Authorised Access: localhost:3001/auth/test
```
node app.js
```
Open **localhost//3301**


## ERROR?
`Error: listen EADDRINUSE: address already in use :::3001`

head to .env and change the port number
