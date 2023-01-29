# Activity 3 - Post Name 

Create a route **"/name"** where user can send first name and last name in the body as JSON and get their full name back as JSON. 

**Request (POST):** 
```
{

 "firstname": "John", 

"lastname": "Doe"

}
```
**Response (POST):** 
```
{

 "fullname": "John, Doe" 

}
```