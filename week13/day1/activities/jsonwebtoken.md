
# Activity 1 - Creating and Returning JSON Web Token

In this activity you will use jsonwebtoken Node package to create a JWT token and return it to the client.  

Create a brand new Node project using the following: 

`npm init`

**Install the following packages:** 

`npm install express` 

`npm install jsonwebtoken` 

Create a route called `"/token"`. This route will create the jsonwebtoken and return the token in a JSON format as follows: 

```
{"token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJzdWIiOiIxMjM0NTY3ODkwIiwibmFtZSI6IkpvaG4gRG9lIiwiaWF0IjoxNTE2MjM5MDIyfQ.SflKxwRJSMeKKF2QT4fwpMeJf36POk6yJV_adQssw5c" }
```

* Please note that you token value will be different 