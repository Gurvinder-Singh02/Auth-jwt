# Auth-express-jwt-html

Simplified Express app with jwt verification with a simplest frontend you can use postman also
data is stored in js object on the server

## Features
- **Sign Up**: Register users
- **Sign In**: Authenticate and get JWTs
- **Get User Info**: Retrieve user details

## Usage
1. Clone: `git clone https://github.com/-Singh02/express-mongo.git`
2. Install: `npm install`
3. Run: `node index.js`


**POST /signup**
```json
{ 
    "username": "gurvinder", 
    "password": "yourpassword", 
}
```

**POST /signin**
```json
{ 
    "username": "gurvinder", 
    "password": "yourpassword" 
}
```

**GET /me**
- Include header: `token: the output you get in signin`

