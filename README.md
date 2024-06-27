POSTMAN TESTING EXAMPLES:

POST - http://localhost:4000/api/user/login Body: 
{
    "email": "user12@gmail.com",
    "password": "12"
}

GET - http://localhost:4000/api/user Headers: KEY - Authorization  Value - Bearer <YourTokenAfterLogingIn>

To run - npm run dev (In Backend Folder)
