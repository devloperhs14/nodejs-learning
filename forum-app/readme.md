# STEP 1
Clone the repo & navigate to forum-app folder using: 
```
cd forum-app
```

Next run the follow commands in terminal:
```
npm install bcryptjs body-parser dotenv ejs express express-session mongoose
```

# Step 2
* Change the `env.example` file to `.env` file

* In env do following changes

```
db_connection="your-mongo-db-connection-password"
PORT=3001
SESSION_SECRET='topsecret'
```

# STEP 3
In terminal run:
```
node app.js
```
Open **localhost//3301**

## ERROR?
`Error: listen EADDRINUSE: address already in use :::3001`

head to .env and change the port number
