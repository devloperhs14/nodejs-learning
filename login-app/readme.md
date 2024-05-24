# STEP 1
Clone the repo

# Step 2
* Navigate to login-app folder using:
  ```
  cd login-app
  ```
  
* Change the `env.example` file to `.env` file

* In env do following changes

```
db_connection="mongodb+srv://username:mypassword@dbname.juksftb.mongodb.net/?retryWrites=true&w=majority&appName=StackUpNodeII"
PORT=3001
SESSION_SECRET='topsecret'
```
make sure to replace username, password and dbname with yours

# STEP 3
In terminal run:
```
node app.js
```
Open **localhost//3301**

## ERROR?
`Error: listen EADDRINUSE: address already in use :::3001`
head to .env and change the port number
